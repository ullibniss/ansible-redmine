# ansible-redmine

Lightweight Redmine deploy role

---

## Usage

Role consists of 5 tasks

- Deploy redmine: deploy.yml
- Start redmine: start.yml
- Stop redmine: stop.yml
- Restart redmine: restart.yml
- Show redmine logs: logs.yml

You can use this tasks separate or together, in playbooks or in other roles.

To call task use redmine_action variable:

```yaml
---
- hosts:
  roles:
  - role: redmine
    redmine_action: deploy
```

You can also see example of usage on [example branch](https://github.com/ullibniss/ansible-redmine/tree/example)



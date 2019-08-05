# ansible-redis

- Install Redis Servers with Ansible.
- OS: CentOS 7

## Before Install
- Use DNS Server or update /etc/hosts for all servers.

### Install Redis Server.
- Run the playbook.

```
ansible-playbook -i hosts redis.yml
```

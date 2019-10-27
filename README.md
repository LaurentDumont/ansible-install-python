Ansible role template
=========

{Summary of the role objectives and functions.}

Role Variables
--------------

{ List of the variables of the role}

```yaml
users:
  - username: patate1
    name: Jean Bon
    admin: true
    ssh_key: https://github.com/not_my_keys.keys
  - username: ansible
    name: Ansible
    admin: true
    ssh_key: public_ssh_hash_here
```

Example Playbook
----------------

This is an example of how to use this role:

```yaml
---
- hosts: debian
  become: yes
  roles:
    - users

```

License
-------

MIT

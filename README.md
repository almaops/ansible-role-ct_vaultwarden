Role Name
=========

This role installs Docker container with [Vaultwarden](https://github.com/dani-garcia/vaultwarden).

Requirements
------------

Docker container engine and Python's Docker module installed on target host

Role Variables
--------------

see [./defaults/main.yml](./defaults/main.yml)

Dependencies
------------

No specific dependencies

Example Playbook
----------------

```
- hosts: servers
  become: yes
  roles:
    - role: almaops.ct_vaultwarden
```

License
-------

[MIT License](./LICENSE)

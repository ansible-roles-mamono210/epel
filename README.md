[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/epel/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/epel/tree/main)

Role Description
=========

Installs [EPEL](https://docs.fedoraproject.org/en-US/epel/) for CentOS7 / Stream 8.

Requirements
------------

None

Role Variables
--------------

```YAML
---
epel_disable: false
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - epel
```

License
-------

BSD

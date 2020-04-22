[![](https://github.com/ansible-roles-matsumura/exa/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3ABuild)
[![](https://github.com/ansible-roles-matsumura/exa/workflows/Lint/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3ALint)
[![](https://github.com/ansible-roles-matsumura/exa/workflows/Trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3A%22Trailing+whitespace%22)

Role Description
=========

Installs [exa](https://github.com/ogham/exa) for CentOS7.

Requirements
------------

None

Role Variables
--------------

None

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
    - exa
```

License
-------

BSD

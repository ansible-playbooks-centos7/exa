[![](https://github.com/ansible-roles-matsumura/exa/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/exa/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/exa/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/exa/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/exa/actions?query=workflow%3Ayamllint)

Role Description
=========

Installs [exa](https://github.com/ogham/exa) for CentOS7/CentOS8

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

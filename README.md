Java
====

An Ansible role to install Java.

Requirements
------------

- Supported version of Ansible: 2.12 and highter.
- Supported platforms:
  - Debian
    - 10
    - 11
    - 12
  - RHEL
    - 7
    - 8
    - 9
  - Ubuntu
    - 18.04
    - 20.04
    - 22.04

Role Variables
--------------

- `java_package` `Java` package name (see default values in `vars/*.yml`).

Dependencies
------------

None.

Example Playbook
----------------

Install `Java` package:

```yaml
---
- name: 'Install Java package'
  hosts: all

  roles:
    - role: antmelekhin.java
```

License
-------

MIT

Author Information
------------------

Melekhin Anton.

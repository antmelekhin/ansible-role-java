Java
====

An Ansible role to install the Java package. This role installs the `OpenJDK` or `Amazon Corretto` distribution.

Requirements
------------

- Supported version of Ansible: 2.12 and highter.
- Supported platforms:
  - Amazon Linux
    - 2
    - 2023
  - Debian
    - 10
    - 11
    - 12
  - Fedora
    - 39
    - 40
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

All variables which can be overridden are stored in `defaults/main.yml` file as well as in `meta/argument_specs.yml`.
Similarly, descriptions and defaults for preset variables can be found in the `vars/` directory.

Dependencies
------------

None.

Example Playbook
----------------

Install the `Java` package:

```yaml
---
- name: 'Install the Java package'
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

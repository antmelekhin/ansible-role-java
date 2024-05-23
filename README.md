Java
====

An Ansible role to install the `Java` package.

Requirements
------------

- Supported version of Ansible: 2.12 and highter.
- Supported platforms:
  - Amazon Linux
    - all
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

- `java_package` The Java package name (see default values in `vars/*.yml`).
- `java_home` The JAVA_HOME environment variable is used to specify the location of the Java executable files.

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

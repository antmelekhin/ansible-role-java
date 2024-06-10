Java
====

An Ansible role to install the `Java` package.

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

- `java_distribution` The Java package distribution type. Available values are: `openjdk` (default), `corretto`.
- `java_openjdk_package_name` The OpenJDK package name (see default values in `vars/*.yml`).
- `java_corretto_repository_mirror_url` The Amazon Corretto repository mirror.
  - `https://yum.corretto.aws` (for RedHat based distributions)
  - `https://apt.corretto.aws` (for Debian based distributions)
- `java_corretto_repository_gpgkey_url` URL to Amazon Corretto GPG key file.
  - `https://yum.corretto.aws/corretto.key` (for RedHat based distributions)
  - `https://apt.corretto.aws/corretto.key` (for Debian based distributions)
- `java_corretto_package_name` The Amazon Corretto package name (see default values in `vars/*.yml`).
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

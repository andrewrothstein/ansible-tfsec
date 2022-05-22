andrewrothstein.tfsec
=========

![Build Status](https://github.com/andrewrothstein/ansible-tfsec/actions/workflows/build.yml/badge.svg)

Installs AquaSec [tfsec](https://github.com/aquasecurity/tfsec).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.tfsec
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>

ipv6-support
============

Ansible role for configuring IPv6 support on Debian- or RHEL6-based systems

Requirements
------------

None, however there is an option to configure IPv6 support in Postfix if installed.

Role Variables
--------------

 defaults:

  - ipv6_enabled: true
  - ipv6_configure_postfix: false

Dependencies
------------

none

Example Playbook
----------------

    - hosts: all
      roles:
         - role: mgoodness.ipv6-support
         - ipv6_enabled: false
         - ipv6_configure_postfix: true

License
-------

Apache License, Version 2.0

Author Information
------------------

[Michael Goodness](https://plus.google.com/+MichaelGoodness)

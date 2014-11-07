staenker.ipv6-support
=========

Ensures that ipv6 is either enabled or disabled on a Debian based system.

Requirements
------------

A Debian based system is enough

Role Variables
--------------

 - enabled, default: true

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: staenker.ipv6-support, enabled: false }

License
-------

Apache License, Version 2.0

Author Information
------------------

Awesome dude

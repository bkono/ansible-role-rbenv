bkono.rbenv
=========

Setup rbenv, with automatic installation of ruby interpreters. Defaults to all users installation via /usr/local.

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

    - hosts: servers
      roles:
         - bkono.rbenv

License
-------

MIT / BSD

Author Information
------------------

This role was created by [Bryan Konowitz](https://github.com/bkono).

Debian-Mysql
============

The world's most popular open source database

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-mysql }

Tasks
-----

  - Install [MySQL](http://www.mysql.com/) server and client


License
-------

BSD

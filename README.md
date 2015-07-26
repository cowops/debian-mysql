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
         - { role: loranger.debian-mysql }

Tasks
-----

  - Install [MySQL](http://www.mysql.com/) server and client
  - Install [libmysqlclient-dev](http://packages.debian.org/search?lang=fr&searchon=names&keywords=libmysqlclient-dev)
  - Install [mytop](http://jeremy.zawodny.com/mysql/mytop/)
  

License
-------

BSD
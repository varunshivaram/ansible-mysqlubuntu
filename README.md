Role Name
=========

This role installs MySQL on Debian/Ubuntu systems with a default database admin and user root with all privileges on localhost the password can be found in the vars directory.

Requirements
------------
Python 2.7 or higher , pip and the package python-mysqldb

Role Variables
--------------

The settable variables are available in vars/main.yml. They are:
db_name , db_user and db_password

Example Playbook
----------------

Including an example of how to use the role in ansible playbooks:

    - hosts: servers
      roles:
         - { role: varunshivaram.ansible-mysqlubuntu, x: 42 }

License
-------

BSD

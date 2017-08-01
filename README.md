Role Name
=========

Installs openvm tools for centos 6/redhat

Requirements
------------

none

Role Variables
--------------
Defaults for tools-openvm:

platform: 'Redhat'
virtualization_type: 'VMware'

Dependencies
------------
none

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

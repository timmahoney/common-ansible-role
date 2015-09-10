Common Ansible Role
===================

This role takes care of several common tasks that should be taken care of on each machine in the infrastructure

Requirements
------------

This role is CentOS specific

Role Variables
--------------

You can override several defaults:

* machine_locale: String. Set the locale, default is  "es_US.utf8"
* machine_timezone: String. Set the timezone, default is "UTC"
* machine_packages: List. Default is empty list. Install specific standard packages onto the machines in your infrastructure.


Example Playbook
----------------

- hosts: servers
  roles:
  - common

License
-------

GPLv2

Author Information
------------------

Tim Mahoney
http://timothymahoney.com

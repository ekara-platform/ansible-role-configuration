Role Name
=========

Role to use to load all platform configuration.

Requirements
------------

None.

Role Variables
--------------

- input_dir: input directory to load configuration files. 

This role returns a dict variable : **lagoon_configuration_params** which contains all configuration.


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------


    - hosts: localhost
      roles:
         - { role: lagoon.configuration, config_dir: /opt/inputs }

License
-------

MIT

Author Information
------------------

https://github.com/lagoon-platform/ansible-role-configuration

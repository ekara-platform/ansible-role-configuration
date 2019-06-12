Role Name
=========

Role used to load ekara configuration file and check for required play vars, environment vars and ekara parameters.

Requirements
------------

None.

Role Variables
--------------

- input_dir: input directory to load configuration file from. 

This role register a dict variable, **ek_config**, which contains validated configuration.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- name: Load ekara configuration
  include_role:
    name: ekara.config
  vars:
    input_dir: /opt/input_dir
    required_vars:
      - requiredVar
    required_env_vars:
      - REQUIRED_ENV_VAR
    required_params:
      - requiredParam
```

License
-------

MIT

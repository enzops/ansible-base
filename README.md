ansible-base
=========
Simple role to install a fresh deployed server.

Requirements
------------

debian-family

Role Variables
--------------

| Variable            | Required | type   | Comments |
|---------------------|----------|--------|----------|
| base_hostname       | no       | string |          |
| base_locale         | no       | list   |          |
| base_timezone       | np       | string |          |
| base_repos          | no       | list   |          |
| base_pkg            | no       | list   |          |
| base_users          | no       | list   |          |
| base_shell          | no       | list   |          |
| base_swapiness      | no       | bool   |          |
| base_sudoers        | no       | list   |          |
| base_authorizedkeys | no       | list   |          |

Dependencies
------------

ansible.community.general

Add in your playbooks requirements
----------------

```yaml
- src: https://github.com/enzops/ansible-base
  name: enzops.base
  version: latest
```

License
-------

MIT

Author Information
------------------

[github.com/enzops](https://github.com/enzops)

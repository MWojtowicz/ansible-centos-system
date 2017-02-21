Role Name
=========

This role allows to manage packages required by playbook, and hostnames

Role Variables
--------------

```
system_packages: []
host_names: []
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: MWojtowicz.system }

License
-------

MIT

Clickhouse
=========

This role can install Clickhouse on Centos 7

Role Variables
--------------

|vars|description|
|--------|-------------|
|clickhouse_version|Version of Clickhouse|

Example Playbook
----------------

```
- name: Clickhouse | Install
  hosts: servers
  roles:
    - clickhouse
```

License
-------

MIT

Author Information
------------------

ArsalanSan

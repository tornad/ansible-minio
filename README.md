Minio server
=========

> Setup a [minio] server

Requirements
------------

There is no requirements

Role Variables
--------------

```yaml
minio_bin: /usr/local/bin/minio
minio_user: minio
minio_group: minio
minio_envfile: /etc/default/minio
minio_datadirs: []
minio_addr: ":9000"
minio_opts: ""
minio_access_key: "myAccessKey"
minio_secret_key: "mySecretKey"
```

Dependencies
------------

There is no dependencies

Example Playbook
----------------

```ymal
- hosts: servers
  roles:
  - { role: SimpliField.minio }
```

License
-------

BSD


[minio]: https://minio.io

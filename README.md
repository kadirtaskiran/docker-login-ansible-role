# docker-login-ansible-role

Ansible role to perform docker logins.

Role Variables
--------------

```
ansible_python_interpreter: "/usr/bin/python3"
dockerpy_version: 4.2.0
docker_registries: []
```

Registries  Examples
----------
```
docker_registries:
  # docker hub
  - url: index.docker.io
    username: XXX
    password: ZZZ
  # if your registry require email
  - url: my.custom.registry
    username: XXX
    password: ZZZ
    email: something@yourcompany.com
```
License
-------

Apache License 2

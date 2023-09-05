[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/christopherlouet/ansible-role-docker/blob/main/LICENSE)

Ansible Role: Docker
=========
Installation of the docker environment, and integration of dependencies for the "community.docker" module.

Dependencies
--------------
- `community.general` collection
- `community.docker` collection

Installation
--------------
To install this role you can use the following command:

`$ ansible-galaxy install git+https://github.com/christopherlouet/ansible-role-docker.git`

Role Variables
--------------
Available Variables:

| Variable Name  | Description                                                                           | Default    |
|----------------|---------------------------------------------------------------------------------------|------------|
| `docker_module_enabled` | Installing dependencies for the docker module                                | `true`     |
| `docker_compose_module_enabled` | Installing dependencies for the docker-compose module                | `false`    |
| `docker_compose_version` | Version of docker-compose to use for the ansible module (>= 1.7.0, < 2.0.0) | `1.25.0-1` |

License
-------

MIT/BSD

Author Information
------------------
This role was created in 2023.

# test_task
[![asnible](https://github.com/poogas/test_task/actions/workflows/ansible.yml/badge.svg)](https://github.com/poogas/test_task/actions/workflows/ansible.yml)
[![set env](https://github.com/poogas/test_task/actions/workflows/set_env.yml/badge.svg)](https://github.com/poogas/test_task/actions/workflows/set_env.yml)
[![deply](https://github.com/poogas/test_task/actions/workflows/deploy.yml/badge.svg)](https://github.com/poogas/test_task/actions/workflows/deploy.yml)

# Info:

Project for DelaWeb by [Dmitriy Volynov]

Creates simple project wordpress, nginx with letsencrypt, mariadb in docker compose with CI/CD and github actions 

# Requements

- Centos7 for host

# Secrets

 | Secrets | Discription | Example |
| ------ | ------ | ------ |
| **HOST** | *Your ip host* | 127.0.0.1
| **HOST_USER** | *User from host* | asdasd3ds:asdsad3773dhd37d37d
| **SSH_KEY** | *Private Key from Key pair in host* | -----BEGIN RSA PRIVATE KEY...
| **SSH_KEY_RSA** | *Private Key from Key pair in host* | -----BEGIN RSA PRIVATE KEY-----
| **SSH_KEY_PUB** | *Pub Key from Key pair in host* | ssh-rsa AAAAB3NzaC1yc2EAAAADAQA...
| **LE_EMAIL** | *for letsencrypt should be your email* | mail@example.com
| **LE_FQDN** | *for letsencrypt Domain, for multiple FQDNs you can pass comma-separated list* | aaa.example.com,bbb.example.com
| **DB_USER** | *User username of future Database* | admin
| **DB_USER_PASSWORD** | *User password of future Database* | qwerty123
| **DB_ROOT_PASSWORD** | *root password of future Database* | qwerty1234

# Usage:

- *Fork project and setup all variables*
- *Push*
- *Wait*
- ...
- ..
- *Profit*

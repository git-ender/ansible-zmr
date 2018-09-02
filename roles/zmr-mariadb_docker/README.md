# zmr-mariadb_docker

This role is just and exercise. It run a MariaDB container on a given host, with custom user and password

# Requirements

* Ansible >= 2.1
* Python >= 2.6
* Docker-py >= 1.7.0
* Docker API >= 1.20

# Role Variables

See default/main.yml for example

    mariadb_docker_imagename: mariadb
    mariadb_docker_imagetag: 10.2.14
    mariadb_docker_containername: mariadb_docker

The vars/main.yml file is encrypted with ansible-vault.

    mariadb_root_password: "my_root_password"
    mariadb_user: "my_user"
    mariadb_password: "my_user_passord"

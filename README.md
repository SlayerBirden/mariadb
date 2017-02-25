# MariaDB docker image

See original description in [parent (official) repo](https://github.com/docker-library/mariadb) README.

## About this fork

This is mainly aimed to add Image based on [Alpine Linux](https://www.alpinelinux.org/) while preserving other configuration workflow (like Env Variables). Look here to get the current MySQL version: https://pkgs.alpinelinux.org/package/v3.4/main/armhf/mariadb 

You can set the requested version in the Dockerfile and rebuild image for your needs.

All configuration variables are preserved from original Image. See description here: https://hub.docker.com/_/mariadb/

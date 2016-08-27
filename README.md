# MariaDB docker image

See original description in [parent (official) repo](https://github.com/docker-library/mariadb) README.

## About this fork

This is mainly aimed to add Image based on [Alpine Linux](https://www.alpinelinux.org/) while preserving other configuration workflow (like Env Variables). Current MySQL server version is "10.1.16-MariaDB" - however it's getting built from Alpine Edge apk repo. You can set the requested version in the Dockerfile and rebuild image for your needs.

This repo is **not** build automatically. The Alpine version is available on Docker Hub https://hub.docker.com/r/maketok/mariadb-alpine/.

All configuration variables are preserved from original Image. See description here: https://hub.docker.com/_/mariadb/

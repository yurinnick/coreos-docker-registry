Systemd docker-registry services
================================

Systemd services for [docker-registry](https://registry.hub.docker.com/_/registry) and [docker-registry-ui](https://registry.hub.docker.com/u/atcol/docker-registry-ui), can be used on [CoreOS](https://coreos.com).

Services
--------

- **docker-registry** - Start docker registry container on 5000 port, uses `docker-registry.yaml` config from `/home/core/registry-conf` directory and `/home/core/registry` for images storing
- **docker-registry-webui** - Start docker-registry-webui on 80 port

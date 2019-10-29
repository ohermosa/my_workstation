# Docker Deploys

- [Docker Deploys](#docker-deploys)
  - [Despliegues disponibles](#despliegues-disponibles)
    - [Vault](#vault)
    - [Nextcloud](#nextcloud)

Para `docker-compose`, hay que ejecutar el siguiente comando:

```bash
cd ansible
ansible-playbook install.yml -t install_docker --ask-bacome-pass
```

## Despliegues disponibles

| **SUBDIRECTORIO** | **DESCRIPCIÓN** |
|-------------------|-----------------|
| [vault](docker_deploys/vault) | Despliegue de `Vault` usando `Consul` como backend e incluyendo interfaz web y backup de datos |
| [nextcloud](docker_deploys/nextcloud) | Despliegue de `Nextcloud` con `MariaDB` como base de datos |

### Vault

### Nextcloud
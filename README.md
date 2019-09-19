# faithfulword-deploy

## Environment variables
```
export DOMAIN=
export USERNAME=
export ADMIN_NAME=$USERNAME
export ADMIN_PASSWORD=
export EMAIL=
export HASHED_PASSWORD=$(openssl passwd -apr1 $ADMIN_PASSWORD)

export FW_SECRET_KEY_BASE=
export FW_PORT=4000
export FW_DATABASE_USERNAME=postgres
export FW_DATABASE_PASSWORD=
export FW_DATABASE_HOSTNAME=postgres
export FW_DATABASE_NAME=
export FW_DATABASE_PORT=5432

export TRAEFIK_PUBLIC_TAG=proxy-public
```

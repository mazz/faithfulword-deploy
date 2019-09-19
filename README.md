# faithfulword-deploy

## Environment variables
```
export DOMAIN=
export USERNAME=
export ADMIN_NAME=$USERNAME
export ADMIN_PASSWORD=
export EMAIL=
export HASHED_PASSWORD=$(openssl passwd -apr1 $ADMIN_PASSWORD)

export DB_PASSWORD=

export FW_SECRET_KEY_BASE=
export FW_PORT=4000
export FW_DATABASE_USERNAME=postgres
export FW_DATABASE_PASSWORD=$DB_PASSWORD
export SEO_DATABASE_HOSTNAME=database
export SEO_DATABASE_NAME=
export SEO_DATABASE_PORT=5432

export TRAEFIK_PUBLIC_TAG=proxy-public
```

# PostgreSQL

Hello!

To run postgreSQL, we need to run this command:

If we do not want to see the logs:

    docker compose up -d

If we want to see the logs:

    docker compose up

## Access PostgreSQL Container

To access the database container we need to run these commands:

    docker exec -it postgresql /bin/bash

Once that we are inside the container we just need to execute this command to access the database:

    psql -U postgres

This will use the default username.

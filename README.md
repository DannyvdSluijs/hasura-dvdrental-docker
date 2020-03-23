# hasura-dvdrental-docker
A docker setup with Hasura initialised with the DVD rental database.

To start the docker contrainer run `docker-compose up -d` from the terminal located at this folder.
After bringing the docker containers up open the web browser at http://localhost:8080

# Credits
This docker-compose setup has been created using sources from:
- Hasura: https://hasura.io/docs/1.0/graphql/manual/getting-started/docker-simple.html
- Postgres tutorial: https://www.postgresqltutorial.com/postgresql-sample-database/

# Warning
*DO NOT* use in production as the password and data are in plain text in this file

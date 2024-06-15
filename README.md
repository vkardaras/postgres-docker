# postgres-docker

## postgres db running on docker with init script

- Customize the parameters of the database in the .env file
- Run `docker-compose up -d` to start the container
- Move into the container with the command `docker exec -it postgres_db bash`
- Connect to the database with the command `psql -d postgres_db -U user`
  - `postgres_db`: The database to connect
  - `user`: The user of the database
- Check the created tables with the command `\dt`

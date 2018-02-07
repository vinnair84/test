Nginx and Postgres
==================
# Overview
Nginx exposed on port 10080 on the Docker host
Potgres exposed on port 15432. Postgres password is taken as a parameter during docker-compose run


To run
```bash
password="PASSWORD" docker-compose up
```
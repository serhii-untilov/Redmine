# Redmine in Docker

[Live Demo](https://redmine.untilov.com.ua)

## Quick Start

For a quick start, run this command on a Linux server:

``` bash
curl -s https://raw.githubusercontent.com/serhii-untilov/Redmine/master/scripts/download-and-run | bash
```

Note: Docker required.

- [Get Docker Desktop](https://docs.docker.com/guides/getting-started/get-docker-desktop/)
- [How To Install and Use Docker on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04)

## Safe Start

``` bash
curl -s https://raw.githubusercontent.com/serhii-untilov/Redmine/master/scripts/download | bash

cd ~/redmine
```

In the .env file replace the variables with desired values: DATABASE_USERNAME, DATABASE_PASSWORD, POSTGRES_USER, POSTGRES_PASSWORD, PGUSER, etc.

Perform script to create database and start the application:

``` bash
./start
```

Check URL <http://localhost:8080>


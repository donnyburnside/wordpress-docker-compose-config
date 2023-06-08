# WordPress Docker
Docker environment featuring the latest version of WordPress, MySQL and phpMyAdmin.


## Requirements
* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Node.js](https://nodejs.org/)


## How to use
1. Clone the repo to your machine.
1. Start the containers by running `docker-compose up -d`
1. That's it, you're good to go!. You can now [view the application](http://localhost:8000) or [manage the database](http://localhost:8080) (use the `MYSQL_USER` and `MYSQL_PASSWORD` settings from `docker-compose.yml` to login to phpMyAdmin). See the [commands](#commands) section below for more information.


## Commands
| Command | Description
|---|-
| `docker-compose up -d` | Start the containers.
| `docker-compose down` | Stop the containers.


## Contributors
* [Donny Burnside](http://www.donnyburnside.com)
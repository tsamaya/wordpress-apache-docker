# wordpress-apache-docker

This repository is quick start for [Wordpress](https://wordpress.org/) using [docker-compose](https://docs.docker.com/compose/)

### get started

- clone or fork this repository
-  `$ cd /path/to/checkout`
- check `.env` file
```
MYSQL_ROOT_PASSWORD=somewordpress
MYSQL_DATABASE=wordpress
MYSQL_USER=wordpress
MYSQL_PASSWORD=wordpress

APACHE_PORT=80
```
- adjust values with your needs
- run `$ docker-compose up --build -d`
- open your Browser http://localhost/

### to stop

- run `$ docker-compose down`

### version

Tested with :
- Docker Version 17.06.2-ce

### Licensing

Licensed under the MIT License

A copy of the license is available in the repository's LICENSE file.

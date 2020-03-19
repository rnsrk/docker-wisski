# USAGE

install [docker](https://docs.docker.com/install/)

and [docker-compose](https://docs.docker.com/compose/install/)

extract wisski-env.tar.gz 

`$ tar -xzvf wisski-env.tar.gz`

start containers

`$ docker-compose up -d`

change permissions for drupal-website

`$ docker-compose run drupal chmod -R 0755 /var/www/html`

go to your browser and type

`localhost:8081`

Webpage looks weird on the first attempt, just klick `log in`.

User: wisski
PW: wisski

quit services in Terminal with 

`ctrl + c`

and 

`$ docker-compose down`

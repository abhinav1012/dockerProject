This is a Docker Project created on WordPress using MySQL, Apache webserver and docker-compose command.
To run this file, run the following command:
docker-compose up
This project also uses several other docker concepts like docker images, containers, enviroment variables, volumes and many more.
Also it includes some Networking concepts like PAT(-p).


Note:
To run this project user should install docker-compose and some docker images like:

1. WordPress.Command to install wordpress in docker:
docker pull wordpress:5.1.1-php7.3-apache

2. MySql. Command to install MySql in docker:
docker pull mysql:5.7

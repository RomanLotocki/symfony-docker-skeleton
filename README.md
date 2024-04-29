# Symfony-Docker Skeleton

## About

This is a Symfony 7 webapp base project with a Docker-ready configuration.  
No need to meet Symfony requirements (PHP, databases...), you just need Docker on your computer to start to code !  
By default this docker recipe comes with a classic LAMP stack and also provides PHPmyadmin to run a smooth and graphic interface to interact with the database.

## Quick install

1. Clone this repository.  
⚠️Do not forget to change the database parameters (name, user, password) in the docker-compose.yml file if you want to run a safe app. You will also have to change the data in the PHP AND PHPmyadmin services.

2. Go to the docker directory and build the containers

3. Install composer dependancies

## Getting started

Once the installation is complete you just have to open your favorite browser to see The Symfony 7 Welcoming Page

- on Windows go to : <http://host.docker.internal:8080>
- on MAC/Linux go to: <http://localhost:8080>  

You can also access your app with https connection available at <https://localhost:8443>. As the key and SSL certificate were generated by me and are not official, your browser won't recognize them the first time. You just have to click on `advanced` and `Proceed to localhost (unsafe)`

Finally you can see what is going on in your database by changing 8080 with 8181 in the url.

Enjoy your work with Symfony !

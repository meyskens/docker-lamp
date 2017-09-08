Docker LAMP Stack (for 2ITF)
============================

This is a simple LAMP stack running on Docker for use in local development, the stack exists of an Apache server with PHP 7 (plus useful plugins) and a MySQL 5 server. 

## How to use?
You need these files stored as well as `docker` and `docker-compose` installed and running.  
In your favourite shell go to this folder and execute `docker-compose up` and it will build and start the needed containers. 

## How to connect to MySQL
Since we link toghether 2 containers the mysql host is configured to be `mysql`. By default the root password is `pass`. You can change these in the `docker-compose.yml` file.

## Where is PHPMyAdmin
It is at `http://localhost:8080/phpmyadmin`. The username is `root` and the password is `pass` by default.

## Where is HTTPS?
It is a **simple** LAMP stack for **local** development. 

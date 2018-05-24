# BillingTestDocker

## Stable on ##
* ubuntu 16.04 LTS
* docker version 17.09.0-ce, build afdb6d4 
    * after installing docker run `sudo usermod -a -G docker $USER`
    * re-login(in system) after this command
* docker-compose version 1.15.0, build e12f3b9

## Project Install ##
* clone this repo
* cd billing-task-docker
* git clone https://github.com/Arty123/billing-task app
* sh build.sh
* sh run.sh php-cli bin/console app:test-consumer

## Stack ##
* Docker
* Symfony 4 - skeleton
* RabbitMQ (RabbitMqBundle)
* Supervisor
* Mysql 5.7
* PHP7.1

Run test script:  
```bash 
sh run.sh php-cli bin/console app:test-consumer 

# Azubi AWS Solutions Architect Project - Understanding Dockers

## by kebe

> This project looks at migrating applications into containers in the AWS environment, as well as the Docker environment.

## Objective of version 1

The main outcome is to have a shareable working docker image hosted on the docker Hub.

## Objective of version 2

Your main outcome is to have a working docker image deployed on AWS and running on Fargate.

------------------------------Deploy first on local machin and then on fargate---------------------------

  1 Création de l'image
  
   docker buildx build -t phpapp .

  2 Execution du container
  
  docker run --name myawesome-php-app -d -p 8086:80 phpapp

Accéder au browser et vérifier: http://0.0.0.0:8086/

    

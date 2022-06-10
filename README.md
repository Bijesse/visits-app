# Sample Node Application using Docker
This repository contains a basic application that is intended to run locally on your device and counts the numbers of visitors to the site

The application in this exercise has been build for Docker. It makes use of [Redis](https://hub.docker.com/_/redis) and [Alpine](https://hub.docker.com/_/alpine) images found in the Docker Hub. Follow the instructions below to run the app.

## Requirements:
In order to participate in this exercise you will need...

* Laptop with Mac OS X, Windows is not supported for this workshop
* [Docker for Mac](https://www.docker.com/products/docker-desktop)

## Step 1
Clone this repository to your local machine using `git clone https://github.com/Bijesse/visits-app`

## Step 2 
Build and run the app using Docker:
```shell
docker-compose up
```

## Step 2 
Run this app in your browser by visiting [http://localhost:8080/](http://localhost:8080/)

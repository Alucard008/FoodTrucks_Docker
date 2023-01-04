Food Trucks
===

![img](shot.png)

The app is built with [Flask](http://flask.pocoo.org/) on the backend and [Elasticsearch](http://elastic.co/) is the search engine powering the searches. The front-end is built with [React](http://facebook.github.io/react/) and the beautiful maps are courtesy of [Mapbox](https://www.mapbox.com/).

#### Docker

There are two different ways of getting the app up and running with Docker. To learn more about how these two differ, check out the [docker curriculum](http://prakhar.me/docker-curriculum).

##### Docker Network
```
$ ./setup-docker.sh
```

##### Docker Compose
```
$ docker-compose up
```

The app can also be easily deployed on AWS Elastic Container Service. Once you have [aws ecs cli](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI_installation.html) installed, you can run the following to deploy it on ECS!
```
$ ./setup-aws-ecs.sh
```
##### To run this application on your machine
```
$ git clone https://github.com/Alucard008/FoodTrucks_Docker
$ cd FoodTrucks_Docker
$ ./setup-docker.sh
```

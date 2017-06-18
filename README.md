# qbot-ms-yo
Vert.x microservice "yo" to add feature to QBot

## What is it?

This is a Vert.x microservice walking skeleton project to add features to QBot (you can test the distribution of QBot here https://github.com/botsgarden/qbot-distribution | currently QBot is not OSS)

## Requirements

- Redis database: microservices discovery backend

## Setup

```shell
BOT_HANDLE=indythebot
JAVA_VERSION=8 # optional, needed for deployment on Clever Cloud
PORT=8080 # only if you want to change the port (default is 8080)
SERVICE_HOST=qbotmsyo.cleverapps.io # default is "localhost", this is the domain of your service
SERVICE_PORT=80 # this is the external port of your service (default is 80)

# for local tests PORT == SERVICE_PORT, except if you use VM or containers

# REDIS PART
REDIS_HOST=<...> # default is "127.0.0.1"
REDIS_PASSWORD=<...> # default is null
REDIS_PORT=<...> # default is 6379
REDIS_URL=<...> # optional, needed for some cloud providers 
```

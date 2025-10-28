# Node.js: Microservices

https://www.linkedin.com/learning/node-js-microservices-22685072

- duration: 03:39:00
- language: en
- topics: microservices, node
- rank: 4.58
- description: Daniel Khan, three hours
- year: 2023
- status: started

## Understanding how microservices are built and used , 0:46, 2025-10-17

- intro

## What you should know , 1:02, 2025-10-17

- Node and Express

## Installing Git, Node.js, and Docker , 1:18, 2025-10-17

- Docker needed

## Getting the exercise files from GitHub, 1:48, 2025-10-17

- nice trick to get all branches locally

## Setting up Visual Studio Code, ESLint, and Prettier , 2:51, 2025-10-17

- two extensions

## Launching MongoDB, Redis, and Jaeger in Docker , 3:53, 2025-10-17

- everything with docker worked well

## Installing MongoDB Compass , 0:59, 2025-10-17

- installed fine

## Setting up and exploring your sample application , 5:25, 2025-10-22

- app (shopper) worked exactly like in the video

## Understanding the sample apps code , 5:37, 2025-10-22

- a classic EJS app written in JavaScript

## Getting insights with OpenTelemetry and Jaeger , 3:54, 2025-10-22

- OpenTelemetry puts a camera in each service
- Jaeger brings this trace data together so you can understand what is happening

## Setting your mission , 1:49, 2025-10-22

- scale services more easily

## What's your goal for this chapter? , 2:19, 2025-10-23

- shows how microservive will replace a part of the old application, catalog

## Creating the service, 6:35, 2025-10-23

- a short tour

## Designing a REST API for the catalog service , 3:57, 2025-10-23

- basic REST

## Adding business logic and database access , 5:15, 2025-10-23

- moved some over to microservice

## Creating your first REST endpoint , 4:03, 2025-10-23

- set up first endpoint

## Completing the API, 6:11, 2025-10-23

- built rest of routes

## Testing REST endpoints, 5:36, 2025-10-23

- uses REST Client

## What's your goal for this chapter?, 1:59, 2025-10-23

- a service itself

## Setting up the registry , 5:06, 2025-10-23

- set up three routes

## Registering services , 6:55, 2025-10-23

...........................

## Creating the service client , 9:35, 2025-10-23

- getService, callService

## Using the catalog service , 8:11, 2025-10-23

- converted the CatalogService to CatalogClient, which uses the ServiceRegistry

.............................

## Service monitoring with OpenTelemetry and Jaeger , 3:29, 2025-10-23

- shows how to browser Jaeger to see spans etc.

## API authentication with JWT, 3:42, 2025-10-23

- overview

## Creating the user service , 3:42, 2025-10-23

- just swapped it out

## Add JWT tokens to the user service , 5:09, 2025-10-23

- creates and returns token

## Make the front end use JWT authentication , 7:50, 2025-10-23

- verifies the user

## Using bearer headers, 8:47, 2025-10-23

- more jwt in middleware

## Protecting endpoints with JWT , 4:48, 2025-10-23

- protects with a middleware function

...............................................

## Installing up RabbitMQ , 1:24, 2025-10-23

- install with Docker

## Setting up the order service , 3:02, 2025-10-23

- just make last micro service

## Producing orders , 6:47, 2025-10-23

- adds to RabbitMQ queue

## Consuming orders , 9:03, 2025-10-23

- watches and consumes queue edditions in IIFE

## VOCAB - SPANISH

```

```

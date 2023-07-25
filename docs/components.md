---
sidebar_position: 10
---

# Components

> Subenshi comes with a set of components that can be used to build your own solutions.

## Nats

This is a message broker that allows microservices to communicate with each other.

## Gateway

This is an entry point for your application. It exposes a web server that receives all requests from a client and forwards them to the microservices.

## Template

This is a template for a microservice. It contains the basic structure and configuration for a microservice.

By default: 
- Uses Nats to communicate with other microservices.
- Makes use of MongoDB - if the env var MONGODB_CONNECTION_STRING is set.
- Makes use of MongoDB collection with its same name (as the microservice's name in package.json) to store the data.

## Admin

This is a React-admin application that connects to the gateway and allows you to manage the data stored in the database via microservices.
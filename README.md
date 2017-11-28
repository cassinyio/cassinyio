# Cassiny.io

[Cassiny](https://www.cassiny.io) is a hosted data science platform.

This repository contains the [central issue
tracker](https://github.com/cassinyio/cassinyio/issues) for the Cassiny project.

## Documentation

Documentation for the Cassiny project can be found at <https://docs.cassiny.io>.

## Other repositories

Cassiny.io consists of many different microservices. The main ones are:

### cassiny-spawner

[cassiny-spawner](https://github.com/cassinyio/cassiny-spawner) receives/sends
notifications to the event stream, he is in charge of creating/removing services.

### cassiny-auth

[cassiny-auth](https://github.com/cassinyio/cassiny-auth) is the microservice in charge of authethincation. Is the only microservice that can create new jwt tokens.

### cassiny-dockerevents

[cassiny-dockerevents](https://github.com/cassinyio/cassiny-dockerevents) collect and save Docker events.

### cassiny-websockets

[cassiny-websockets](https://github.com/cassinyio/cassiny-websockets) holds shared
logic for the different Travis CI apps. It is different from travis-core in
that it holds more generic things, like how to run an async job or how to
handle exceptions.

### cassiny-web

[cassiny-web](https://github.com/cassinyio/cassiny-web) is our web client.
It is written using [Vue.js](http://www.vuejs.org) and communicates with the other microservices using HTTP APIs and websockets.

### cassiny-cli

[cassiny-cli](https://github.com/cassinyio/cassiny-cli) is the microservice in charge of authethincation. Is the only microservice that can create new jwt tokens.
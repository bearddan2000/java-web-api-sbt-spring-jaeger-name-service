# java-web-api-sbt-spring-jaeger-name-service

## Description
Calls remote services and
benchmarks the response.

### STEP 1
Once the project is done building, make
some api calls `http://localhost:81/api/v1/names/random`.

To see a coverage of response times:
- Nav to http://localhost
- Look on left-hand side find services.

## Tech stack
- java
- sbt
  - opentracing

## Docker stack
- openjdk:8-jdk-alpine
- jaegertracing/all-in-one:1.17

## To run
`sudo ./install.sh -u`
- JAEGER DASHBOARD http://localhost
- API http://localhost:81/api/v1/names/random

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Project concept](https://github.com/himankbatra/opentracing-microservices-example)

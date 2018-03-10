# Intro

This project is an extremely simplistic host app that loads microfrontends. It is served by a very simplistic node express server.


# Commands

docker build -t 'willismorse/microservices-demo-microfrontend-hostapp:latest' .
docker push willismorse/microservices-demo-microfrontend-hostapp:latest

helm package microservices-demo-microfrontend-hostapp-chart
helm repo index . 
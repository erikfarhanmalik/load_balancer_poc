# POC for load balancer

## Description
This is a docker compose app. App consist of several services:
- redis (for storage)
- app1 (application instance 1)
- app2 (application instance 2)
- nginx (used as load balancer)

## Note
The war file is not commited, put the war you want on the app1 and app2 folder

## Run
Run with `docker-compose up`

## Access the app
Access the app using `http:/localhost/{path to your app or war file name}`


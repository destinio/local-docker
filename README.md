## Install
https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/

## Uninstall
https://www.mongodb.com/basics/uninstall-mongodb

## Learning
https://learn.mongodb.com/learning-paths/using-mongodb-with-nodejs?_ga=2.145718004.1976169176.1697727608-1499804326.1697727608

## Starter DB

## Docker

`docker-compose up -d`

`docker exec -it mongo-local bash`
`docker exec -it mongo-local mongosh`


### Get IP
docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' thedbname
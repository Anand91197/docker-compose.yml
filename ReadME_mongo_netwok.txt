Firstly we have to create our own network, that can be connect while services get up of mongo via compose file.

docker network create mongo-network


To check compose file: docker-compose -f mongo.yml config

To start/Up service: docker-compose -f mongo.yml up


Para escalar a aplicação no Swarm:

wget "https://raw.githubusercontent.com/cnorbiato/fiap-microservices-trabalho-2/master/docker-compose-swarm.yml"

docker stack deploy --compose-file docker-compose-swarm.yml findsupplier

docker stack services findsupplier


8080: frontend  
8081: servico  
3306: db-servico  

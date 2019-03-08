docker-compose up --build

docker-compose up -d
 
docker run -it --rm docker-nmap  --script=mysql-brute.nse 10.145.89.1

docker-compose stop
 
docker-compose down

docker container prune -f

docker image prune -a -f

docker volume prune -f

docker network prune -f

docker system prune -f 

sudo rm -rf /var/lib/docker/volumes/*

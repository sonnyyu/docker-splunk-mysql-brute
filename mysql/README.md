docker build -t docker-mysql .

docker run --name mysql  -d -p 3306:3306 docker-mysql

docker logs mysql

docker exec -it  mysql /bin/bash 


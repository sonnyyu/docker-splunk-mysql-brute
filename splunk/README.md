docker build -t splunk .

docker run -d -p 8000:8000 --name splunk splunk:latest

docker logs splunk

docker exec -it splunk  /bin/bash


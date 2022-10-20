# RUN
- ```docker build . -t ichirub/ot-microservice-dz1```
- ```docker run -d -it --rm -p 8080:80 --name=ot-microservice-dz1 ichirub/ot-microservice-dz1 && composer install```

# Open in Browser:
- ```http://localhost:8080/health```

# HELP
- ```docker ps -a```
- ```docker rm $(docker ps -qa)```
- ```docker images```
- ```docker rmi $(docker images -q)```

# DOCKER HUB
- ```docker login -u ichirub```
- ```docker push ichirub/ot-microservice-dz1:latest```
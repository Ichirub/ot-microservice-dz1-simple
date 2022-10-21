# RUN
- ```docker build . -t ichirub/ot-microservice-dz1:1.0.0```
- ```docker run -d -it --rm -p 80:80 --name=ot-microservice-dz1 ichirub/ot-microservice-dz1:1.0.0```

# Open in Browser:
- ```http://localhost/health```

# HELP
- ```docker ps -a```
- ```docker rm $(docker ps -qa)```
- ```docker images```
- ```docker rmi $(docker images -q)```

# DOCKER HUB
- ```docker login -u ichirub```
- ```docker push ichirub/ot-microservice-dz1:latest```
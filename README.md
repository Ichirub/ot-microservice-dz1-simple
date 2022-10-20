# RUN
- ```docker build . -t ichirub/ot-microservice-dz1-simple```
- ```docker run -d -it --rm -p 8080:80 --name=ot-microservice-dz1-simple ichirub/ot-microservice-dz1-simple && composer install```

# Open in Browser:
- ```http://localhost:8080/health```
- 
# HELP
- ```docker ps -a```
- ```docker rm $(docker ps -qa)```
- ```docker images```
- ```docker rmi $(docker images -q)```
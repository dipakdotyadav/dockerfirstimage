# dockerfirstimage
 `docker build -t friendlyhello .`
 
 `docker run -d -p 4000:80 friendlyhello`
 
 http://0.0.0.0:4000
 
 
 # docker-compose.yml
 
 `docker swarm init`
 
 `docker stack deploy -c docker-compose.yml getstartedlab`
 
 `docker stack ps getstartedlab`
 
 `docker stack rm getstartedlab`
 

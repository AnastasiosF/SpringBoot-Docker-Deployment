# Spring Boot Docker Deployment


http://localhost:8080/api/v1/findAll

`docker-compose up --build`


### Run dockerfile independent
1. `cd` inside the folder
2. Change the gym.jar with your own `jar file`
3. Replace in `Dockerfile` the `gym.jar` with your own `jar file` name 
4. `docker build -t <your own tag> . `

### Info
Inside spring `application.properties` you have to set the IP Address of 
host machine. Don't put `localhost` as an IP Address !!! 

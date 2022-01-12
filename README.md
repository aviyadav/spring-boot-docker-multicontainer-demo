# spring-boot-docker-multicontainer-demo

### Build - mvn clean install -DskipTests

### Deploy - docker-compose up

### Verify deployment 

- docker images
- docker ps


### Rebuild on change - docker-compose build

### TESTS

#### POST /user/save

curl -s -X POST

http://localhost:8080/user/save

-H ‘Content-Type: application/json’

-d ‘{“name”:”Your Name”}’


#### GET /user/{id}

curl -s -X GET

http://localhost:8080/user/1


#### GET /user/all

curl -s -X GET

http://localhost:8080/user/all

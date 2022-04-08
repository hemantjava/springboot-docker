docker container ls
docker image remove <id>
docker images  
docker container stop <id>
docker push hemantjava/springboot-docker:0.0.1-SNAPSHOT
docker run -d -p 8080:8080 hemantjava/springboot-docker:0.0.1-SNAPSHOT
mvn spring-boot:build-image
# how to build project
Need to set environment _DOCKER\_HOST_ first.
```
mvn clean package -DskipTests -Ddocker.host=${DOCKER_HOST}
```

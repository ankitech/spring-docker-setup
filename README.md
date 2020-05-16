# spring-docker-setup
This is an repository that shows how to set up automated docker images from a spring project

To build image:
```
.\mvnw clean package docker:build
```

To build and Push image :
```
.\mvnw clean package docker:build verify docker:push
```

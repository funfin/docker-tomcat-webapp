# docker-tomcat-webapp
Building docker image with Java webapp on Tomcat


1. build docker image:

```mvn package docker:build```

2. run docker container

 ```docker run -it --rm -p 8888:8080 pkarpik/webapp```

3. check in browser
  
http://docker-machine-ip:8888/webapp
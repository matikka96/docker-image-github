# Creating docker image from Github with Dockerfile
This is a demo project, which shows how to initialize a simple "hello world" app within docker using Dockerfile.
Docker needs to be already installed on your system. Installation link: https://www.docker.com/get-started

![demo gif](https://github.com/matikka96/node-web-server/blob/master/demo.gif?raw=true)

## Instructions

1) Download project from Github and build it in Docker.
COMMAND: 
```
docker build -t gitnodeserver https://github.com/matikka96/Dockerfile-demo.git
```
This will create docker image named "gitnodeserver".

2) Final step is to run above image.
COMMAND: 
```
docker run -p 333:8080 -d gitnodeserver
```
Now your app is seen here: http://localhost:333

# node-web-server
This is a demo project, which shows hos you can create a simple "hello world" app with docker.
Docker needs to be installed on your system

![demo gif](https://github.com/matikka96/node-web-server/blob/master/demo.gif?raw=true)

## Instructions

1. Download project from Github and build it in Docker.
RUN: ```docker build -t gitnodeserver https://github.com/matikka96/Dockerfile-demo.git```
This will create docker image named "gitnodeserver".

2. Final step is to run above image.
RUN: ```docker run -p 333:8080 -d gitnodeserver```
Now your app is seen here: http://localhost:333

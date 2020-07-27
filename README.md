# docker_golang_hello
Simple Golang service that returns "Hello World!".
# How to build it
docker build --tag hello:1.0 .
# How to run it
docker run --publish 3000:3000 --detach --name db hello:1.0
# how to push it to docker hub
docker tag hello:1.0 phucmars/hello:1.0
docker push phucmars/hello:1.0
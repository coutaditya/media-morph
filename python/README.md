## Media Morph

This is an mp4 to mp3 converter app based on the microservices architecture with auth, notification, gateway and converter services deployed on docker containers and managed by k8s

### Docker Images:

I created the following docker images for the different services -

1. [coutaditya/gateway:latest](https://hub.docker.com/repository/docker/coutaditya/gateway/general)
2. [coutaditya/auth:latest](https://hub.docker.com/repository/docker/coutaditya/auth/general)
3. [coutaditya/converter:latest](https://hub.docker.com/repository/docker/coutaditya/converter/general)
4. [coutaditya/notification:latest](https://hub.docker.com/repository/docker/coutaditya/notification/general)
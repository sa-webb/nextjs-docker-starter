# Next-js(TS) Docker Starter Application

Dockerized Next.js Application

## Running Docker

### Build the container and bind the ports

`docker build -t client . && docker run --name CLIENT_CONTAINER -p 0.0.0.0:5000:3000 client`

### Teardown the container

`docker stop [containerId]`

### Restart the container

`docker start [containerId]`

### Verify the container is running

`docker ps -a`

[Resources](https://medium.com/swlh/dockerize-your-next-js-application-91ade32baa6)
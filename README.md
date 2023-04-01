![docker_logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/2560px-Docker_%28container_engine%29_logo.svg.png)

# Docker 🐳

## Why

The problem

## What

It is a container, that...

## The Process

### Starting a container

### Running a container

## Simple Example

```dockerfile
# use an existing docker image as a base
From alpine

# Download and install a dependency
RUN apk add --update redis

# Tell the image what to do when it starts as a container
CMD ["redis-server"]
```

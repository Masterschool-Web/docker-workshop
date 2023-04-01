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

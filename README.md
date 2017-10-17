# apigeetool

## build
This will build the image from the Dockerfile.
```
docker build -t apigeetool .
```

## run locally
This will run the local image built using the commmand above.
```
docker run --rm -it \
           --name apigeetool \
           apigeetool:latest $*
```

## run
This will pull and run the container image built by [dockerhub](https://hub.docker.com/r/cagiti/apigeetool).
```
docker run --rm -it \
           --name apigeetool \
           cagiti/apigeetool:latest $*
```

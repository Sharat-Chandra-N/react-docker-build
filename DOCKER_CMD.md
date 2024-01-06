## Build the Image

docker build -t react-image-docker .

## Run the Image

docker run -d -p 3000:3000 --name react-image-name react-image-docker

## Discard Running Image

docker rm react-image-name -f

## Running Docker Images

docker ps

## Images

docker image ls

## Remove Docker Image

docker rmi react-image-docker
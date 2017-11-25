# NodeJSDockerWebServer
## Building your Docker image
  $ docker build -t hemants/nodejsdockerwebserver .

## Verify image
  $ docker images
  
## Run your Docker image
  $ docker run -p 80:8080 -d hemants/nodejsdockerwebserver --name node_web_server

## Verify container
  $ docker ps
  
  
  

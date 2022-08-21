# JSON Server

## Technologies

- Node.js
- Express
- Docker
- JSON

## Installation and Setup

To Setup the application, run the following commands

```code
# Clone the repo
git clone https://github.com/hesbon-osoro/docker-json-server.git

# Go to the directory and install the node packages
cd docker-json-server && yarn

# To run the local server
node index.js

# Open the local server on
http://localhost:4000/notes

# To build the image with Docker
docker build -t low-json .

# Incase you run into permission error (Ubuntu 20.04)
sudo chmod 666 /var/run/docker.sock

# To list Docker images
docker images

# To run Docker image
docker run -p 4000:4000 -d low-json

# To view the list of running Docker containers
docker ps

# To stop the running Docker container
docker stop [CONTAINER ID]
```

Install the required dependencies for the Node app.

Run the commands below

**docker build -t node-app:1.0 .** - This command is used to create a Docker image from a Dockerfile with tag name "node-app" and the version is "1.0"

**docker ps** - lists all running Docker containers

**docker run -d -p 8080:3000 node-app:1.0** - starts a new container in detached mode, maps port 8080 of the host machine to port 3000 inside the container

**docker stop <container ID>** - stops the container

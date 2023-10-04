# docker-hello
Docker very simple project


1) Install Docker in your computer (MacOS and Windows should use the Docker Desktop instalation)

2) Check if Docker was correctly installed
   $ docker version

3) Check if there is any Docker container running or stopped
  $ docker ps -a

4) Clone this repository (with app.js)

5) Check to see there's no node previously installed:
  $ node app.js (you should see an error because node is not installed)

5) Build the Docker Image
  $ docker build -t docker-hello .

6) Check if the Docker Image is really available in the computer
  $ docker images
REPOSITORY     TAG       IMAGE ID       CREATED          SIZE
docker-hello   latest    xxxxxxxxxxxx   36 seconds ago   181MB

7) Run the Docker Image (create the Docker Container!!!)
  $ docker run docker-hello

8) You should see:
  $ Hello Docker












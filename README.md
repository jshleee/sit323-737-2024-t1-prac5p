# sit323-737-2024-t1-prac5p

1. Install Docker

2. Clone the Sample Web Application
Use Git to clone the web application repository. I used sit323-737-2024-t1-prac4.1p.

3.Create a Dockerfile
Inside the root directory of cloned application, create a file named Dockerfile. This file will contain all the commands a user could call on the command line to assemble an image.

4.Build the Docker Image
Build Docker image using the docker build command "docker build . -t seoheelee/5.1p"

5.Create a Docker Compose File
Create a file named docker-compose.yml in the project directory. This file defines services, networks, and volumes for a Docker application.

6.Start the Docker Compose Environment
Run the Docker Compose file to start the application. The command is "docker-compose up".

7.Test the Application

8.Push the Docker Image to a Registry
Change the image name is same as the registry.
"docker image tag c6c7752d1c24 jshlee/seoheelee5.1p"
Push the image to the registry.
"docker push jshlee/seoheelee5.1p"

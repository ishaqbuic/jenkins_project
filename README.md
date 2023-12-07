# jenkins_project
This repository contains Dockerfile and docker-compose file of jenkins installation
(Create image from Dockerfile)
docker build -t <image-name>
(Create container from image)
docker run -d -p 8081:8080 --name <container-name> <image-name>
After running container go to browser and paste (http://localhost:8081/)

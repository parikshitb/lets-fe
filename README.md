# lets-fe
Let's learn some FE development. Avoided for long; much necessary now

# Prerequisite
Docker/Docker-desktop is installed

# How to start
1. Download the repo.
2. `cd lets-fe`
3. `docker build -t my-apache2 .`
4. `docker run -dit --name my-running-app -p 8080:80 my-apache2`
5. go to http://localhost:8080

# Reference
https://hub.docker.com/_/httpd

#Changelog
1. Single line html code is added and hosted in apache web server container.
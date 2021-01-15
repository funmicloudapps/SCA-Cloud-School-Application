# SCA-Cloud-School-Application
Created a project folder and a subfolder "docker"
Added Dockerfile with commands in it
I ran the following commands:
$ docker build -t my-php-app .
$ docker run -it --rm --name my-running-app my-php-app
$ docker run -d -p 80:80 --name my-apache-php-app -v C:\Users\olufunmi\Desktop\Code\php-docker:/var/www/html php:7.2-apache
I installed GIT
I ran "git init" in the project folder
I ran "git add"
Then ran "git commit -am 'First commit'"
Created a branch named "stable" by running "git branch stable"
I switched to it with "git checkout stable"
I pushed the content of the project including the Docker files to the stable branch with "git push origin -u stable"
I made changes to the Dockerfile and pushed to feature branch
I switched back to stable branch and merged it with feature branch

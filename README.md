# SCA-Cloud-School-Application
Created a project folder and a subfolder "docker"<br/>
Added Dockerfile with commands in it<br/>
I ran the following commands:<br/>
$ docker build -t my-php-app .<br/>
$ docker run -it --rm --name my-running-app my-php-app<br/>
$ docker run -d -p 80:80 --name my-apache-php-app -v C:\Users\olufunmi\Desktop\Code\php-docker:/var/www/html php:7.2-apache<br/>
I installed GIT<br/>
I ran "git init" in the project folder<br/>
I ran "git add"<br/>
Then ran "git commit -am 'First commit'"<br/>
Created a branch named "stable" by running "git branch stable"<br/>
I switched to it with "git checkout stable"<br/>
I pushed the content of the project including the Docker files to the stable branch with "git push origin -u stable"<br/>
I made changes to the Dockerfile and pushed to feature branch<br/>
I switched back to stable branch and merged it with feature branch

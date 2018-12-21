This project is about launching EC2 instance with specified operating system and setting up the infrastructure to installing software.

Step-1 includes launching of instance with desired hostname of instance(server)
step-2 includes installing of software packages in server
step-3 includes commiting of code/files to Github repository

Commands used for this project:

1. "sudo su - " for root access
2. Configure webpages by adding index.html in /var/www/html/index.html or /var/www/index.html. Configure site-enable for httpd (enable 0r disable index.html) 
3. apt install docker.io(installing docker)
4. docker pull "image-name"
5. docker images( shows installed images)
6. docker run -itd "image-name" (create container for particular image)
7. docker ps (check running  container)
8. docker start/stop "conatiner-id" (start/stop contaier)
9. docker run -itd "image-name" /bin/bash (login into container)
10.apt install docker-compose Install git (apt install git)
11.git clone "URL"
12.git add "host machine file-name"    git commit -m "first commit"
git remote add origin "URL"
git push -u orin master (pushing files/code into github repository)





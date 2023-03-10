# Contact-me - deployment instructions:
Contact-me is a chat application, demonstrating micro-service architecture.  
Composed of Angular frontend, Spring backend, Eureka, RabbitMQ, and Zipkin,  
to enable communication with Slack servers and create a two way live chat.  
All set on docker containers and ready to run.  

To run Contact-me application, you need to have:  
1 - windows10 or newer.  
2 - docker-desktop installed and running - https://docs.docker.com/desktop/install/windows-install/  
2.1 - when NOT using docker-desktop, make sure your hosts file points your docker machine ip to "host.docker.internal" and to "gateway.docker.internal" to enable communication with docker containers.  
3 - download "docker-compose.yaml" and ".env" files from this repository, to your computer.  
4 - open a command prompt (cmd) at docker-compose.yaml location.  
5 - start the servers by running the command "docker-compose up -d".  
6 - open a browser to http://localhost, wait for web site to be available (about 5 minutes).  
7 - fill and send the contact form.  
8 - chat with me.  
9 - stop the servers by running the commond "docker-compose down".  

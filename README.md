# Wordpressproject

This is an project related to docker technology that i have learn from the IIEC-RISE 1.0
This is an wordpress website project with integratio of the mysql, php and apache server

This project will let you create your own wordpress website with the mysql databse.
Using Docker you can ensure that your website will not be failed at anytime. regardless of the traffic on the server.
as docker will gives you the power of starting another server in a second.

Use It.

# Prerequisite that are required for the project

1) docker
    install the stable version of docker 
      its available for
      1) Windows
      2) Linux
      3) Mac
2) install wordpress and mysql in docker (following instructions)
   1) Mysql
      $ docker pull mysql:5.7
      
   2) Wordpess
      $ docker pull wordpress:1.1.1-php7.3-apache
      
3) install docker compose (use following commands)
    1) $ sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    2) $ sudo chmod +x /usr/local/bin/docker-compose
   
# These are all the prerequisites

# Importing the files 

   1) Create a new directory
        $ mkdir mycompose
        
   2) copy this docker-compose.yml file to that directory
      (you can modify some arguments in that file likr os name mysql username password some basic stuff)
      but i suggest keep as it is 
      
   3) Now change directory to mycompose
   
      $ cd mycompose
   
   4) give the command 
   
      $ docker-compose up
      
      it will create two os with mysql and wordpress servers and host a website for you.
      
      # Now in your browser access the website using
         your base os ip address:exposed port
         
         ex. 192.168.43.169:8080    (this is just a example use yours)
      
     # Thanks!
      
 

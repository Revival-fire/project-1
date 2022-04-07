## LAMP stack Implementation
STEP 1 — INSTALLING APACHE AND UPDATING THE FIREWALL 

Apache HTTP Server is a web server software mostly used .
In order to install apache we must update all the packages using this code 

`sudo apt update`  

and the install apache with

`sudo apt install apache2`

then check the check the status

`sudo systemctl status apache2`

![Apache Status](./images/Apache_status.PNG)

checking the apache landing page on my browser

![Apache landing page](./images/Landing_page.PNG)


STEP 2 — INSTALLING MYSQL

 Installing MYSQL using the code below 

`sudo apt install mysql-server`

For secure installation use the code below

`sudo mysql_secure_installation`

mysql successfully installed

![mysql](./images/Mysql_installed.PNG)


STEP 3 — INSTALLING PHP

To install these 3 packages of  php, php plus and php plus sql at once, run:

`sudo apt install php libapache2-mod-php php-mysql`

Php successfully installed

![](./images/php_installed.PNG)

At this point our LAMP is successfully installed

L-Linux (ubuntu)  
A-Apache HTTP Server  
M-Mysql  
P-Php


STEP 4 — CREATING A VIRTUAL HOST FOR YOUR WEBSITE USING APACHE









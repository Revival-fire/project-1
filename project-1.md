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




# Linux-Server-Configuration
# Project Description
Hosting the Catalog Item web applications by installing a Linux server and securing it from getting attacked 

# IP address
3.17.74.105.xip.io

# URL
ec2-3-17-74-105.us-east-2.compute.amazonaws.com

# Summary of software installed
$ sudo apt-get install apache2 <br/>
$ sudo apt-get install libapache2-mod-wsgi python-dev <br/>
$ sudo apt-get install git<br/>
$ sudo apt-get install python-pip<br/>
$ sudo pip install flask<br/>
$ sudo pip install httplib2 oauth2client sqlalchemy psycopg2 <br/>
$ sudo apt-get install libpq-dev python-dev<br/>
$ sudo apt-get install postgresql postgresql-contrib<br/>

# Summary of configurations made
Go to the .ssh file <br/>
Download the .pem file and move it to the .ssh folder<br/>
Type $ chmod 600 ~/.ssh/udacity.pem in the termenal to securing the key<br/>
Type $ ssh -i ~/.ssh/udacity.pem ubuntu@3.17.74.105 to log into the server as the user ubuntu<br/>
Type $ sudo adduser grader to create new user called grader<br/>
Type $ sudo nano /etc/sudoers.d/grader to give the grader superuser privileges<br/>
Upgrading the current packages by typeing $ sudo apt-get update<br/>
$ sudo apt-get upgrade<br/>
$ sudo apt-get dist-upgrade<br/>



# Resources
https://github.com/mulligan121/Udacity-Linux-Configuration/blob/master/README.md

# Documentation of project 5

a. I created and configured two linux based virtual servers and named them 'mysql-server" and "mysql-client" respectively.
   	![linux servers](images/image1.PNG)

b. I set host-name for the two servers in my terminal
         `sudo hostnamectl set-hostname mysql-server `

         `sudo hostnamectl set-hostname mysql-client`
     	![hostname](images/image2.PNG)
         	![hostname](images/image3.PNG)
c.   I updated the server on both terminals
      `sudo apt update -y`
      	![sudo update](images/image4.PNG)

d.  I upgraded the server on both terminals
      `sudo apt upgrade -y`
      	![sudo upgrade](images/image5.PNG)

e.   I installled mysql server
      `sudo apt install mysql-server -y`
      	![install mysql](images/image6.PNG)

f.   I enabled mysql
       `sudo systemctl enable mysql`
       	![enable mysql](images/image7.PNG)

g.   I secured installation of mysql
       `sudo mysql_secure_installation`
       	![secure installation](images/image9.PNG)

h.   I configured mysql server to allow connections from remote hosts
       `sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf`
       ![configure mysql](images/image10.PNG)

i.  I tried connecting from the mysql-client to the mysql-server
        ![Connect](images/image11.PNG)
        ![Connect](images/image12.PNG)
	

    


sudo ufw enable ---> command used to enable the ufw

sudo ufw disable ---> command used to disable the ufw

sudo ufw status ---> 

sudo ufw status verbose ---> 

sudo ufw status numbered ---> 

sudo ufw reset ---> to reset ufw to the installed default 

sudo ufw default deny incoming ---> 

sudo ufw default allow outgoing ---> 

sudo ufw allow ssh ---> allows incoming shh connection 
or 
sudo ufw allow 22 ---> allows incoming shh connection 

sudo ufw deny shh ---> denies incoming shh connection

sudo ufw allow https ---> 
or ?
sudo ufw allow 443 ---> 

sudo deny https ---> 


sudo ufw allow proto tcp from any to any port 80,443 ---> 

sudo ufw allow ftp ---> 

sudo ufw deny ftp ---> 

sudo ufw allow from (((ip address or a subnet))) to any port 22 ---> all the connection should pass through the port 22 

sudo ufw delete 1 ---> 



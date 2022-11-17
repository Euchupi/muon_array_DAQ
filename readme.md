
1. Follow this readme to set up the basic environment 
2. source the passwd.sh to get the basic settings 
3. run the maria initialize.py to set up the database structure

## LAMP
```
sudo apt install apache2-dev
sudo apt install php-dev
sudo apt install mariadb-server
```

### mariadb-setup

```
sudo mysql_secure_installation
sudo mysql 
```

```
create database local;
create user 'muon_array_local' identified by 'muon_array_local';
grant all privileges on local.* TO 'muon_array_local' ;  
# Further modifications could be found at /etc/mysql/mariadb.conf.d/50-server.cnf
```


## Python dependencies
```
pip3 install mariadb 
pip3 install numpy 
pip3 install scipy
```
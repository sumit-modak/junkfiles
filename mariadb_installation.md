# MariaDB installation

```
sudo apt install mariadb-server
sudo systemctl status mariadb.service
```

# Setting up mariadb

```
mysql_secure_installation
```

# Running mariadb at localhost (also no password set)

```
mariadb -u root -p
```
-u		user
-P 		port
-h		server

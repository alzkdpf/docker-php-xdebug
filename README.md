#### Install Guide ####

1. edit xdebug.ini
xdebug.remote_host is your ip address 

example:
```
    xdebug.remote_host=192.168.9.22
```

2. configuration setting
edit docker-compose.xdebug.yml
volumes:
- <your www root path>:/var/www/html
- <your log path>:/tank/log

3. execution shell script
#./start.sh
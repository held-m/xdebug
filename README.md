# xdebug

; Xdebug  
xdebug.idekey = PHPSTORM   
xdebug.client_host = localhost   
xdebug.discover_client_host = 1   
xdebug.start_with_request = yes   
xdebug.mode = develop,debug,coverage,debug,gcstats,profile,trace   
xdebug.log_level = 7   
xdebug.show_local_vars = 1


# docker-compose.yml
```
#php   
volumes:   
    - './conf/php/xdebug.ini:/usr/local/etc/php/conf.d/99-xdebug.ini'
```

# Docker build with Apache and PHP with SSL enabled.

## Description

This is a simple Apache/PHP72 docker configuration for local development. It has following 

## Configuration

You can change the server settings base on your need. Edit docker-compose.yml to update port and path mapping.


## Usage

Start the server
```
docker-compose up
```

Stop the server
```
docker-compose down
```

Open the info file from browser
```
https://localhost:4434/info.php
```

## References

* [PHP Docker with SSL](https://github.com/nezhar/php-docker-ssl)

[![CodeFactor](https://www.codefactor.io/repository/github/sergeevpasha/docker-php-worker/badge)](https://www.codefactor.io/repository/github/sergeevpasha/docker-php-worker)
[![Docker Image CI](https://github.com/sergeevpasha/docker-php-worker/actions/workflows/dockerimage.yml/badge.svg)](https://github.com/sergeevpasha/docker-php-worker/actions/workflows/dockerimage.yml)

# PHP Worker

Built on PHP 8.0 image and is used for php based services

Main locale: en_US.UTF-8

## PHP Modules

* bcmath       
* Core
* ctype
* curl
* date
* dom
* exif
* fileinfo
* filter
* ftp
* gd
* gettext
* hash
* iconv
* imap
* intl
* json
* libxml
* mbstring
* openssl
* pcntl
* pcre
* PDO
* pdo_pgsql
* Phar
* posix
* readline
* redis
* Reflection
* session
* SimpleXML
* soap
* sodium
* SPL
* sqlite3
* standard
* tokenizer
* xml
* xmlreader
* xmlwriter
* zip
* zlib

# Additional Software
* Cron

Example configuration for docker-compose.yml
```
app:
    image: uralenergotel/php-worker:latest
    tty: true
    volumes:
        - ./:/var/www
    networks:
        - some-network
```

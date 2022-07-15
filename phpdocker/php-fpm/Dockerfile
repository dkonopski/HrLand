FROM phpdockerio/php:8.1-fpm
WORKDIR "/application"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        php8.1-bcmath \ 
        php8.1-dba \ 
        php8.1-decimal \ 
        php8.1-http \ 
        php8.1-imap \ 
        php8.1-intl \ 
        php8.1-mcrypt \ 
        php8.1-mysql \ 
        php8.1-phpdbg \ 
        php8.1-redis \ 
        php8.1-sqlite3 \ 
        php8.1-uuid \ 
        php8.1-xdebug \ 
        php8.1-raphf \ 
        php8.1-yaml; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*

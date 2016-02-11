FROM mysql:5.6
RUN { \
    echo '[mysqld]'; \
    echo 'character_set_server = utf8'; \
    echo 'collation_server = utf8_unicode_ci'; \
    echo 'max_connections = 2000'; \
} > /etc/mysql/conf.d/charset.cnf
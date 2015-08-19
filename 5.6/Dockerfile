FROM mysql:5.6
RUN { \
    echo '[mysqld]'; \
    echo 'character-set-server = utf8'; \
    echo 'default-collation = utf8_unicode_ci'; \
} > /etc/mysql/conf.d/charset.cnf
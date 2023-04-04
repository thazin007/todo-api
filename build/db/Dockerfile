FROM library/mysql:latest

ENV MYSQL_DATABASE todo

COPY custom.cnf /etc/mysql/conf.d/

COPY sql /docker-entrypoint-initdb.d
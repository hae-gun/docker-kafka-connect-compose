FROM mariadb

ENV MYSQL_ROOT_PASSWORD qwer1234
ENV MYSQL_DATABASE mydb
COPY ./mysql /var/lib/mysql
EXPOSE 3306
ENTRYPOINT ["mysqld", "--user=root"]
FROM mysql:5.7.25

LABEL mainatainer="Sandeep Kumar"
LABEL description="mysql db for production dockerwebapp"

WORKDIR /docker-entrypoint-initdb.d

EXPOSE 3306

ENV MYSQL_DATABASE="accounts"

COPY db_backup.sql ./db_backup.sql

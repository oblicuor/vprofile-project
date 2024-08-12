FROM mysql:8.0.33
LABEL "proyect"="vprofile"
LABEL "Autor"="Luis"

ENV MYSQL_ROOT_PASSWORD="1234abcd"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
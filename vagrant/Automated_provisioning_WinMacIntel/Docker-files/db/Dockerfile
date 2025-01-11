FROM mysql:8.0.33
LABEL "project"="uprofile"
LABEL "Author"="Utkarsh"

ENV MYSQL_ROOT_PASSWORD="Vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoints-initdb/db_backup.sql
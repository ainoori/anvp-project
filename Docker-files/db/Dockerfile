FROM mysql:8.0.33
LABEL "Project"="anvp"
LABEL "Author"="an"

ENV MYSQL_ROOT_PASSWORD="vpdbpass"
ENV MYSQL_DATABASE="accounts"
ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

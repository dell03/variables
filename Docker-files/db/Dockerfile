FROM mysql:8.0.33 
LABEL "Project"="Vprofile"
LABEL "Author"="kester"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_back.sql docker-entry-initdb.d/db_backup.sql
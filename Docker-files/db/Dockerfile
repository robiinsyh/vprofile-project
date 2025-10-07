FROM mysql:8.0.33
LABEL Author="Robiansyah"

ENV MYSQL_ROOT_PASSWORD=Robi8741.
ENV MYSQL_DATABASE=accounts
ENV MYSQL_USER=robi
ENV MYSQL_PASSWORD=robi8741.

COPY db_backup.sql docker-entrypoint-initdb.d/db_backup.sql


FROM postgres:15-alpine
COPY ./postgres-image/init.postgres.sql /docker-entrypoint-initdb.d/
COPY ./postgres-image/pg_hba.conf /var/lib/postgresql/data/pg_hba.conf
COPY ./postgres-image/postgresql.conf /var/lib/postgresql/data/postgresql.conf
EXPOSE 5432
CMD ["postgres"]

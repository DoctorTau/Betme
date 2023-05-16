FROM postgres:latest

# Copy an SQL file into the container to be executed on startup
COPY init.sql /docker-entrypoint-initdb.d/

VOLUME /var/lib/postgresql/data




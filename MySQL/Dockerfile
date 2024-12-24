FROM mysql:8.0

# Set environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=projectdb
ENV MYSQL_USER=projectuser
ENV MYSQL_PASSWORD=projectpass

# Copy initialization scripts
COPY ./init.sql /docker-entrypoint-initdb.d/

EXPOSE 3306


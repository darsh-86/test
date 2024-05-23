FROM mysql:8.0

# Copy the custom MySQL configuration file
COPY mysql.cnf /etc/mysql/conf.d/

COPY student.sql /docker-entrypoint-initdb.d/
# Ensure the configuration is loaded correctly
CMD ["mysqld"]

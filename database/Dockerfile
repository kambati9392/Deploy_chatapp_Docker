FROM mysql:latest

# Copy custom configuration files (if any) into the container
# (e.g., to modify my.cnf for custom settings)
#COPY my.cnf /etc/mysql/my.cnf

# Set environment variables for MySQL setup
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=mydb
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=userpassword

# Expose MySQL default port
EXPOSE 3306

# Start MySQL server when the container starts
CMD ["mysqld"]

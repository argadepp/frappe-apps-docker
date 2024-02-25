# Use the official frappe/bench image as the base image
FROM frappe/bench:latest

ENV DBHOST=mariadb
ENV DBROOTPASSWORD=123
ENV ADDMINPASSWORD=admin
ENV REDISHOST=redis
ENV REDISPORT=6379
# Set the working directory
WORKDIR /home/frappe

# Copy the init.sh file to the working directory
COPY init.sh .

# Set the entry point command
CMD ["bash", "/home/frappe/init.sh"]
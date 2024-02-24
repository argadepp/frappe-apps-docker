# Use the official frappe/bench image as the base image
FROM frappe/bench:latest

# Set the working directory
WORKDIR /home/frappe

# Copy the init.sh file to the working directory
COPY init.sh .

# Set the entry point command
CMD ["bash", "/home/frappe/init.sh"]
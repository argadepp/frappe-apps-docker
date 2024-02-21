# Frappe Applications Repository

This repository contains multiple Frappe applications, each residing in its respective folder. You can easily deploy these applications using Docker Compose.

## Frappe Applications Included

- [frappe-builder](./frappe-builder): A Frappe application for building and construction management.
- [frappe-drive](./frappe-drive): A Frappe application for document management and collaboration.
- [frappe-gameplan](./frappe-gameplan): A Frappe application for planning and managing gaming events.
- [frappe-healthcare](./frappe-healthcare): A Frappe application for healthcare management.
- [frappe-helpdesk](./frappe-helpdesk): A Frappe application for helpdesk and customer support.
- [frappe-hrms](./frappe-hrms): A Frappe application for human resource management.
- [frappe-lending](./frappe-lending): A Frappe application for managing lending activities.
- [frappe-lms](./frappe-lms): A Frappe application for learning management.

## Getting Started

To deploy any Frappe application, follow these simple steps:

1. Navigate to the desired application folder:

    ```bash
    cd frappe-appname
    ```

    Replace `appname` with the specific application you want to deploy.

2. Run the following Docker Compose command to start the Frappe application:

    ```bash
    docker-compose up -d
    ```

    This command will set up the Frappe application and its dependencies in detached mode.

3. Access the application in your web browser:

    - Frappe Builder: [http://localhost:8000](http://localhost:8000)
    - Frappe Drive: [http://localhost:8001](http://localhost:8001)
    - ...

    Replace the port number accordingly based on the application you deployed.

4. You can stop the application using:

    ```bash
    docker-compose down
    ```

## Note

- Ensure you have Docker and Docker Compose installed on your machine before running the above commands.

- Customize the application settings, environment variables, or any other configurations as needed for your specific use case.

- Refer to the respective application folders for additional documentation or customization options.

Happy coding!

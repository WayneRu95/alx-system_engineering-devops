Project 0x09-web_infrastructure_design
Welcome to Project 0x09-web_infrastructure_design! In this project, we explore the design of a simple web infrastructure using a single server. This README file provides an overview of the project structure, components, and how to get started.

Overview
This project focuses on designing a web infrastructure that consists of a single server hosting a website accessible via the domain name www.foobar.com. The infrastructure includes components such as a web server (Nginx), an application server, and a database (MySQL). The goal is to understand the roles of each component, their interactions, and potential issues with the infrastructure design.

Project Structure
The project is structured as follows:

server_config/: Contains configuration files for setting up the server, including Nginx configuration, application server setup, and MySQL configuration.
application_code/: Stores the application code base, including HTML, CSS, JavaScript files, and server-side scripts.
README.md: This file provides an overview of the project, instructions, and information about the infrastructure design.
Components
Server: A single server responsible for hosting the web infrastructure.
Web Server (Nginx): Handles incoming HTTP requests and serves static content or forwards dynamic requests to the application server.
Application Server: Executes the application code base, processes user requests, and generates dynamic content.
Database (MySQL): Stores and manages website data, such as user accounts, posts, and other information required by the application.
Getting Started
To set up and run the project locally, follow these steps:

Clone the repository to your local machine:
bash
git clone https://github.com/your-username/0x09-web_infrastructure_design.git
Navigate to the project directory:
bash
cd 0x09-web_infrastructure_design
Configure the server by modifying the server_config files according to your environment and requirements.

Set up the application code base by placing your HTML, CSS, JavaScript files, and server-side scripts in the application_code directory.

Install Nginx, the application server (e.g., Node.js, Django, Flask), and MySQL on your server.

Configure Nginx to serve the website and proxy dynamic requests to the application server.

Configure the application server to execute the application code base and interact with the MySQL database.

Start the web server, application server, and MySQL database.

Access the website via the domain name www.foobar.com to verify its functionality.

Issues
While this infrastructure design serves as a starting point for hosting a simple website, it comes with several limitations and potential issues:

Single Point of Failure (SPOF): The entire infrastructure relies on a single server, making it vulnerable to downtime if the server fails.
Downtime during Maintenance: Performing maintenance tasks, such as deploying new code or restarting the web server, may result in downtime for users.
Scalability Limitations: The infrastructure cannot easily scale to handle increased traffic or workload, requiring significant changes to accommodate growth.
Contributors
Wayne R Masakure
Brendon Jeje


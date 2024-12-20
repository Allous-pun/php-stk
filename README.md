# STK Push Project using PHP
This is an STK Push project implemented using PHP. It integrates with the Safaricom M-Pesa Daraja API to perform STK Push payments. The project allows you to initiate payments through the M-Pesa API using a simple PHP interface.

# Prerequisites:
You can use either XAMPP or Heroku for local or online development.

# Using XAMPP (Local Development)

Why Use XAMPP?
XAMPP is a free, open-source platform that provides an easy-to-use local server environment for PHP and MySQL development. It's lightweight, fast to set up, and doesn't require you to verify your application, unlike cloud services like Heroku.

Steps to Use XAMPP:
Install XAMPP from https://www.apachefriends.org/index.html.
Extract the project folder into the htdocs directory in your XAMPP installation directory (usually C:/xampp/htdocs).
Open the XAMPP Control Panel and start the Apache server.
Open your browser and go to http://localhost/<your_project_folder> to view the application.

# Using Heroku (Online Deployment)

Why Use Heroku?
Heroku is a cloud platform as a service (PaaS) that enables you to deploy and run web applications without worrying about server management. If you want your STK Push project to be accessible online, Heroku is a great choice. However, it requires email verification for deployment.
Steps to Deploy on Heroku:
        
Create a free account on Heroku.
Install the Heroku CLI.
In the terminal, log in to your Heroku account by running:
    heroku login

Create a new Heroku app:
    heroku create <your-app-name>

Push the project to Heroku:
    git push heroku main

Open the app in your browser:
    heroku open

# Configuration

Before using the STK Push feature, configure the necessary parameters such as your M-Pesa Consumer Key, Consumer Secret, and Shortcode. You can find these details on the Safaricom Developer Portal.

Update the configuration settings in the code with the following details:

    Consumer Key
    Consumer Secret
    Shortcode
    Passkey
    Callback URL

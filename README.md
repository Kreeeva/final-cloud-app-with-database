Introduction
This repository contains the source code for an online course web app using Django (for the backend) and Node.js (for the frontend).

Prerequisites:
-Python 3.x
-Node.js
-Django
-PostgreSQL (or any other database supported by Django)

Setting up the backend:
-Clone the repository to your local machine.
-Navigate to the backend directory.
-Install the required packages using pip install -r requirements.txt.
-Create a .env file in the backend directory and set the following environment variables:
-SECRET_KEY: the secret key for your Django app.
-DEBUG: set to True if you are in development, False otherwise.
-Run migrations using python manage.py migrate.
-Start the Django development server using python manage.py runserver.


- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the models.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

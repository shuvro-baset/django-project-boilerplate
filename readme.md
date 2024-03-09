# Django Boilerplate with Authentication App

This repository serves as a basic Django project boilerplate with authentication functionality included. It's designed
to help you kickstart your Django projects quickly by providing a structured setup and a starting point for building
authentication features.

# Features

- Basic Django project configuration.
- Environment file (env) for managing environment variables.
- requirements.txt file listing project dependencies.
- Authentication app with login, logout, change password, and forget password functionalities.

# Getting Started

1. Clone The Repository
    - git clone https://<your_repository_url>
2. Create a Virtual Environment:
    - It's highly recommended to create a virtual environment to isolate project dependencies. You can use tools like
      venv or virtualenv.
   > $ python -m venv venv  
   $ source venv/bin/activate # For Linux/macOS  
   $ venv\Scripts\activate.bat # For Windows
3. Install Dependencies:
    - Install the required Python libraries listed in requirements.txt:
   > $ pip install -r requirements.txt
4. Customize the project
    - Rename the project directory (currently named <project_name>) to your desired name.
    - Update settings in myproject/settings.py with your database and other project-specific configurations.
    - Customize the authentication app in the authentication app directory (templates, forms, views).

5. Run Migrations and Start the Development Server:
   > python manage.py migrate  
   python manage.py runserver


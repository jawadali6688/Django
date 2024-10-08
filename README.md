# Django
# Django Project Setup and Instructions

This repository contains the code and instructions for setting up a Django project. Follow the steps below to create your Django project, activate the virtual environment, and run the development server.

## Prerequisites

Before starting, ensure that you have Python installed on your machine. We recommend using a virtual environment to manage your dependencies.

## Setting Up the Virtual Environment

# 1. **Create a Virtual Environment**:  
   Navigate to your project directory and run the following command to create a virtual environment:

# - python -m venv env


# 2. **Activate the Virtual Environment:**
After creating the virtual environment, activate it with the following command:

# On Windows:

# - .\env\Scripts\activate


# On macOS and Linux:

# - source env/bin/activate


# Installing Django

Once the virtual environment is activated, install Django by running:

# - pip install django


Creating a Django Project
To create a new Django project, use the following command:


# - django-admin startproject myproject

Replace myproject with the desired name of your project.

# Running the Development Server
Navigate into your project directory and run the following command to start the development server:

# - python manage.py runserver


This will start the Django development server, and you can view your project by visiting http://127.0.0.1:8000/ in your web browser.

# Deactivating the Virtual Environment
When you are done working on your project, you can deactivate the virtual environment by running:

# - deactivate

# Additional Resources
For more detailed information, refer to the,
https://docs.djangoproject.com/
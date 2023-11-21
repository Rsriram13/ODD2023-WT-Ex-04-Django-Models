# Ex-04-Django-Models
### Step1 : Create django project and app
Create django project and app using the following commands:

Django-admin startproject mymodels

Python manage.py startapp myapp

### Step 2: Create a user_profile models in model.py
Add the models in the admin interface using the code in admin.py

### Step 3: Define user creation view
Write the function based view to render the data from the models to the template in view.py

### Step 4: Setup the url
Setup the url path for the templates using urls.py

In settings.py file add the app created.

### Step 5 Create template
Create a template within your app if it doesn't already exist. Inside this directory, create a template named 'user_profiles.html'.

### Step 6 Apply migrations
Now do the migrations process to initiate and save the models

Python mange.py makemigrations

Python manage.py migrate

### Step 7: Run the program
Run the program using the command

Python manage.py runserver 8000

In the admin/ page you can view the models created

And in the user_profile template page you can see the profile page of the user.

### OUTPUT:
![screen_shot 2023-11-21 at 21 11 42_6b2319fb](https://github.com/Rsriram13/ODD2023-WT-Ex-04-Django-Models/assets/145742823/dfacd3f7-01ab-4011-ab77-7274352ce790)



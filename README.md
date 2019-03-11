# ToDoApp
A simple TODO Application using Django

Requirements: 
  Django >= 2.0.0
  MySql
  
To run the application in settings.py file some changes have to be made. Create a database named "todolist". 
And check if the database credentials are correct at the settings.py file.

In the command prompt run python manage.py migrate inorder to migrate the database into your local database. 
Then run python manage.py runserver to run the application at localhost at port 8000 in default.

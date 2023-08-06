# recipe-app-api
learning: Django REST API

# commands 
docker-compose run --rm app sh -c "flake8"
Note: This command checks the installation of flake8


docker-compose run --rm app sh -c "django-admin startproject app ."
Note: In this command, the first part runs our service app and then we are passing django CLI command for creating a new project. The "dot" in the end specifies that create the project in the current directory, if we dont put the dot then it will create a sub-directory inside out current directory.




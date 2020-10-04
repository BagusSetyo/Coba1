# Db_shayna

This is a project from Shayna's online shop server that uses laravel version 6x

So when we clone or download the Laravel application, we need the files and folders that are not included in order to run Laravel properly. How to?

After we clone or download it from the GitHub repository, or from anywhere, run the command at the command prompt, before that we have to go to the location of the application folder:

*composer install*

This command will install the libraries or dependencies that Laravel uses.

Next, we need to create an .env file based on the .env.example file, how to run the command:


*copy .env.example .env*

For Linux users use the command:


*cp .env.example .env*

After successfully creating the .env file, run the following command:


*php artisan key: generate*

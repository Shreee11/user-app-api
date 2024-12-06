Install XAMMP 
After installation please go to xammp\htdocs

clone both the repos in the htdocs directory

run the xammp MySQL server 

Clone the user-app-api repo of url "https://github.com/Shreee11/user-app-api.git"
cmd
git clone https://github.com/Shreee11/user-app-api.git

after run

composer install

and add the .env file in the project files attached to the mail

after migrating the database run the ommand 
php artisan migrate

after that run the API server using the following command
php artisan serve


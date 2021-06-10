# assessment

## Steps to run the project
1. $ git clone https://github.com/yadavrohitneosoft/assessment.git
2. $ composer install 
3. create a database and update .env file
4. $ php artisan config:cache
5. $ php artisan serve
6. $ php artisan migrate
7. $ php artisan db:seed --class=UsersTableSeeder  (it is for creating random admin users)
# assessment report
only filteration part is remaining on frontend because time frame is less
if I got the time frame then i will do that one as well.

## Steps to run the project
1. $ git clone https://github.com/yadavrohitneosoft/assessment.git
2. $ composer install 
3. create a database and update .env file
4. $ php artisan config:cache
5. $ php artisan serve
6. $ php artisan migrate
7. $ php artisan db:seed --class=UsersTableSeeder  (it is for creating random admin users)
8. website url: http://127.0.0.1:8000/property/property-home
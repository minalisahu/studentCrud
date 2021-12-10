Student - Add , Update , Edit , show and Delete

After cloning project, go to the root folder of project and run,

    composer install

After composer install successfully, create environment file from sample env.example and setup required credentials in .env file

    cp .env.example .env

After entering required values in .env generate app key by following command

    php artisan key:generate

create the database with same name used in .env file in your mysql and run following command

    php artisan migrate --seed

Above command will generate all tables and default admin as 
		**User** tinkeshwar@gmail.com
		**Password** admin

Finally run

    npm install

to compile assest

# feedback-test
You have installed PHP and Composer for Laravel.
You have installed Node.js and npm for React.
You have a database system such as MySQL.
Installation
To install and run this application, follow these steps:

Clone the repository to your local machine:

git clone https://github.com/your-username/feedback-system.git
Navigate to the backend directory:

cd feedback-system/backend
Install the Laravel dependencies using Composer:

composer install
Copy the .env.example file and rename it to .env. Update the database configuration in this file according to your setup.

Generate the application key:

php artisan key:generate
Migrate the database:

php artisan migrate
Seed the database with sample data (optional):

php artisan db:seed
Start the Laravel server:

php artisan serve
Open another terminal and navigate to the frontend directory:

cd ../frontend
Install the React dependencies using npm:

npm install
Start the React development server:

npm run dev

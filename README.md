
# Laravel React Project Setup 
Boilerplate with laravel 10 and react

<img src="https://joeczubiak.com/static/06f8ecdbcb6fb858fb6a85f187c0c5bb/laravel-plus-react.png">

## Installation
Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/10.x).

Clone the repository
```bash
git clone git@github.com:prazzolgautam62/laravel_react.git
```
OR
```bash
git clone https://github.com/prazzolgautam62/laravel_react.git
```
Switch to the repo folder
```bash
cd laravel_react
```
Install all the dependencies using composer
```bash
composer install
```
Copy the example env file and make the required configuration changes in the .env file
```bash
cp .env.example .env
```
Generate a new application key
```bash
php artisan key:generate
```
Run the database migrations (Create new database & set the database connection in .env before migrating)
```bash
php artisan migrate
```
Start the local development server
```bash
php artisan serve
```
You can now access the server at (http://127.0.0.1:8000/).

For react, install all the dependencies using npm
```bash
npm install
```
Running react dev Server
```bash
npm run dev
```
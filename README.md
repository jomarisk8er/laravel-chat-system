## Simple Chat System using Laravel and Pusher

This is a simple chat system
* Laravel 8.x
* Pusher Websocket
* Vue.js Frontend framework

## How to install

Type on command:

To to clone the repository:
`git clone https://github.com/jomarisk8er/laravel-chat-system.git`

Next, go to the working directory:
`cd laravel-chat-system`

Next, install node_modules:
`npm install`

Next, install packages:
`composer install`

Next, migrate database on your local, you must edit .env file and replace your database credentials,
also you need to create `laravel_chat_system` schema on your database. After that, run this command to migrate:
`php artisan migrate`

It should create tables inside `laravel_chat_system`

Finally, run the web application with this command:
`php artisan serve`

visit `localhost:8000` to start using the application

# Customer Relationship Management System
The project was written using PHP and the Laravel Framework, and Bootstrap Library.

## Features
- Manage users.
- Manage organizations.
- Manage clients.
- Manage projects.
- Manage tasks.
- Manage documents.
- Manage roles.

## How to use

2. Run `composer install` to install composer dependencies.
3. Copy `.env.example` to `.env` and edit the database credentials there.
4. Run `php artisan key:generate` to generate an app encryption key.
5. Run `php artisan migrate --seed` to migrate the database.
6. [Optional] Run `php artisan db:seed --class=DummyDataSeeder` if you want to create some dummy data.

Launch the main URL. You can log in to the admin panel using the default credentials: `admin@example.com` - `password`.

## Installing using Docker

2. Run `docker compose up` to build the images and start the containers.
3. Run `docker compose exec app php artisan migrate --seed` to migrate the database.
4. [Optional] Run `docker compose exec app php artisan db:seed --class=DummyDataSeeder` if you want to create some dummy data.

To stop the containers, run `docker compose stop`.


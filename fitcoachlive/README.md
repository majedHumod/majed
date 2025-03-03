# FitCoachLive

FitCoachLive is a Laravel-based web application built with Laravel Breeze and Livewire.

## Requirements

- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL or another database system

## Installation

1. Clone the repository
2. Navigate to the project directory
3. Install PHP dependencies:
   ```
   composer install
   ```
4. Install NPM dependencies:
   ```
   npm install
   ```
5. Create a copy of the `.env.example` file:
   ```
   cp .env.example .env
   ```
6. Generate an application key:
   ```
   php artisan key:generate
   ```
7. Configure your database in the `.env` file
8. Run migrations:
   ```
   php artisan migrate
   ```
9. Compile assets:
   ```
   npm run dev
   ```
10. Start the development server:
    ```
    php artisan serve
    ```

## Features

- User authentication (login, registration, password reset)
- User profile management
- Dashboard
- Responsive design with Tailwind CSS

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
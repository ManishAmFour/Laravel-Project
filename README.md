# Laravel Authentication System

A simple and secure authentication system built with Laravel, featuring registration, login, and a dashboard.

## Features

- User Registration
- User Login
- Protected Dashboard
- Server-side Validation
- Bootstrap Styling
- Responsive Design
- CSRF Protection
- Password Hashing

## Prerequisites

Before you begin, ensure you have the following installed:
- PHP >= 8.1
- Composer
- MySQL/MariaDB
- Web server (Apache/Nginx) or use Laravel's built-in server

## Installation Steps

1. Clone the repository:
```bash
git clone [your-repository-url]
cd RegistrationFile
```

2. Install PHP dependencies:
```bash
composer install
```

3. Create and configure environment file:
```bash
cp .env.example .env
```

4. Configure your `.env` file with your database details:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

5. Generate application key:
```bash
php artisan key:generate
```

6. Run database migrations:
```bash
php artisan migrate
```

## Running the Application

### Method 1: Using Laravel's Built-in Server

```bash
php artisan serve
```
Access the application at: `http://localhost:8000`

### Method 2: Using XAMPP

1. Place the project in `C:\xampp\htdocs\RegistrationFile`
2. Start Apache and MySQL in XAMPP
3. Access the application at: `http://localhost/RegistrationFile/public`

## Available Routes

- Registration: `/register`
- Login: `/login`
- Dashboard: `/dashboard` (requires authentication)

## Security Features

- Password hashing using Laravel's built-in encryption
- CSRF protection on all forms
- Server-side validation
- Protected routes using authentication middleware

## Contributing

Feel free to submit issues and enhancement requests.

## License

[Your License Here]
#   L a r a v e l - P r o j e c t  
 
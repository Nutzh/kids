<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## 🛠️ Installation

1. install [laragon-wamp.exe](https://github.com/leokhoa/laragon/releases/download/6.0.0/laragon-wamp.exe)
2. extract [php-8.4.5-nts-Win32-vs17-x64.zip](tools/php-8.4.5-nts-Win32-vs17-x64.zip) in C:\laragon\bin\php
3. install [Composer-Setup.exe](tools/Composer-Setup.exe)
4. choose C:\laragon\bin\php\php-8.4.5-nts-Win32-vs17-x64\php.exe for **Composer Setup**
5. open laragon.exe -> Menu -> php -> php-8.4.5-nts-Win32-vs17-x64 -> start All
6. `composer install`
7. `move .env.example .env`
8. `php artisan key:generate`
9. `mysql -u root -p -e "CREATE DATABASE kids; USE kids; SOURCE kids.sql;"`
12. `php artisan storage:link`
13. `php artisan serve`

## 🚀 Requirements

- PHP 8.4.5
- MySQL 8.0+
- Laragon (WAMP stack)
- Composer

## 📝 Database

The project uses MySQL 8.0+ with the following main features:
- User management
- Content categorization
- Story management
- Game management
- Animal information
- Media storage
- Rating system

## 📚 Website Content

### 1. Stories Section
- Educational stories for children
- Categorized content
- Rating system
- Rich media support

### 2. Games Section
- Interactive educational games
- Game content management
- coloring and drawing
- Game categorization

### 3. Animals Section
- Animal information and facts
- Categorized by animal types
- Detailed animal profiles
- Educational content about wildlife

### 4. Admin Features
- Content management system
- Category management
- Story management
- Game management
- Animal content management
- Media file management

## 🔒 Authentication

- User registration
- Login system
- Admin authentication
- Role-based access control

### Laravel Framework
Laravel is a modern PHP framework that provides a robust foundation for building web applications. It offers:
- Elegant syntax and developer-friendly features
- Built-in security features
- Database abstraction and migration system
- Powerful routing system
- Middleware for request filtering
- Built-in authentication and authorization
- Extensive ecosystem of packages

### Blade Templating Engine
We chose Blade over plain HTML for several reasons:

1. **Template Inheritance**
   - Allows creation of master layouts
   - Enables content sections to be extended
   - Reduces code duplication
   - Makes maintenance easier

2. **Powerful Features**
   - Directives for control structures (@if, @foreach, etc.)
   - Component system for reusable UI elements
   - Easy integration with Laravel's features

3. **Developer Experience**
   - Clean, readable syntax
   - Familiar PHP-like syntax
   - Better error handling
   - Improved debugging capabilities

4. **Performance**
   - Compiled to plain PHP
   - Cached for better performance
   - Minimal overhead
   - Optimized for Laravel

## 🛠️ Tech Stack
- Laravel framework
- Blade templating
- MySQL database
- Composer for PHP dependencies

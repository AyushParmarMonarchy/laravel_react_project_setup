<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" width="80" alt="React Logo">
  &nbsp;&nbsp;&nbsp;
  <img src="https://vitejs.dev/logo.svg" width="80" alt="Vite Logo">
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>

---

# 🚀 Laravel + React Starter

This project is a **Laravel application with React frontend** using [Laravel Breeze](https://laravel.com/docs/starter-kits#laravel-breeze).  
It includes authentication scaffolding and a React-powered frontend to quickly get started with modern full-stack development.

---

## 📦 New Project Setup

Run the following commands step by step:

```bash
# 1. Create a fresh Laravel project
composer create-project laravel/laravel project_name

# 2. Enter project folder
cd project_name

# 3. Install Breeze starter kit
composer require laravel/breeze --dev

# 4. Install Breeze with React
php artisan breeze:install react

# 5. Install frontend dependencies
npm install

# 6. Run Vite for development
npm run dev

# 7. Run database migrations
php artisan migrate

# 8. Start Laravel development server
php artisan serve
```


## 🚀🚀 Setup After Cloning from GitHub

If you clone this project from GitHub, follow these steps:

```bash
# 1. Clone the repository
git clone https://github.com/AyushParmarMonarchy/laravel_react_project_setup.git

# 2. Move into project
cd laravel_react_project_setup

# 3. Install PHP dependencies
composer install

# 4. Install frontend dependencies
npm install

# 5. Copy .env file
cp .env.example .env

# 6. Generate app key
php artisan key:generate

# 7. Run database migrations
php artisan migrate

# 8. Build frontend assets
npm run dev

# 9. Start the Laravel server
php artisan serve

```

Run Laravel server → http://127.0.0.1:8000


# 📌 Command Reference


| Command                                                | Description                        |
| ------------------------------------------------------ | ---------------------------------- |
| `composer create-project laravel/laravel project_name` | Create new Laravel project         |
| `cd project_name`                                      | Move into project folder           |
| `composer require laravel/breeze --dev`                | Install Laravel Breeze             |
| `php artisan breeze:install react`                     | Scaffold authentication with React |
| `npm install`                                          | Install frontend dependencies      |
| `npm run dev`                                          | Build React & assets with Vite     |
| `php artisan migrate`                                  | Run database migrations            |
| `php artisan serve`                                    | Start Laravel server               |
| `git clone <repo>`                                     | Clone GitHub repo                  |
| `composer install`                                     | Install PHP dependencies           |
| `php artisan key:generate`                             | Generate app encryption key        |

# 🛠 Tech Stack

Laravel → Backend framework

React → Frontend library

Vite → Build tool for frontend assets

MySQL / PostgreSQL / SQLite → Database (configurable) 


## 📄 License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

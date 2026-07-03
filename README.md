# 🔐 LaravelAuth

A modern authentication boilerplate built with **Laravel 12**, featuring a premium 
dark glassmorphism interface designed for developers.

![Laravel](https://img.shields.io/badge/Laravel-12.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.2+-777BB4?style=for-the-badge&logo=php&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## ✨ Features

- 🔑 **Login & Register** — Secure authentication with validation
- 🔁 **Password Reset** — Email-based reset flow
- 📊 **Dashboard** — User info cards with quick actions
- 👤 **Profile Management** — Edit name, email, and password
- 🌙 **Dark UI** — Premium glassmorphism design with animated background
- 🛡️ **CSRF Protection** — Built-in Laravel security
- 📱 **Fully Responsive** — Works on all screen sizes

---

## 🛠️ Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Backend    | Laravel 12, PHP 8.2+    |
| Frontend   | Blade, Tailwind CSS 3   |
| Build Tool | Vite 7                  |
| Auth       | Laravel Breeze          |
| Database   | MySQL / SQLite          |
| Font       | Inter (Google Fonts)    |

---

## 🚀 Getting Started

### 1. Clone the repository
git clone https://github.com/your-username/LaravelAuth.git
cd LaravelAuth

### 2. Install dependencies
composer install
npm install

### 3. Environment setup
cp .env.example .env
php artisan key:generate

### 4. Configure database in `.env`
DB_CONNECTION=mysql
DB_DATABASE=laravel_auth
DB_USERNAME=root
DB_PASSWORD=

### 5. Run migrations
php artisan migrate

### 6. Start the dev servers
php artisan serve
npm run dev

### 7. Visit the app
http://127.0.0.1:8000

---

## 📸 Pages

| Page            | Route               |
|-----------------|---------------------|
| 🏠 Welcome      | `/`                 |
| 🔐 Login        | `/login`            |
| 📝 Register     | `/register`         |
| 🔑 Forgot Pass  | `/forgot-password`  |
| 📊 Dashboard    | `/dashboard`        |
| 👤 Profile      | `/profile`          |

---

## 📁 Project Structure

resources/
├── views/
│   ├── auth/          # Login, Register, Forgot Password
│   ├── layouts/       # App, Guest, Navigation
│   ├── components/    # Reusable Blade components
│   ├── profile/       # Profile edit views
│   └── dashboard.blade.php
└── css/
    └── app.css        # Tailwind + custom styles

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

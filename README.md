<p align="center">
    <a href="https://www.codehunger.in" target="_blank">
        <img src="https://www.codehunger.in/assets/image/logo.png" alt="CodeHunger Logo">
    </a>
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

# Create Sidebar and Simple CRUD in Laravel Filament v3 (Step-by-Step)

This repository demonstrates a clean and modern way to build an **admin dashboard with sidebar and CRUD functionality** using **Laravel Filament v3**. With minimal setup, you'll get a full-featured backend panel powered by Livewire and TailwindCSS.

---

## ✨ Features

- Laravel Filament v3 installation
- Responsive admin dashboard at `/admin`
- Sidebar navigation with grouped links and icons
- Simple CRUD for `Project` model with:
  - Searchable table
  - Create/Edit/Delete actions
  - Custom form and table columns
- Dark mode support
- "Create & Create Another" button disabled
- Lightweight and fully extendable

---

## 🧑‍💻 Technologies Used

- Laravel 10+
- Filament v3
- TailwindCSS
- Livewire
- Blade Components

---

## 📝 Blog Tutorial

Read the complete step-by-step blog here:

👉 [How to Create a Sidebar and Simple CRUD in Laravel Filament v3 - CodeHunger](https://www.codehunger.in/blog/how-to-create-a-sidebar-and-simple-crud-in-laravel-filament-v3-step-by-step-guide)

---

## 📂 Folder Structure

- `app/Models/Project.php` – Eloquent model
- `app/Filament/Resources/ProjectResource.php` – CRUD definition
- `app/Filament/Resources/ProjectResource/Pages` – Create/Edit/List pages
- `resources/views/` – Blade templates for UI (if needed)
- `routes/web.php` – Web routes (Laravel default)
- `.env` – Environment configuration

---

## ⚙️ Setup Instructions

1. Clone this repo:
```bash
git clone https://github.com/your-username/filament-crud-demo.git
cd filament-crud-demo

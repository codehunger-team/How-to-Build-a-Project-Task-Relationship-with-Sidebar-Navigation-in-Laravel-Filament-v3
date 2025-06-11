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

# Project-Task Relationship with Sidebar Navigation in Laravel Filament v3 (Step-by-Step)

This repository demonstrates how to build a fully functional **Project-Task relationship** with a sidebar navigation using **Laravel Filament v3**. Perfect for task management systems, CRMs, or project dashboards.

---

## ✨ Features

- Laravel Filament v3 installation and setup
- Sidebar navigation with icons and grouped resources
- CRUD functionality for:
  - Project
  - Task (linked to Project)
- One-to-many relationship between Project and Task
- Resource pages for Create, Edit, and List
- Relationship-aware dropdowns for linking Tasks to Projects
- Dark mode support
- Clean and extendable codebase

---

## 🧑‍💻 Technologies Used

- Laravel 10+
- Filament v3
- TailwindCSS
- Livewire
- Eloquent Relationships

---

## 📝 Blog Tutorial

Read the full step-by-step implementation guide:

👉 [How to Build a Project-Task Relationship with Sidebar Navigation in Laravel Filament v3](https://www.codehunger.in/blog/how-to-build-a-project-task-relationship-with-sidebar-navigation-in-laravel-filament-v3-step-by-step-guide)

---

## 📂 Folder Structure

- `app/Models/Project.php` – Eloquent model for projects
- `app/Models/Task.php` – Eloquent model for tasks
- `app/Filament/Resources/ProjectResource.php` – Project CRUD resource
- `app/Filament/Resources/TaskResource.php` – Task CRUD resource
- `app/Filament/Resources/TaskResource/Pages` – Pages for listing, creating, and editing tasks
- `resources/views/` – Optional Blade view overrides
- `routes/web.php` – Laravel routes (default)
- `.env` – Environment config for database

---

## ⚙️ Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/your-username/project-task-filament.git
cd project-task-filament

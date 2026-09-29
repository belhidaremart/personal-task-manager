# Personal Task Manager

A simple web-based task management system built using Laravel.  
The system helps users organize their tasks by allowing them to create, view, edit, and delete tasks.


---Developer---
Remart S. Belhida

BSIT 2 SEC 1

Personal Task Manager  

Laravel Project

---Development Assistance---

Developed with assistance from **ChatGPT (OpenAI)** for
coding guidance, debugging, UI/CSS suggestions, and project documentation.

---Features---
- Create new tasks
- View all tasks
- Edit existing tasks
- Delete tasks
- Set task status
- Set due dates
- Responsive user interface

---Technologies Used---
- Laravel 12
- PHP 8.2
- MySQL / MariaDB
- HTML
- CSS
- JavaScript
- Vite
- XAMPP
- Visual Studio Code

---Task Information---
Each task contains:

- Task Name
- Description
- Status
- Due Date

---Project Structure---
personal-task-manager/
│
├── app/
│   ├── Http/
│   │   └── Controllers/
│   │       └── TaskController.php
│   │
│   └── Models/
│       └── Task.php
│
├── database/
│   └── migrations/
│
├── resources/
│   ├── css/
│   │   └── app.css
│   │
│   └── views/
│       └── tasks/
│           ├── index.blade.php
│           ├── create.blade.php
│           └── edit.blade.php
│
├── routes/
│   └── web.php
│
└── README.md


Setup Instructions

1. *Start XAMPP*
   Open the XAMPP Control Panel and start the *Apache* and *MySQL* modules.

2. *Create the database*
   Go to http://localhost/phpmyadmin and create a new database matching the DB_DATABASE value you'll set in .env (e.g. task_manager).

3. *Install PHP dependencies*
   
   composer install
   

4. *Create the environment file*
   
   cp .env.example .env
   

5. *Generate the application key*
   
   php artisan key:generate
   

6. *Run fresh database migrations*
   
   php artisan migrate:fresh
   

7. *Start the development server*
   
   php artisan serve
   

8. *Open the app in your browser*
   
  (http://127.0.0.1:8000/)
   
ScreenShot




<img width="1892" height="845" alt="image" src="https://github.com/user-attachments/assets/6560307d-57ca-4835-acd0-20e92731ec81" />








<img width="1915" height="857" alt="image" src="https://github.com/user-attachments/assets/112d01bd-915e-4a74-92f2-f5bb3971efb4" />


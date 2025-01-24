Simple Task Management API Using laravel - Created Bt Md. Shawn Shikder Sonet

## Installation

```
composer install
cp .env.example .env
php artisan key:generate
```

## Create Database
Name: task_api


```
php artisan migrate
php artisan db:seed
```

## Login Credentials

```
Email: admin@admin.com
Password: 123456
```

## Auth APIs

```
POST http://localhost:8000/api/login
POST http://localhost:8000/api/login
POST http://localhost:8000/api/logout
```

## Task APIs

```
GET http://localhost:8000/api/tasks


POST http://localhost:8000/api/tasks
{
  "title": "Task Title",
  "description": "Task description"
}


PUT http://localhost:8000/api/tasks/1
{
  "status": 1
}


DELETE http://localhost:8000/api/tasks/1
```


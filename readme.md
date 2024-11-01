# LMS Platform Made with Laravel 10 | Php 08.2

===========================================================================
  
# Web laravel ini tediri dari
- User_Login
- User_Register

- Admin_Login
- Teacher_Login

===========================================================================

# Login system
  - User_Login
    Email: Student@mail.com
    Password: 123
  
  - Teacher_Login
    Email: Teacher@mail.com
    Password: 123

  - Admin_Login
    Email: Admin@mail.com
    Password: 123
    
===========================================================================


# Installation
1. Clone this repo
```
git clone https://github.com/emtiazzahid/e-learning.git
```

2. Install composer packages
```
cd e-learning
```
```
composer install
```

3. Create and setup .env file
```
cp .env.example .env
```
```
php artisan key:generate
```

6. Migrate and insert records
```
php artisan migrate --seed
```


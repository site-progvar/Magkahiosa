# Magkahiosa Project

## Description

    Magkahiosa Project aims to address the redundancy of signing in SARF

## Dependencies

-   php
-   composer
-   local database (mysql || xampp || lamp || postgresql || any)
-   nodejs
-   git

## Setup

### 1. Fork this repository

### 2. Clone this repository

    git clone https://github.com/site-progvar/magkahiosa.git

### 3. Change directory to magkahiosa

    cd magkahiosa

### 4. Open VS CODE using cmd

    code .

### 5. Open terminal in VS CODE in gitbash

### 6. Copy env.example and change it to .env

<<<<<<< HEAD
<<<<<<< HEAD
    cp .env.example .env 
=======
    cp .env.example .env
>>>>>>> 517001b4191123cd281bfcddad4dafecbd3d108f
=======
    cp .env.example .env 
>>>>>>> bff0ab9864ae11802dc045b5d145a6004c6c2c58

### 7. Configure env file

### 8. Run Composer Update

    composer update

### 9. Run migration and seeder

    php artisan migrate:fresh --seed

### 10. Run generate key

    php artisan key:generate

### 11. Run npm install

    npm install

### 12. Run Artisan Serve

    php artisan serve

### 13. Run Npm dev

    npm run dev

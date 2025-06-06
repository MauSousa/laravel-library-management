# Laravel libray management system
This project is made with laravel, Vue, Inertia, Tailwindcss.

## Installation instructions

1. Install php dependencies
    - ```composer install```
    - ```cp .env.example .env```
    - ```php artisan key:generate```
    - ```php artisan migrate```
2. Install npm dependencies
    - ```npm install```
    - ```npm run build```

The ```npm run build``` command is important to run the test suite.

3. Run the test suite
    - ```composer test```

4. Run the linter
    - ```composer lint```

5. Test php types
    - ```composer test:types```

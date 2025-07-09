# Agency Portfolio

This repository now includes a minimal Laravel skeleton. The demo page is stored in `resources/views/welcome.blade.php` and uses Alpine.js and TailwindCSS.

## Requirements
- PHP 8.1+
- Composer

## Setup
1. Install dependencies:
   ```bash
   composer install
   ```
2. Copy `.env.example` to `.env` and generate an app key:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```
3. Serve the application:
   ```bash
   php artisan serve
   ```

Then visit `http://localhost:8000` to view the agency site.

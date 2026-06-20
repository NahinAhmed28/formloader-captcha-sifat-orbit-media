# Formloader Captcha Sifat Orbit Media

This Laravel-based project focuses on form loading, form submission, and captcha validation for an Orbit Media workflow.

## Features

- Form rendering/submission workflow
- Captcha validation integration point
- Laravel backend for request handling
- Environment-based secret/configuration management

## Modules

- Form module: fields, validation, and submission processing
- Captcha module: provider keys, verification, and bot-prevention flow
- Admin module: submitted record review when enabled
- Data module: models, migrations, and stored submissions
- Integration module: captcha provider or external service configuration

## System Architecture

The system follows Laravel MVC. Users submit forms through views, controllers validate input and captcha tokens, service classes can verify captcha providers, and models persist valid submissions. Captcha secrets must live in environment variables.

## Getting Started

```bash
git clone https://github.com/NahinAhmed28/formloader-captcha-sifat-orbit-media.git
cd formloader-captcha-sifat-orbit-media
composer install
cp .env.example .env
php artisan key:generate
npm install
npm run dev
php artisan serve
```

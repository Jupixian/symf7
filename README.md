# symf7

An experimental [Symfony 7](https://symfony.com/) application.

## Requirements

- PHP 8.2+
- [Composer](https://getcomposer.org/)

## Getting Started

```bash
# Install dependencies
composer install

# Start the development server
php -S localhost:8000 -t public/
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Running Tests

```bash
php bin/phpunit
```

## Project Structure

```
├── bin/           # Console entry point
├── config/        # Application configuration
├── public/        # Web root (index.php)
├── src/           # Application source code
│   ├── Controller/
│   └── Kernel.php
├── templates/     # Twig templates
├── tests/         # PHPUnit tests
└── var/           # Cache and logs (not committed)
```

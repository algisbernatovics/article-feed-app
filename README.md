# Article Feed App

A custom PHP MVC-style article platform using routing, Twig templates, SQL data, and JSONPlaceholder-inspired content.

## Overview

A custom PHP MVC-style article platform using routing, Twig templates, SQL data, and JSONPlaceholder-inspired content.

## Preview

![Article Feed preview](./prev0.png)
![Article Feed detail preview](./prev1.png)

## Features

- Article, user, and comment models.
- Controllers for showing, adding, editing, and deleting articles/users/comments.
- Twig-based views and FastRoute routing.
- Database schema/sample SQL included.
- Preview screenshots included.

## Tech Stack

- PHP
- Composer
- Guzzle
- FastRoute
- Twig
- PHP-DI
- Doctrine DBAL
- Dotenv
- SQL

## Project Structure

- `public_html/index.php` - front controller
- `app/Controllers/` - HTTP controllers
- `app/Models/` - article, user, and comment models
- `app/Views/` - Twig templates
- `homeNews.sql` - database dump/schema data

## Getting Started

Install dependencies and configure environment:

```bash
composer install
cp .envExample .env
```

Serve the `public_html` entry point with your local PHP server or web server, and import `homeNews.sql` if database data is required.

## Portfolio Notes

- Demonstrates custom MVC architecture without Laravel.
- Shows CRUD-style application structure, routing, templating, and persistence.

## Status

Portfolio-ready PHP web application.

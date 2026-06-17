# Article Feed App

A custom PHP MVC-style article platform using routing, Twig templates, SQL data, and JSONPlaceholder-inspired content.

## Overview

This project demonstrates a framework-light PHP application with controllers, models, views, dependency wiring, SQL data, and external API-oriented structure.

## Preview

![Article Feed preview](./prev0.png)
![Article Feed detail preview](./prev1.png)

The screenshots show the article listing and detail-style pages included with the repository.

## Features

- Article, user, and comment models.
- Controllers for showing, adding, editing, and deleting articles/users/comments.
- Twig-based views and FastRoute routing.
- Database schema/sample SQL included.
- JSONPlaceholder-style content/API practice.

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

## Run

```bash
composer install
cp .envExample .env
```

Serve the `public_html` entry point with your local PHP server or web server, and import `homeNews.sql` if database data is required.

## Project Structure

- `public_html/index.php` - front controller
- `app/Controllers/` - HTTP controllers
- `app/Models/` - article, user, and comment models
- `app/Views/` - Twig templates
- `homeNews.sql` - database dump/schema data

## License

MIT License. See [LICENSE](./LICENSE).

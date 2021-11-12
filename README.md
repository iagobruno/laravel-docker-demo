# laravel-docker-demo

Forked from https://github.com/iagobruno/my-first-laravel-app.

## Getting started

Please check the official [laravel/sail documentation](https://laravel.com/docs/8.x/sail) before you start.

Clone this repo and run commands in the order below:

```bash
> composer install
> yarn install
> cp .env.example .env # And edit the values
> php artisan key:generate
```

Then start docker containers and run the migrations:

```bash
> sail up -d
> sail artisan migrate
> sail artisan db:seed
```

You can now access the server at http://localhost

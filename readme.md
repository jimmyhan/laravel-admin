### Installation

Install all Dependencies

```
git clone git@github.com:jimmyhan/laravel-admin.git
cd path/to/your_project
composer install
```

Install node modules

```
npm install
```

## Setting Your .env

```
cp .env.example .env
php artisan key:generate
```

## Confirm the website it up

```
php artisan serve
```
Open browser with url http://localhost:8000

## Compile scss/js from resources/assets to public

```
npm run dev (or ‘npm run prod' for production)
```
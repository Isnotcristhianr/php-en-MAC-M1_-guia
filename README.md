# php-en-MAC-M1_-guia

## Installation

### Clone the repository

```bash
git clone 
```

### Install dependencies

```bash
composer install
```

### Create a copy of your .env file

```bash
cp .env.example .env
```

### Generate an app encryption key

```bash
php artisan key:generate
```

### Create an empty database for our application

### In the .env file, add database information to allow Laravel to connect to the database.

### Migrate the database

```bash
php artisan migrate
```

### Install node modules

```bash
npm install
```

### Build assets using Laravel Mix

```bash
npm run build
```

### Start the local development server

```bash
php artisan serve
```

### You can now access the server at http://localhost:8000

.[!Note]
Solo para Mac

### Laravel Log Error
```bash
sudo chown -R daemon:daemon ''
```

### Error Git Init
```bash
sudo  chmod -R 775 ''
```

### BoostrapCache
```bash
chmod -R 755 storage chmod -R 755 bootstrap/cache
```

.[!Important]
### React correctly on mac with Laravel

```bash
php artisan storage:link
```

```bash
npm run dev
```

# Create project with docker

## Setup

Add sail's alias like below.
```
alias sail='[ -f sail ] && bash sail || bash vendor/bin/sail'
```

So you can sail command like this.
```
sail up
```

And migrate.
```
sail artisan migrate
```

## Install Laravel Breeze

Install laravel/breeze by this command.
```
composer require laravel/breeze --dev
```

### Add React
Command like below.
```
php artisan breeze:install react
```

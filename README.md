alias alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'

# install package
sail composer require juststeveking/launchpad

sail artisan setup:phpstan
sail artisan setup:laravel-pint

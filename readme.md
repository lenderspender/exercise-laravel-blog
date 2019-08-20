## Laravel introduction exercise

Create a very simple blog built on the Laravel framework where a user can perform the following actions:
- viewing a list of all existing blog items
- add a new blog item
- delete a blog item

Note the following:
- a blog item has only a title and content attribute. 
- ignore user authentication, a user in this case is a non-logged in user (a.k.a. guest)
- sqlite has been configured for your database connection
- for your (and our) viewing pleasure you can use Bootstrap, but don't spend more than a few minutes on styling!
- your code should contain at least one "Feature" (a.k.a. acceptance) test, see https://laravel.com/docs/testing

When finished, make sure the following script runs without errors:
```bash
git clone https://github.com/<yourid>/laravel-blog-exercise laravel-blog-exercise
cd laravel-blog-exercise
composer install
php artisan migrate
vendor/bin/phpunit
php artisan serve
```

Don't spend more than 4 hours on this.

Good luck!

###Getting started
```bash
git clone https://github.com/lenderspender/laravel-blog-exercise laravel-blog-exercise
cd laravel-blog-exercise
composer install
php artisan serve
```
https://laravel.com/docs/ is your best friend ;-)
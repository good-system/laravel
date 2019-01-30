# good-system/organization

This is a fork of [laravel/laravel](https://github.com/laravel/laravel) version 5.7.19, with the following changes to start an application for various community organization operations.


## Required for Dev

- Create a database `homestead`
- Grant permission for `homestead` to user `homestead` and password `secret`
 
## Required for production

## Version Equivalency

laravel/laravel 5.7.19

### (v)0.0.1 

Cloned.

### (v)0.0.2 
 
- Removed `app/User.php`
- Changed `name` section in `composer.json`
- Moved all but `php` and `laravel/framework` from `require` section to `require-dev` section in `composer.json`
- Added `good-system/core` to `require` section in `composer.json`

### (v)0.0.3
 
- Added scaffolding files for built-in authentication by running `php artisan make:auth`
- Enabled email verification for registration by following instructions in [Laravel Documentation](https://laravel.com/docs/5.7/verification)

 

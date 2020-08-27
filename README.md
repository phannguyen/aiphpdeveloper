# Using Composer
Composer is a tool for dependency management in PHP. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you. Drupal uses Composer to manage the various libraries that it depends on. Modules can also use Composer to include 3rd party libraries. Drupal site builds can use Composer to manage the various modules the site is composed of. Learn how to use Composer in your Drupal project.

`composer install`

https://www.drupal.org/docs/develop/using-composer


# Config file 

Update config_sync_directory: 

`$settings['config_sync_directory'] = '../config/sync';`

https://www.drupal.org/docs/configuration-management/keeping-your-local-and-remote-sites-synchronized

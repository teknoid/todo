[Related blog post](http://zenofcoding.com/2014/11/06/cake3-baby-steps-step-1-getting-started/)

# CakePHP 3 and jQuery "To-do" Application

[![Build Status](https://api.travis-ci.org/cakephp/app.png)](https://travis-ci.org/teknoid/todo.svg?branch=develop)
[![Coverage Status](https://coveralls.io/repos/github/vlad-ko/todo/badge.svg?branch=master)](https://coveralls.io/github/vlad-ko/todo?branch=master)
[![License](https://poser.pugx.org/cakephp/app/license.svg)](https://packagist.org/packages/cakephp/app)

## Installation

1. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist -s dev cakephp/app [app_name]`.

If Composer is installed globally, run
```bash
composer create-project --prefer-dist -s dev cakephp/app [app_name]
```

You should now be able to visit the path to where you installed the app and see
the setup traffic lights.

## Configuration

Read and edit `config/app.php` and setup the 'Datasources' and any other
configuration relevant for your application.

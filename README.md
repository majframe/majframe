<h1 style="text-align: center; width: 100%;"><a href="http://majframe.com" rel="nofollow">
    <img src="logo.png" style="max-width:100%;" alt="Majframe">
</a></h1>

Majframe is a php7.4 MVC framework.
It uses:
* Dependency Injection
* Routing annotations
* Doctrine 2 ORM

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Installing

The best way to install Web Project is using Composer.

```
composer create-project majframe/majframe
```

Make directories `temp/` and `log/` writable.


### Web Server Setup

The simplest way to get started is to start the built-in PHP server in the root directory of your project:
```
php -S localhost:8000 -t www
```
Then visit `http://localhost:8000` in your browser.

## Running the tests

We use [Codeception](https://codeception.com/quickstart) for testing.
Running the tests is really simple. You just run `codecept` or `codecept-steps` script from composer.

## Requirements
* Majframe requires PHP 7.4

## Code style
* PSR-4
* 4 spaces instead of tab
* single class in every file

## Authors

* **Ondřej Maxa** - ondrej@maxa.expert - http://ondrej.maxa.expert/

## License

This project is licensed under the GPL v3.0 License - see the [LICENSE.md](LICENSE.md) file for details
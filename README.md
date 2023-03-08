# Weeyn Review Module
Weeyn catalog review module

![Packagist PHP Version](https://img.shields.io/packagist/dependency-v/weeynsoft/catalog-review/php)
![Packagist Version](https://img.shields.io/packagist/v/weeynsoft/catalog-review)
![Packagist Downloads](https://img.shields.io/packagist/dt/weeynsoft/catalog-review?label=download)
![GitHub](https://img.shields.io/github/license/weeynsoft/catalog-review)


This is the standalone review module of the [Weeyn](https://weeyn.com).

## Installation

(As Standalone Component)

1. `composer require weeynsoft/catalog-review`
2. `php artisan vendor:publish --provider="Konekt\Concord\ConcordServiceProvider"`
3. Add `Weeyn\CatalogReview\Providers\ModuleServiceProvider::class` to modules in `config/concord.php`
4. `php artisan migrate`

## Usage

See the [Weeyn Review Module Documentation](https://weeyn.com/docs/master/catalog-review) for more details. 

## About Us

Weeyn development is led by the core team.
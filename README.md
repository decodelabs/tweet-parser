# Chirp

[![Latest Version](https://img.shields.io/packagist/v/decodelabs/chirp.svg?style=flat-square)](https://packagist.org/packages/decodelabs/chirp)
[![Total Downloads](https://img.shields.io/packagist/dt/decodelabs/chirp.svg?style=flat-square)](https://packagist.org/packages/decodelabs/chirp)
[![Build Status](https://img.shields.io/travis/decodelabs/chirp/develop.svg?style=flat-square)](https://travis-ci.org/decodelabs/chirp)
[![PHPStan](https://img.shields.io/badge/PHPStan-enabled-44CC11.svg?longCache=true&style=flat-square)](https://github.com/phpstan/phpstan)
[![License](https://img.shields.io/packagist/l/decodelabs/chirp?style=flat-square)](https://packagist.org/packages/decodelabs/chirp)

Twitter tools for PHP


## Installation

Install the library via composer:

```bash
composer require decodelabs/chirp
```

## Usage

Parse a tweet into HTML:

```php
use DecodeLabs\Chirp\Parser;

$parser = new Parser();
echo $parser->parser($myTweet);
```


## Licensing
Chirp is licensed under the MIT License. See [LICENSE](./LICENSE) for the full license text.

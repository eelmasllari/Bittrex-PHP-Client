# Bittrex PHP Client

## Introduction / Preamble

## Installation

Require this package, with [Composer](https://getcomposer.org/), in the root directory of your project.

``` bash
$ composer require faustbrian/bittrex-php-client
```

## Usage

```php
use BrianFaust\Bittrex\Bittrex;

$client = new Bittrex('key', 'secret');

dump($client->getWithdrawalHistory('BTC'));
```

## Testing

``` bash
$ phpunit
```

## Security

If you discover a security vulnerability within this package, please send an e-mail to Brian Faust at hello@brianfaust.me. All security vulnerabilities will be promptly addressed.

## Credits

- [Brian Faust](https://github.com/faustbrian)
- [All Contributors](../../contributors)

## License

[MIT](LICENSE) © [Brian Faust](https://brianfaust.me)

# alcohol\iso4217

A library providing ISO 4217 data.

[![Latest Stable Version](https://poser.pugx.org/alcohol/iso4217/v/stable.png)](https://packagist.org/packages/alcohol/iso4217)
[![Build Status](https://travis-ci.org/alcohol/iso4217.png?branch=master)](https://travis-ci.org/alcohol/iso4217)
[![License](https://poser.pugx.org/alcohol/iso4217/license.png)](https://packagist.org/packages/alcohol/iso4217)

## Usage

Code:

``` php
use Alcohol\ISO4217;

ISO4217::getByAlpha3('EUR');
 // or
ISO4217::getByNumeric('978');
```

Result:

```
Array
(
    [name] => Euro
    [alpha3] => EUR
    [numeric] => 978
    [exp] => 2
    [country] => Array
        (
            [0] => AX
            [1] => AD
            ...
            [30] => ES
            [31] => ZW
        )
)
```

## Installation

Either install it directly from command line using composer:

``` sh
$ composer require alcohol/iso4217
```

or include it as a dependency in your composer.json:

``` javascript
{
    "require": {
        "alcohol/iso4217": "~1.0"
    }
}
```

## Contributing

Feel free to submit a pull request or create an issue ticket.

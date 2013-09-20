# Iban

![Build Status](https://travis-ci.org/jschaedl/Iban.png)

## Usage

    <?php
    
    /* IBANValidator */
   	$ibanValidator = new \IBAN\Validation\IBANValidator();
   	$isValid = $ibanValidator->validate('DE89370400440532013000');
   	
   	/* IBANGenerator */
   	$ibanGenerator = new \IBAN\Generation\IBANGenerator();
   	$generatedIban = $ibanGenerator->generate('DE', '10010010', '1001001000');
   	
    
## How to Install

...

## Contributions

### Pull Requests

…

### Style Guide

…

### Unit Testing

All pull requests must be accompanied by passing unit tests and complete code coverage. This repository uses phpunit
and Composer. You must run `composer install` to install this package's dependencies before the unit tests will run.

## Author

[Jan Schädlich](https://github.com/jschaedl)

## License

MIT Public License

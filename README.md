# Boilerplate for PHP projects #
Contains everything needed for starting a new project in small amount of time.

## Disclaimer ##
This is for my own use, so the parts of the boilerplate will be highly opinionated.

## How to use it ##
```bash
composer create-project dusank/boilerplate-php --repository-url=https://raw.githubusercontent.com/DusanKasan/boilerplate-php/master YOUR_PROJECT_DIR
```

## What does it contain ##
* Stuff in composer.json
    * [Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer)
    * [Mess Detector](http://phpmd.org/)
    * [Behat](www.behat.com)
    * [PHPSpec](www.phpspec.com)
    * [PHPSpec Coverage Plugin](https://github.com/henrikbjorn/PhpSpecCodeCoverageExtension)
* PHPSpec setup to generate coverage
* Mess detector ruleset file
* Pretty strict scrutinizer setup
* Default .gitignore
    * ignores /vendor and coverage output
* This Readme
* MIT License

## What to do after creating new project ##
* Set it up in Scrutinizer
* Set it up in SensioLabs Insight
* Write som Behat tests
* Red/Green/Refactor PHPSpec tests till done :)

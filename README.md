# URL Scanner Script

## Description

A PHP script that scans a list of URLs and reports inaccessible URLs to standard out.

## Usage

This is a command line script that should be executed with your local PHP
binary.

    php scan.php ./urls.csv

The first argument is the path to the `scan.php` file. The second argument is
the path to the `urls.csv` file. The CSV file should contain a list of
URLs, one URL per line.

## Installation

Because this repository is not a PHP component, you should clone this repository
to your local computer with:

    git clone https://github.com/modern-php/url-scanner-script.git

After you clone the repository, install its Composer dependencies. From within
this repository's directory on your local machine, run:

    composer install

## Documentation

<https://github.com/modern-php/url-scanner-script>

## Copyright

Copyright 2014 Josh Lockhart

## License

This repository is distributed with the MIT Public License.

## Author

Josh Lockhart<br/>
Twitter: @codeguy<br/>
Web: <http://programming.oreilly.com/jlockhart>

## How to submit bug reports

Open a new issue in the GitHub issue tracker here:

<https://github.com/modern-php/url-scanner-script/issues>

## How to contribute

You can send a pull request to the master branch here:

<https://github.com/modern-php/url-scanner-script>

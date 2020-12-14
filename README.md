![Developer Tools](https://github.com/binarykorra/php-dev/blob/main/php_api.png?raw=true)

# PHP Developer Tools

* Soon to be, Tools in Recognizing and Helping build PHP Extensions with API headers.
* Usual PHP Zend Header Files are found at "/usr/include/php" or "usr/local/include/php".

## How to Start?

* apt-get update -y --fix-missing
* apt-get install php php-dev -y
* apt-get install re2c bison -y

## Bash API / Build Number Locator

* This Tool will help you recognize what PHP Version you are using currently while building Extensions.
* Using php-dev & php install via apt-get (aptitude) install from Debian Repos.
* Its currently being maintained by me, just change the Prefix for the PHP Location.
* Then Edit the IncludeDir for the Folder which where the API No Headers, reside.

## Bash PHP Extension's Builder

* This Tool eases up the use of One-Liner command, phpize then ./configure
* Production-ready and Fully-tested, So code up' and use it properly

## Bash Maketest Extension Tester / Checker

* This Tool eases up the use of One-Liner Command, in testing the Functions of the PHP Extension.
* Use either Bash or Sh (./maketest.sh.installer) in order to use the Tool and executing the Extension Functions.

## Demo, to test the Extension

* php -dextension=hello.so -r "echo name('Abcd');"
* php -dextension=hello.so -r "echo hello_world();"

## Notice

* Tested on PHP7.4.3
* Soon will be, PHP8.0
* Extensions Folder: "/usr/lib/php/php_api_number/" or "/usr/lib/php/"

## Releases Page

* https://github.com/binarykorra/php-dev/releases/

## Copyright (2020)

* Xin Snowflakes, 09225205353

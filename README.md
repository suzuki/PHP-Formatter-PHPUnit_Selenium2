PHP-Formatter-PHPUnit_Selenium2
===============================

Selnium IDE: PHP Formatter for PHPUnit_Extensions_Selenium2TestCase

These codes are inspire from [Webdriver-PHP-Formatter](https://github.com/jupeter/Webdriver-PHP-Formatter)

## HOW TO USE


### Build
- Build xpi file.

	$ make


### Install to Firefox browser
1. Drag and drop `build/phpformatter@zatsubun.com.xpi` file to your Firefox browser.


### Make Test
1. Open Selenium IDE.
2. Make a testcase.
3. Export a testcase, select `PHP / PHPUnit / PHPUnit Selenium2TestCase` format.
4. Save your a testcase.


### Run PHPUnit
1. Run your testcase.

	$ phpunit --colors YOUR_TEST_CASE.php

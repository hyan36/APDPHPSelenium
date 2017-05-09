APDPHPSelenium Example
======================

 

This project is developed as a part of selenium tutorial for PHP

 

| Key              | Value      |
|------------------|------------|
| Author           | Haihao Yan |
| Version          | 1.0.0      |
| Operation System | Windows    |

 

Library Dependency
------------------

Following library are required in order to run the project properly. Composer
need to be pre-installed for running the project.

 

| Name              | Description                             | URL                                       |
|-------------------|-----------------------------------------|-------------------------------------------|
| Composer          | Used to include PHP library             | https://getcomposer.org/                  |
| PHPUnit           | Unit testing framework for PHP          | https://phpunit.de/                       |
| Facebook Webdrive | Facebook webdrive for PHP selenium test | https://github.com/facebook/php-webdriver |

 

Software Dependency
-------------------

The project need following software to be included. They are already inside of
the /server folder for windows user. Linux / Mac user will need to download
Geckodriver separately.

 

| Name                       | Description                        | URL                                             |
|----------------------------|------------------------------------|-------------------------------------------------|
| Selenium Standalone Server | Local server for selenium testing  | http://www.seleniumhq.org/download/             |
| Geckodriver                | Firefox driver provided by Mozilla | https://github.com/mozilla/geckodriver/releases |

 

How to run the example
----------------------

 

1.  Compile the project via composer

`composer install`

1.  Start Selenium Server

`cd server`

`java -Dwebdriver.gecko.driver="geckodriver.exe" -jar selenium-server-standalone-3.4.0.jar`

1.  Run the Test

`vendor\\bin\\phpunit.bat GitHubTest.php`

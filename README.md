# Mage2 Module OrviSoft Newsletter

    ``orvisoft/module-newsletter``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Specifications](#markdown-header-specifications)
 


## Main Functionalities


## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/OrviSoft/Newsletter`
 - Enable the module by running `php bin/magento module:enable OrviSoft_Newsletter`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require orvisoft/module-newsletter`
 - enable the module by running `php bin/magento module:enable OrviSoft_Newsletter`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Specifications

 - Plugin
	- aroundExecute - Magento\Newsletter\Controller\Subscriber\NewAction > OrviSoft\Newsletter\Plugin\Frontend\Magento\Newsletter\Controller\Subscriber\NewAction




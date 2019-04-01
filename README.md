# Magento 2: Core
This is a wrapper for all of Alvis Magento 2 modules.

## Installation
Recommended installation through composer, within your Magento root directory enter the following:

    composer require alvis/magento2-core

Alternatively you can install manually by following these steps:

  1. [Download](https://github.com/jasonujmaalvis/magento2-core/archive/master.zip) the repo zip file and extract
  2. You should have a folder called 'magento2-core-master'. Rename this folder to 'Core'
  4. Under your Magento site folder create a new directory 'app/code/Alvis'
  5. Upload the module to this folder 'app/code/Alvis/Core'

## Enable the module

    php bin/magento module:enable Alvis_Core

You may also need to re-compile:

    php bin/magento setup:upgrade
    php bin/magento setup:di:compile

There are no configuration options for this module.

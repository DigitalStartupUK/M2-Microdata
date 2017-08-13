# M2-Microdata
Removes default microdata from Magento 2.1.7

# Credit
Please do **not credit me** for this exension. This is simply a repackaged extension based off a [Mageworx](http://blog.mageworx.com/2016/09/extending-rich-snippets-functionality-in-magento-2/) article I read

# Basic Installation
1. Upload files to `app/code/`
2. From Magento root directory, run: `composer require digitalstartup/microdata`
3. From Magento root directory, run: `composer update`
4. From Magento root directory, run: `php bin/magento setup:upgrade`

# Notes
There is no backend configuration. To check that this exension is working correctly, visit [Google Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool).

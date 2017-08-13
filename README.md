# M2-Microdata
Removes default microdata from Magento 2.1.7. It's unlikely that I'll maintain this extension, so please feel free to create Pull Requests. As far as I'm concerned this is a working community project.

# Credit
Please do **not credit me** for this exension. This is simply a repackaged extension based off a [Mageworx](http://blog.mageworx.com/2016/09/extending-rich-snippets-functionality-in-magento-2/) article I read some time ago.

# Basic Installation
Backup your Database and Files. As with any extension, **always** Test on Development installation before installing on Production environment
1. Upload files to `app/code/`
2. From Magento root directory, run: `composer require digitalstartup/microdata`
3. From Magento root directory, run: `composer update`
4. From Magento root directory, run: `php bin/magento setup:upgrade`

# Notes
There is no backend configuration. To check that this exension is working correctly, visit [Google Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool).

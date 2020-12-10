# Custom Shipping for Magento 2

This is a sample for Shipping module in Magento 2. You are free to use this module as a base for developing any custom shipping modules.

## Installation

#### Step 1 

##### Using Composer (recommended)

```
composer require magetop/magento2-custom-shipping
```

##### Manual Installation (not recommended)
To install Custom Shipping for Magento2
 * Download the extension
 * Unzip the file
 * Copy the content from the unzip folder for magento root folder



#### Step 2 -  Enable Custom Shipping Rate
 * php -f bin/magento module:enable --clear-static-content Magetop_Customshipping
 * php -f bin/magento setup:upgrade

#### Step 3 - Config Custom Shipping Rate
Log into your Magento Admin, then goto Stores -> Configuration -> Sales -> Shipping Methods -> Custom Shipping


Contribution
---
Want to contribute to this extension? The quickest way is to open a [pull request on GitHub](https://help.github.com/articles/using-pull-requests).


Support
---
If you encounter any problems or bugs, please open an issue on [GitHub](https://github.com/magetop/magento2-custom-shipping/issues).

Need help setting up or want to customize this extension to meet your business needs? Please email support@magetop.com and if we like your idea we will add this feature for free or at a discounted rate.

© Magetop eCommerce - Magento Extensions Store | [https://www.magetop.com/](https://www.magetop.com/)

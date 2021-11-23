# MageReactor Base module for Magento 2

This module contains all the necessary configurations that are common in all MageReactor's Modules.

## Install

### Composer

```bash
composer require magereactor/base
```

### Compatiblity
Currently this module is compatible with Magento 2.4.x


### Enable Module

```php
php bin/magento module:enable MageReactor_Base
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
```

You may need to Flush Magento Cache after installation.

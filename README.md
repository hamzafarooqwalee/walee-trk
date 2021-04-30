## Walee Tracking Plugin for Magento 2 


### 1. Requirements

+ **Magento 2.0.0 or greater**
+ **Composer PHP Dependency Manager**

### 2. Plugin installation

+ Open command prompt, go to `<MAGENTO_ROOT>` folder and run the following
commands:

```
$ composer require walee-dev/walee-tracking
$ php bin/magento setup:upgrade
$ php bin/magento setup:di:compile
$ php bin/magento setup:static-content:deploy
$ php bin/magento cache:clean
$ php bin/magento cache:flush
```

### 3. Plugin configuration

Plugin is auto configurable. No need of any configuration.

# Success!
Your Walee Tracking Plugin is now installed and configured.

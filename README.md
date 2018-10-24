# Easyflags

It's a metapackage for the [source code repository](https://github.com/swissup/module-easyflags).

#### Installation

```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/easyflags --prefer-source
bin/magento module:enable Swissup_Core Swissup_Easyflags
bin/magento setup:upgrade
```

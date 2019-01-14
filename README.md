# Easyflags

It's a metapackage for the [source code repository](https://github.com/swissup/module-easyflags).

## Installation

### Swissuplabls / Argento customers

Swissuplabs and Argento customers get access to Swissuplabs composer repository. If you want to install module via composer then please add Swissuplabs repo to your composer:

```bash
composer config repositories.ci.swissuplabs.com composer https://ci.swissuplabs.com/api/packages.json
```

For next steps go to http://docs.swissuplabs.com/m2/extensions/easyflags/installation/composer/

### Anyone else

In case you don't have Swissuplabs/Argento account and don't want to create one. It is not a problem. You still can use this module. Just follow commands below:

```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/easyflags
bin/magento module:enable Swissup_Core Swissup_Easyflags
bin/magento setup:upgrade
```

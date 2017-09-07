yii2-showloading
================

## Installation

### Composer

Simply add extension to your composer.json:
``` js
{
    "require": {
        "slimic960/yii2-showloading": "*"
    }
}
```
After this just update your dependencies as usual, e.g. by running `composer update`

##Configuration

To make the plugin work you just need to register asset bundle. Either specify it as a dependency, or register directly in your view like this:
``` php
use slimic960\showloading\ShowLoadingAsset;
ShowLoadingAsset::register($this);
```

##Sample usage

To show / hide loading indicator, simply call `showLoading()` / `hideLoading()` methods:
``` js
$('#my-content-panel-id').showLoading();
$('#my-content-panel-id').hideLoading();
```

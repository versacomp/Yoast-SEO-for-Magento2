# MaxServ_YoastSeo

## Introduction
We have developed this advanced SEO module in close corporation with YOAST. It incorporates the YOAST library into Magento2.  

## Requirements
Magento 2.1.*

## Latest version
The current stable version is 1.0.0. 

## Installation
Register the repository:

```
#command line
$ composer repositories.magento-module-yoastseo '{"type": "vcs", "url": "git@github.com:Yoast/magento-seo.git"}'

# OR

#composer.json
respositories: [
    ...
    {
        "type": "vcs",
        "url": "git@github.com:Yoast/magento-seo.git"
    },
    ...
]
```

Then install the module:

```
$ composer require maxserv/magento-module-yoastseo
```

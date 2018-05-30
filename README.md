## Magento 2 Polish Language Pack

It is wise to install **Magento 2 Polish Language Pack** on your Magento 2 store. Why I say that? Frankly speaking, if you want to go further on the international market, the first thing you need to concern is being sociable with the people living there and the shortest way to enter is synchronizing the language. Namely as in Poland, communicating in Polish will make you more convinient in eCommerce business or traditional business as well without creating any awkwardness for the visitors.

Read more [Magento 2 Polish Language Pack](https://www.mageplaza.com/magento-2-polish-language-pack.html)


## Overview

- Download & Contribute
- Install Polish Language Pack
- How to Install Polish Language Pack

## 1. Download & Contribute to Polish Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Polish Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-polish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-polish-language-pack/tarball/master)


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Polish Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Polish language pack via composer is never easier.

**Install Polish pack**:

```
composer require mageplaza/magento-2-polish-language-pack:dev-master
php bin/magento setup:static-content:deploy pl_PL
php bin/magento cache:flush

```


**Update  Polish pack**:

```
composer update mageplaza/magento-2-polish-language-pack:dev-master
php bin/magento setup:static-content:deploy pl_PL
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Polish language pack
- Step 2: Unzip Polish pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Polish language pack

You can download the language pack from above link

#### Step 2: Unzip Polish pack

Unzip the Polish language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip app/i18n/Mageplaza/pl_pl
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Polish pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-polish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-polish-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `pl_PL.zip` into `app/i18n/mageplaza/pl_PL/pl_PL.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Polish language pack
O
Now time to active the Polish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Polish language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

This language pack has been translated 
![language pack](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/pl

## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 pen-source](https://www.mageplaza.com/download-magento/), Magento 2 Commerce.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## 6. Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-polish-language-pack/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References:

- https://www.mageplaza.com/magento-2-polish-language-pack.html
- https://crowdin.com/project/magento-2








## Mageplaza extensions on Magento Marketplace, Github


- [Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [One Step Checkout](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)
- [SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html) ; [SMTP on Github](https://github.com/mageplaza/magento-2-smtp)
- [Blog](https://github.com/mageplaza/magento-2-blog)
- [Security](https://marketplace.magento.com/mageplaza-module-security.html)
- [Social Login](https://github.com/mageplaza/magento-2-social-login)

- [SEO](https://github.com/mageplaza/magento-2-seo) ; [SEO on Marketplace](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)

- [SMTP](https://github.com/mageplaza/magento-2-smtp)

- [Product Slider](https://github.com/mageplaza/magento-2-product-slider)

- [Banner](https://github.com/mageplaza/magento-2-banner-slider)

- [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)




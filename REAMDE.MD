## Instamojo Payment Gateway for Magento 2

This extension allows you to use Instamojo as payment gateway in your Magento 2 store.

## Installing via [Composer](https://getcomposer.org/)

```bash
composer require instamojo/instamojo-magento-2
php bin/magento module:enable Instamojo_Imojo --clear-static-content
php bin/magento setup:upgrade
```

Enable and configure Stripe in Magento Admin under `Stores -> Configuration -> Payment Methods -> Instamojo Payment Gateway`.


If you do not see Razorpay in your gateway list, please clear your Magento Cache from your admin
panel (System -> Cache Management).

## Support

Send your queries to support@instamojo.com
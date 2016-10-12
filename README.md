## Instamojo Payment Gateway for Magento 2

This extension allows you to use Instamojo as payment gateway in your Magento 2 store.

## Installing via [Composer](https://getcomposer.org/)

```bash
composer require instamojo/instamojo-magento-2
php bin/magento module:enable Instamojo_Imojo --clear-static-content
php bin/magento setup:upgrade
```

Enable and configure Instamojo in Magento Admin under `Stores -> Configuration -> Payment Methods -> Instamojo Payment Gateway`.

## Configuration

  - **Enabled:** Mark this as "Yes" to enable this plugin.
 
  - **Title:** Test to be shown to user during checkout. For example: "Pay using DB/CC/NB/Wallets"

  - **Checkout Label:** This is the label users will see during checkout, its default value is "Pay using Instamojo". You can change it to something more generic like "Pay using Credit/Debit Card or Online Banking".
     
  - **Client ID** and **Client Secret** - Client Secret and Client ID can be generated on the [Integrations page](https://www.instamojo.com/integrations/). Related support article: [How Do I Get My Client ID And Client Secret?](https://support.instamojo.com/hc/en-us/articles/212214265-How-do-I-get-my-Client-ID-and-Client-Secret-)
    
  - **Test Mode:** If enabled you can use our [Sandbox environment](https://test.instamojo.com) to test payments. Note that in this case you should use `Client Secret` and `Client ID` from the test account not production.

## Screenshots

![Instamojo extension under admin](http://i.imgur.com/uj2wMZ1.gif)

![Configuration](http://i.imgur.com/ltxylh3.png)

![Instamojo during checkout](http://i.imgur.com/Ayw3MnC.png)


## Support

For any issue send us an email to support@instamojo.com and share the `imojo.log` file. The location of `imojo.log` file is `var/log/imojo.log`.
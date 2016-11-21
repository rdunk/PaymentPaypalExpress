# PaymentPaypalExpress Module for ProcessWire 3.x

ProcessWire payment module for PayPal Express checkout using the v.zero SDK. Originally built for use with apeisa's [PaymentModule](https://github.com/apeisa/PaymentModule/) (PW3 branch).

## Requirements

- PHP 5.4 or newer
- ProcessWire 3.0.10 or newer
– PaymentModule ProcessWire module
- Composer

## Installation

1. In your ProcessWire installation root execute the following command in terminal:

````````
composer require rdunk/payment-paypal-express
````````	

2. Navigate to your ProcessWire admin modules page and refresh the module list.
3. Click "Install" next to the PaymentPayPalExpress module, it should appear under the "Payment" section.
4. Edit the module options and add the relevant data including API keys.

## Notes

Refer to the [v.zero SDK documentation](https://developer.paypal.com/docs/accept-payments/express-checkout/ec-vzero/get-started/) for more information.
This module uses version 3.5.0 of the Braintree Javascript SDK.
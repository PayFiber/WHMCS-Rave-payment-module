# WHMCS-Rave-payment-module
This is a payment Module for WHMCS that allows you to accept payments using Flutterwave Rave
 - **Contributors:** mr-flamez(Oluwole Adebiyi) Flamez
 - **Tags:** rave, flutterwave, payment gateway, bank account, credit card, debit card, nigeria, kenya, ghana, international, mastercard, visa, whmcs

## Requirements

- WHMCS installation.

## Description

Accept Credit card, Debit card and Bank account payment directly on WHMCS with the Rave payment gateway.

Signup for an account [here](https://ravepay.co)

Rave is available in:

* __Nigeria__
* __Ghana__
* __Kenya__


## Install
1. Copy [rave.php](modules/gateways/rave.php?raw=true) in [modules/gateways](modules/gateways) to the `/modules/gateways/` folder of your WHMCS installation.

2. Copy [rave.php](modules/gateways/callback/rave.php?raw=true) in [modules/gateways/callback](modules/gateways/callback) to the `/modules/gateways/callback` folder of your WHMCS installation.

3. Go to your WHMCS admin page, and click on setup
![Rave Installation Screenshot](https://image.prntscr.com/image/zcDRed9lQxOGMkC6nuBu5Q.png)

4. Payments > Payment Gateways
![Rave Installation Screenshot](https://image.prntscr.com/image/bc9RaoBeT1eteh3TWkAuIQ.png)

5 Click on all payment gateways
![Rave Installation Screenshot](https://image.prntscr.com/image/G4tzCx10QCGmCMMt1_38GQ.png)

6 Click on Rave Payment to activate
![Rave Installation Screenshot](https://image.prntscr.com/image/5_G1AE_XRgyAzyZQp1eUEw.png)

7 Enter your details
![Rave Installation Screenshot](https://image.prntscr.com/image/ZEn2QcSLRByuFinzF94pxg.png)

* __Company/Business Name__ - (Compulsory) customize the title of the Pay Modal.
* __Company/Business Description__ - (Compulsory) customize the description on the Pay Modal.
* __WHMCS Link__ - (Compulsory) The URL of WHMCS.
* __Logo__ - (Optional) customize the logo on the Pay Modal. Enter a full url (with 'http'). Default is Rave logo.
* __Public Key__ - Enter your public key which can be retrieved from "Pay Buttons" page on your Rave account dashboard.
* __Secret Key__ - Enter your public key which can be retrieved from "Pay Buttons" page on your Rave account dashboard.
* __Pay Button Text__ - (Optional) The text to display on the button. Default: "PAY NOW".
* __Test Mode__ - Tick to enable test mode.
* Click __Save Changes__ to save your changes.



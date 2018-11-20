SecurePay SecureXML
===================

Enables credit-card payments via the SecurePay gateway

## About

Hosted by [Doghouse](http://doghouse.agency/) 
on [Github](https://github.com/DoghouseMedia) 
because we needed to make changes to an unsupported Magento module 
that needed to be updated for use on a PHP 7+ platform, 

## Features

The official [SecurePay Australia](http://securepay.com.au)
XML API plugin enables support in Magento for the 
following credit-card transactions:

- Standard Credit, when in Authorize + Capture mode
- Preauth/Advice (Preauthorise + Complete), when in Authorize mode
- Reverse (Void)
- Refund
- FraudGuard (Standard payment)

### Credit Card Support

Provides support for the following kinds of credit-card transactions, 
via the SecurePay gateway:

- Standard payment
- Preauthorize
- Complete
- Void
- Refund
- FraudGuard (Standard)

## Installation

Install using Composer (preferred) or Modman.

Just add to require `"doghouse/securepaysecurexml":"1.*",` in your composer.json.

or

`composer require doghouse/securepaysecurexml:1.*`

## Usage

Go to Magento Admin >> Configuration >> Sales >> Payment Methods

Enter your SecurePay SecureXML credentials, Enable module and Save Config

# License

[Open Software License (OSL)](http://opensource.org/licenses/osl-3.0.php)

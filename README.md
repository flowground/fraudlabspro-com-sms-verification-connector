# ![LOGO](logo.png) FraudLabs Pro SMS Verification **flow**ground Connector

## Description

A generated **flow**ground connector for the FraudLabs Pro SMS Verification API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fraudlabspro.com/sms-verification/1.0/openapi.json<br/>
Generated at: 2019-05-07T17:40:47+03:00

## API Description

Send an SMS with verification code and a custom message for authentication purpose. It helps merchants to minimize chargebacks and fraud for various kinds of payment method, such as credit card, paypal, cod and so on. Please visit https://www.fraudlabspro.com to learn more.

## Authorization

This API does not require authorization.

## Actions

### Verify that an OTP sent by the Send SMS Verification API is valid.

#### Input Parameters
* `tran_id` - _required_
* `key` - _required_
* `format` - _optional_
    Possible values: json, xml.
* `otp` - _required_

### Send an SMS with verification code and a custom message for authentication purpose.

#### Input Parameters
* `country_code` - _optional_
* `format` - _optional_
    Possible values: json, xml.
* `tel` - _required_
* `key` - _required_
* `mesg` - _optional_

## License

**flow**ground :- Telekom iPaaS / fraudlabspro-com-sms-verification-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

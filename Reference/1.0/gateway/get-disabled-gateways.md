<!--
@title Get disabled gateways
@author Moltin Ltd
@description Gets an array of disabled gateways

@sidebar 1
@family Gateway
@rate No
@auth Yes
@format JSON
@http GET
@version beta
-->
Returns all disabled gateways


#### Resource URL
GET [{{ api_url }}gateways/disabled]({{ api_url }}gateways/disabled)


#### Parameters
None required

<!--code-->
#### Example Successful Response
``` json
{
  "status": true,
  "result": [
   {
      "name": "2Checkout",
      "slug": "2checkout",
      "description": null,
      "enabled": false,
      "settings": {
         "accountNumber": "",
         "secretWord": "",
         "testMode": false
      }
   },
   {
      "name": "Alipay Express",
      "slug": "alipay-express",
      "description": null,
      "enabled": false,
      "settings": {
         "partner": "",
         "key": "",
         "signType": "MD5",
         "inputCharset": "utf-8",
         "transport": "http"
      }
   },
   {
      "name": "Alipay Secured",
      "slug": "alipay-secured",
      "description": null,
      "enabled": false,
      "settings": {
         "partner": "",
         "key": "",
         "signType": "MD5",
         "inputCharset": "utf-8",
         "transport": "http"
      }
   },
   {
      "name": "AliPay Dual Func",
      "slug": "alipay-dual",
      "description": null,
      "enabled": false,
      "settings": {
         "partner": "",
         "key": "",
         "signType": "MD5",
         "inputCharset": "utf-8",
         "transport": "http"
      }
   },
   {
      "name": "Alipay Wap Express",
      "slug": "alipay-wapexpress",
      "description": null,
      "enabled": false,
      "settings": {
         "partner": "",
         "key": "",
         "signType": "MD5",
         "inputCharset": "utf-8"
      }
   },
   {
      "name": "Alipay Mobile Express",
      "slug": "alipay-mobileexpress",
      "description": null,
      "enabled": false,
      "settings": {
         "partner": "",
         "key": "",
         "signType": "MD5",
         "inputCharset": "utf-8",
         "transport": "http"
      }
   },
   {
      "name": "Alipay Bank",
      "slug": "alipay-bank",
      "description": null,
      "enabled": false,
      "settings": {
         "partner": "",
         "key": "",
         "signType": "MD5",
         "inputCharset": "utf-8",
         "transport": "http"
      }
   },
   {
      "name": "Authorize.Net AIM",
      "slug": "authorize-net-aim",
      "description": null,
      "enabled": false,
      "settings": {
         "apiLoginId": "",
         "transactionKey": "",
         "testMode": false,
         "developerMode": false
      }
   },
   {
      "name": "Authorize.Net SIM",
      "slug": "authorize-net-sim",
      "description": null,
      "enabled": false,
      "settings": {
         "apiLoginId": "",
         "transactionKey": "",
         "testMode": false,
         "developerMode": false,
         "hashSecret": ""
      }
   },
   {
      "name": "Buckaroo",
      "slug": "buckaroo",
      "description": null,
      "enabled": false,
      "settings": {
         "websiteKey": "",
         "secretKey": "",
         "testMode": false
      }
   },
   {
      "name": "CardSave",
      "slug": "cardsave",
      "description": null,
      "enabled": false,
      "settings": {
         "merchantId": "",
         "password": ""
      }
   },
   {
      "name": "TargetPay Directebanking",
      "slug": "directebanking",
      "description": null,
      "enabled": false,
      "settings": {
         "subAccountId": ""
      }
   },
   {
      "name": "Dummy",
      "slug": "dummy",
      "description": null,
      "enabled": false,
      "settings": [

      ]
   },
   {
      "name": "eWAY Rapid 3.0",
      "slug": "eway",
      "description": null,
      "enabled": false,
      "settings": {
         "apiKey": "",
         "password": "",
         "testMode": false
      }
   },
   {
      "name": "First Data Connect",
      "slug": "firstdata",
      "description": null,
      "enabled": false,
      "settings": {
         "storeId": "",
         "sharedSecret": "",
         "testMode": false
      }
   },
   {
      "name": "GoCardless",
      "slug": "gocardless",
      "description": null,
      "enabled": false,
      "settings": {
         "appId": "",
         "appSecret": "",
         "merchantId": "",
         "accessToken": "",
         "testMode": false
      }
   },
   {
      "name": "TargetPay iDEAL",
      "slug": "ideal",
      "description": null,
      "enabled": false,
      "settings": {
         "subAccountId": ""
      }
   },
   {
      "name": "MIGS 2-Party",
      "slug": "migs-2party",
      "description": null,
      "enabled": false,
      "settings": {
         "merchantId": "",
         "merchantAccessCode": "",
         "secureHash": ""
      }
   },
   {
      "name": "MIGS 3-Party",
      "slug": "migs-3party",
      "description": null,
      "enabled": false,
      "settings": {
         "merchantId": "",
         "merchantAccessCode": "",
         "secureHash": ""
      }
   },
   {
      "name": "Mollie",
      "slug": "mollie",
      "description": null,
      "enabled": false,
      "settings": {
         "partnerId": "",
         "testMode": false
      }
   },
   {
      "name": "TargetPay MrCash",
      "slug": "mrcash",
      "description": null,
      "enabled": false,
      "settings": {
         "subAccountId": ""
      }
   },
   {
      "name": "MultiSafepay",
      "slug": "multi-safepay",
      "description": null,
      "enabled": false,
      "settings": {
         "accountId": "",
         "siteId": "",
         "siteCode": "",
         "testMode": false
      }
   },
   {
      "name": "Netaxept",
      "slug": "netaxept",
      "description": null,
      "enabled": false,
      "settings": {
         "merchantId": "",
         "password": "",
         "testMode": false
      }
   },
   {
      "name": "NetBanx",
      "slug": "netbanx",
      "description": null,
      "enabled": false,
      "settings": {
         "accountNumber": "",
         "storeId": "",
         "storePassword": "",
         "testMode": false
      }
   },
   {
      "name": "PayFast",
      "slug": "payfast",
      "description": null,
      "enabled": false,
      "settings": {
         "merchantId": "",
         "merchantKey": "",
         "pdtKey": "",
         "testMode": false
      }
   },
   {
      "name": "Payflow",
      "slug": "payflow",
      "description": null,
      "enabled": false,
      "settings": {
         "username": "",
         "password": "",
         "vendor": "",
         "partner": "",
         "testMode": false
      }
   },
   {
      "name": "PayPal Express",
      "slug": "paypal-express",
      "description": null,
      "enabled": false,
      "settings": {
         "username": "",
         "password": "",
         "signature": "",
         "testMode": true,
         "solutionType": "Sole",
         "landingPage": "Billing",
         "headerImageUrl": ""
      }
   },
   {
      "name": "PayPal Pro",
      "slug": "paypal-pro",
      "description": null,
      "enabled": false,
      "settings": {
         "username": "",
         "password": "",
         "signature": "",
         "testMode": false
      }
   },
   {
      "name": "Pin",
      "slug": "pin",
      "description": null,
      "enabled": false,
      "settings": {
         "secretKey": "",
         "testMode": false
      }
   },
   {
      "name": "PaymentExpress PxPay",
      "slug": "px-pay",
      "description": null,
      "enabled": false,
      "settings": {
         "username": "",
         "password": ""
      }
   },
   {
      "name": "PaymentExpress PxPost",
      "slug": "px-post",
      "description": null,
      "enabled": false,
      "settings": {
         "username": "",
         "password": ""
      }
   },
   {
      "name": "Sage Pay Direct",
      "slug": "sagepay-direct",
      "description": null,
      "enabled": false,
      "settings": {
         "vendor": "",
         "testMode": false,
         "simulatorMode": false
      }
   },
   {
      "name": "Sage Pay Server",
      "slug": "sagepay-server",
      "description": null,
      "enabled": false,
      "settings": {
         "vendor": "",
         "testMode": false,
         "simulatorMode": false
      }
   },
   {
      "name": "SecurePay Direct Post",
      "slug": "securepay",
      "description": null,
      "enabled": false,
      "settings": {
         "merchantId": "",
         "transactionPassword": "",
         "testMode": false
      }
   },
   {
   {
      "name": "WorldPay",
      "slug": "worldpay",
      "description": null,
      "enabled": false,
      "settings": {
         "installationId": "",
         "secretWord": "",
         "callbackPassword": "",
         "testMode": false
      }
   }
  ]
}

```
<!--/code-->
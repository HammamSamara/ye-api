The new Yamsafer Express API
============================

This new Yamsafer Express API has an all new API. It is not compatible with the old one since some requests will be changed permenantly but we will keep them to keep support for old YE clients. This is a REST-style API that uses JSON for serialization and API key for authentication.


Making a request
================

All URLs start with `https://api.yamsafer.com/api/mobile/deals/`. but we are moving to `https://api.yamsafer.com/api/v1/mobile/deals/` to keep backward compatiblity when upgrading the API then we'll pump the version marker. For testing purposes you will deal with our staging server `https://api-staging.yamsafer.com/api/mobile/deals/` which simulates the live environment.


Authentication
--------------

Currently there is no authentication rules on public requests since the API was only consumed inhouse, but we will reject all requests to the new API that don't carry API key in the request header.

We will provide you with Live and Staging keys when you start consuming the API.


Analytics
---------

YE app uses Google Analytics to track user's actions inside the app so we have better understanding how our users using our product. It also helps us to decide on beta features and what imporvments should we make.

YE app also has Kissmetrics integration.

We will provide you with Live and Staging keys when you start consuming the API.


Push Notifications
------------------

We support Push notifications in YE app. We are working with [Push Woosh](https://www.pushwoosh.com) to make that happens.

We will provide you with GCM and APN keys and certificates for pushwoosh integration when you start consuming the API.


Handling errors
---------------

If YE is having trouble, you might see a 5xx error. It's your responsibility to retry your request later. Call us when YE is having issues while you are still in development stage.


API ready for use
-----------------

* [Deals](https://github.com/HammamSamara/ye-api/blob/master/sections/deals.md)
* [Cities](https://github.com/HammamSamara/ye-api/blob/master/sections/cities.md)
* [Hotel Info](https://github.com/HammamSamara/ye-api/blob/master/sections/hotel.md)
* [Checkout](https://github.com/HammamSamara/ye-api/blob/master/sections/checkout.md)
* [Register Users](https://github.com/HammamSamara/ye-api/blob/master/sections/users.md)


Help us make it better
----------------------

Please tell us how we can make the API better. Report any bug if you found any.

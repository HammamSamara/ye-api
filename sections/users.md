Users
=====

Users are required to verify their phone numbers before be able to book rooms.
Registeration process should be taken place for the first time the user is booking a room, then user info cached localy should be used for next bookings.

Registration users and sending confirmation are being serves on a different server running `ROR`. So the base URL will be `http://sms-dev.yamsafer.me/api/subscriptions/`.

You should send `auth_token` with all your requests.


Register new user
-----------------

* `POST /create` will create new subscription.

`country_code` user's country code.
`phone_number` user's phone number.


Verify confirmation code
------------------------

* `POST /verify` will verify subscription code.

`country_code` user's country code.
`phone_number` user's phone number.
`code` user's subscription code.


Resend confirmation code
------------------------

* `POST /resend` will resend subscription code.

`country_code` user's country code.
`phone_number` user's phone number.


TODO
------------------------
* Add response samples.
Checkout
========

This API will accept hotel and rooms details with users info, and returns a transaction status.


User Checkout
-------------

* `GET /checkout` will register user's checkout.

`GET` action will deprecated, and a `POST` action will take place instead.

`hotel_id` for hote id.
`hotel_name` for hotel name.
`room_id` for room id.
`name` for user name.
`email` for user email.
`from_date` for checkin date.
`to_date` for checkout date.
`price` we attached the room rate with the request for extra validation.
`phone_number` user phone number.

Response smaple:

```json
{
  success: true
}
```
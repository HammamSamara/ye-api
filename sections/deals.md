Deals
=====


Get Deals
---------

* `GET /index` will return all one night deals for today.
* `GET /index?isPalestine=true&nights=1&date=0` will return all one night deals for today.

`isPalestine` param presents if the palestiniens cities should be displayed for the user or not (for political reasons). If `false`, palestiniens cities will be not included in the response. YE client used to decide on this based on user's IP, we are considering to move this to the backend though.

`nights` param for how many night the user is looking for.

`date` param is deciding the deals date. a value of `0` is for today, `1` is for tomorrow, `-1` for yesterday and so on.

```json
{
  cities: {
    180543: {
      hotels: [
        {
          id: "12",
          hotel_id: "7928",
          hotel_name: "منتجع جولدن توليب خليج الدانة",
          city_id: "180543",
          stars: "4",
          cover_image: "/app/yamsafer/images/system/tmp/medium_Sala1A.jpg",
          primary_image: "/app/yamsafer/images/system/tmp/medium_RENOVATE-1.jpg",
          secondary_image: "/app/yamsafer/images/system/tmp/medium_9edited(1).jpg",
          latitude: "26.267143080777",
          longtitude: "50.21584510803223",
          availability: "3",
          low_rate: "40.80000",
          original_low_rate: "0.00000",
          priority: "1",
          is_default: "0",
          created_at: "2014-07-17 15:16:28",
          updated_at: "2014-08-24 12:13:20",
          promotion_rate: 236.7408,
          base_rate: 236.7408,
          has_promotion: false,
          pivot: {
            date_id: "61",
            deal_id: "12"
          }
        },
        {
          id: "12",
          hotel_id: "7928",
          hotel_name: "منتجع جولدن توليب خليج الدانة",
          city_id: "180543",
          stars: "4",
          cover_image: "/app/yamsafer/images/system/tmp/medium_Sala1A.jpg",
          primary_image: "/app/yamsafer/images/system/tmp/medium_RENOVATE-1.jpg",
          secondary_image: "/app/yamsafer/images/system/tmp/medium_9edited(1).jpg",
          latitude: "26.267143080777",
          longtitude: "50.21584510803223",
          availability: "3",
          low_rate: "40.80000",
          original_low_rate: "0.00000",
          priority: "1",
          is_default: "0",
          created_at: "2014-07-17 15:16:28",
          updated_at: "2014-08-24 12:13:20",
          promotion_rate: 236.7408,
          base_rate: 236.7408,
          has_promotion: false,
          pivot: {
            date_id: "61",
            deal_id: "12"
          }
        }
      ]
    }
  }
}
```

All rates are in USD.

# Accommodation Booking Cancelled

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "return",
  "apollo_event": "Accommodation Booking Cancelled",
    "booking_cancellation_id": "<booking_cancellation_id>",
    "booking_reservation_id": "<booking_reservation_id>",
    "ecommerce": {
        "coupon": "<coupon>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "currency": "<currency>",
                "index": "<index>",
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "transaction_id": "<transaction_id>",
        "value": "<value>"
    },
    "lodging_location_id": "<lodging_location_id>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|booking_cancellation_id|string|Captures the number of adults associated with a lodging room booking.|CN-34456789|||||||
|booking_reservation_id|string|Captures the reservation ID associated with each booking.||^[a-zA-Z0-9]{6,20}$|6|20||||
|coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|lodging_location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||

## Attached Notes

<p>111</p>

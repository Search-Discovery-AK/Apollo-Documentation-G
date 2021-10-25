# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "page_load",
  "apollo_event": "Page Load Started",
    "country": "<country>",
    "language": "<language>",
    "page_location": "<page_location>",
    "page_name": "<page_name>",
    "site_country": "<site_country>",
    "site_language": "<site_language>",
    "site_name": "<site_name>",
    "site_type": "<site_type>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|country|string|The country the site is associated with.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_location|string|The url of the page currently being viewed.||||||||
|page_name|string|Amount of money discounted for the entire order.|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|site_country|string|Captures the country associated with website or mobile app activity.|US, CA, FR, UK|^[A-Z]{2}$||||||
|site_language|string|Captures the language associated with website or mobile app activity.|en-us, en-gb, ch-cn, fr-ca, fr-fr, da|^[a-z]{2}([-]{1}[a-z]{2}){0,1}$||||||
|site_name|string|Captures the business unit associated with each product.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|site_type|string|Amount of money associated with markdown prices for products reached the order confirmation step of the shopping cart.|Prospecting, Shop, Members, Brand|||||||





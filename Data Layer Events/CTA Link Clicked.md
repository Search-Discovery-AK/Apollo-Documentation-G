# CTA Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "select_content",
  "apollo_event": "CTA Link Clicked",
    "cta_link_click_event": "<cta_link_click_event>",
    "cta_link_container": "<cta_link_container>",
    "cta_link_id": "<cta_link_id>",
    "cta_link_region": "<cta_link_region>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|cta_link_click_event|string|Count of revenue taking place offline from internal databases for use in comparing to online revenue.||||||||
|cta_link_container|string|Total monetary amount associated witheach night of a room booking.|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|cta_link_id|string|Count of times that visitors began the room booking process.|act now, cancel, ok, 3456, 8765|||||||
|cta_link_region|string|Count of units taking place offline from internal databases for use in comparing to online units.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||





# Interstitial Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "interstitial_viewed",
  "apollo_event": "Interstitial Viewed",
    "interstitial_view_type": "<interstitial_view_type>",
    "interstitial_views": "<interstitial_views>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|interstitial_view_type|string|Count of times that visitors canceled website forms.|alert, offer, info required|||||||
|interstitial_views|unknown|Captures the last form field ID the user interacted with prior to abandoning a form.||||||||





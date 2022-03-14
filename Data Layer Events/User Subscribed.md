# User Subscribed

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "User Subscribed",
    "subscription": {
        "subscribeMethod": "<subscribeMethod>",
        "subscriptionType": "<subscriptionType>"
    },
    "user": {
        "profileAttributesList": "<profileAttributesList>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|subscription.subscribeMethod|string|Describes the method used to subscribe. |footer field, registration opt in, order placed, notification preferences|||||||
|subscription.subscriptionType|string|Describes the type of subscription. |news, updates, sales, events|||||||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||





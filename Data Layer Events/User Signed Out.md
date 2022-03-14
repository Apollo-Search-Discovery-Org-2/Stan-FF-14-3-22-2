# User Signed Out

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "User Signed Out",
    "user": {
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "profileAttributesList": "<profileAttributesList>",
        "system": "<system>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user.system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||





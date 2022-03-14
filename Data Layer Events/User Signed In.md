# User Signed In

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "User Signed In",
    "user": {
        "country": "<country>",
        "custKey": "<custKey>",
        "hasPersistedCart": <hasPersistedCart>,
        "loginStatus": "<loginStatus>",
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "loyaltyPoints": <loyaltyPoints>,
        "organizationID": "<organizationID>",
        "persistedCartValue": "<persistedCartValue>",
        "persistedLogin": <persistedLogin>,
        "profileAttributesList": "<profileAttributesList>",
        "registrationStatus": "<registrationStatus>",
        "system": "<system>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.country|string|The country associated with this user's profile.|USA, Canada|||||||
|user.custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|user.hasPersistedCart|boolean|Indicator of the user has a persisted shopping cart|TRUE, FALSE|||||||
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.loyalty.memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|user.loyalty.memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|user.loyaltyPoints|integer|Number of loyalty points |100, 101, 1000||||0|||
|user.organizationID|string|Customer Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|user.persistedCartValue|string|The total value of all items in the persisted cart|125.05, 432.21, 90.22, 12.05|^[0-9]*(\.[0-9]{1,2})?$||||||
|user.persistedLogin|integer|Count of times users selected the option to persist their login \(i.e.,"keep me logged in"\) when signing in.||||||||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user.registrationStatus|string|Describes the registration state of the user \(independent of sign-in state\)|registered|||||||
|user.system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||





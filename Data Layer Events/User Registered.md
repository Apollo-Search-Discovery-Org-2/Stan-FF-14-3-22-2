# User Registered

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "User Registered",
    "user": {
        "country": "<country>",
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "loyalty": {
            "isLoyaltyRegistration": <isLoyaltyRegistration>
        },
        "profileAttributesList": "<profileAttributesList>",
        "registrationStatus": "<registrationStatus>",
        "registrationType": "<registrationType>",
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
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.loyalty.isLoyaltyRegistration|integer|User regsitered for a new Loyalty account.||||||||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user.registrationStatus|string|Describes the registration state of the user \(independent of sign-in state\)|registered|||||||
|user.registrationType|string|Describes the thing that was registered for |account, loyalty program, event, sweepstakes, warranty|||||||
|user.system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||





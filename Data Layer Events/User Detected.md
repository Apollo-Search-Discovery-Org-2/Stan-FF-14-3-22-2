# User Detected

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "User Detected",
    "user": {
        "affiliateCustomerID": "<affiliateCustomerID>",
        "anonymousUserID": "<anonymousUserID>",
        "country": "<country>",
        "custKey": "<custKey>",
        "customerDetails": {
            "SUID": "<SUID>"
        },
        "loginStatus": "<loginStatus>",
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "organizationID": "<organizationID>",
        "profileAttributesList": "<profileAttributesList>",
        "registrationStatus": "<registrationStatus>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.affiliateCustomerID|string|The user ID of user who arrived at the website via a third party partner.||||||||
|user.anonymousUserID|string|When a user is not logged in,, this captures an anonymous user id.||||||||
|user.country|string|The country associated with this user's profile.|USA, Canada|||||||
|user.custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|user.customerDetails.SUID|string|Captures the user ID based on a cookie.||||||||
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.loyalty.memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|user.loyalty.memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|user.organizationID|string|Customer Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user.registrationStatus|string|Describes the registration state of the user \(independent of sign-in state\)|registered|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||

## Attached Notes

<p>11111</p>

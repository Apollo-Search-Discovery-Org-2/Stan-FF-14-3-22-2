# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "Page Load Started",
    "page": {
        "siteExperience": "<siteExperience>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page.siteExperience|string|Describes the version of the site that is being shown|Responsive, Mobile, Desktop|||||||





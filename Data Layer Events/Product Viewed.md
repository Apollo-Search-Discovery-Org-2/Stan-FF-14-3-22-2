# Product Viewed

### 

## Javascript Code
```js
window.appEventData00000 = window.appEventData00000 || [];
appEventData00000.push({
  "event": "Product Viewed",
    "product": [
        {
            "fulfillment": {
                "isBopusOnly": <isBopusOnly>
            },
            "isThirdPartyProduct": <isThirdPartyProduct>,
            "price": {
                "priceTier": "<priceTier>",
                "priceType": "<priceType>",
                "sellingPrice": "<sellingPrice>"
            },
            "productInfo": {
                "brand": "<brand>",
                "businessUnit": "<businessUnit>",
                "color": "<color>",
                "discountAmount": "<discountAmount>",
                "fulfillmentOptions": "<fulfillmentOptions>",
                "isFeatured": <isFeatured>,
                "isOutOfStock": <isOutOfStock>,
                "isSKuAvailable": <isSKuAvailable>,
                "name": "<name>",
                "productID": "<productID>",
                "productLine": "<productLine>",
                "quantityAvailable": "<quantityAvailable>",
                "ratingAverage": "<ratingAverage>",
                "ratingCount": <ratingCount>,
                "ratingCountAndAverageCombined": "<ratingCountAndAverageCombined>",
                "sku": "<sku>",
                "status": "<status>",
                "thirdyPartyVendorID": "<thirdyPartyVendorID>",
                "trademarkedTechnology": "<trademarkedTechnology>",
                "webExclusive": <webExclusive>
            }
        }
    ],
    "productInfo": {
        "isBestSeller": <isBestSeller>,
        "isTopRated": <isTopRated>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|productInfo.isBestSeller|integer|Count of times the product was a best seller product.||||||||
|productInfo.isTopRated|integer|Count of times the product was a top rated product.||||||||
|product[n].fulfillment.isBopusOnly|integer|Count of times the user engaged with a product whose only available shipping method was Buy Online Pick Up In Store \(i.e., BOPUS\).||||||||
|product[n].isThirdPartyProduct|integer|Count of times a user viewed a product page for a third party \(e.g., marketplace vendor\) product.||||||||
|product[n].price.priceTier|string|Describes the general pricing tier of a product. \(Good, Better, Best\)|Good, Better, Best, Bronze, Silver, Gold|||||||
|product[n].price.priceType|string|Describes the type of price offered using commonly used terms. |1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|product[n].price.sellingPrice|string|String representation of the price paid after coupons or discounts. Positive. Up to two decimal places for cents. No currency symbol.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|product[n].productInfo.brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|product[n].productInfo.businessUnit|string|The business unit associated with each product.|Apparel, Shoes, Home|||||||
|product[n].productInfo.color|string|Describes the colorway of a product or product variant|Antique Oak, Granite, Black Marble, Knotty Pine|||||||
|product[n].productInfo.discountAmount|string|The product discount amount shown to the visitor for each product.|$20, 10%, $5|||||||
|product[n].productInfo.fulfillmentOptions|string|The product fulfillment options available for each product to view impact on conversion.|Shipped Only, In Store Only, Local Pickup Only, In Store or Ship, Digital \(Email or Text\)|||||||
|product[n].productInfo.isFeatured|integer|Count of times the product was a featured\/boosted product.||||||||
|product[n].productInfo.isOutOfStock|boolean|Boolean flag indicating that an inventoried product is out of stock. |TRUE, FALSE|||||||
|product[n].productInfo.isSKuAvailable|boolean|True\/False flag to indicate if product SKU is known at the time of the event|true, false|||||||
|product[n].productInfo.productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
|product[n].productInfo.productLine|string|Describes the product Line of a product. |Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||
|product[n].productInfo.quantityAvailable|string|The product quantity available.|1, 10, 100|||||||
|product[n].productInfo.ratingAverage|string|String representation of the average customer rating.  Positive. Up to two decimal places. This is most often a number between 0 and 5. |1.1, 2, 5|^[0-9]*(\.[0-9]{1,2})?$||||||
|product[n].productInfo.ratingCount|integer|Integer number of customer ratings. |1, 5, 11, 200||||0|||
|product[n].productInfo.ratingCountAndAverageCombined|string|Combined Rating Count and Rating Average with colon as delimiter|23:4.5, 222:1.7, 1:5, 2:3.5|||||||
|product[n].productInfo.sku|string|Stock Keeping Unit \(SKU\) Unique Identifier of specific item \(typically\) held in inventory.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level below productID for products with SKU variants. |34567890, 4567890, 00155-large-cornflower|||||||
|product[n].productInfo.status|string|Described the product's status|In Stock, Out of Stcok, Back-Ordered|||||||
|product[n].productInfo.thirdyPartyVendorID|string|Captures the vendor id of the third party vendor associated with product conversion.||||||||
|product[n].productInfo.trademarkedTechnology|string|Describes trademarks and\/or technical branding used to describe the product|Stainmaster, GoreTex, WeatherShield|||||||
|product[n].productInfo.webExclusive|boolean|Captures whether or not the product is sold on website\/app only.||||||||

## Attached Notes

<p>11111</p>

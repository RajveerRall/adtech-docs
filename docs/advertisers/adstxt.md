
***
> **Note:** This section is under construction. Please check back soon for updates.
***

Publishers place an ads.txt file on the root directory of their website. This file acts as a public record, essentially declaring which digital sellers are authorized to resell their ad inventory. Ad exchanges, DSPs (Demand-Side Platforms), and other programmatic buyers can access and verify the information in the ads.txt file. This transparency helps ensure they're purchasing ad impressions from legitimate sources authorized by the publisher. By listing authorized sellers, publishers can help prevent unauthorized parties from fraudulently selling their ad inventory. This mitigates issues like domain spoofing, where bad actors attempt to sell ad space they don't own.

You have to add entries in your domain/sites inside app-ads.txt or ads.txt. This is a transparent way to validate the sellers and buyers in the supply chain. Without these entries Bid request will be invalid.

![img.png](assets/adstxt.png)

Here's an example of an entry: demomedia.com, 50621, DIRECT.

- **demomedia.com:** This identifies the seller's domain.  In this example, it means a company called "demomedia.com" is authorized to sell ad space on the publisher's website.

- **50621**:  This represents the seller's unique account ID within the ad exchange or platform they use. This ID allows for precise identification of the seller.

- **DIRECT**:  This indicates the type of relationship between the publisher and the seller. "DIRECT" signifies that the publisher has a direct sales arrangement with this specific seller. Another possible value is "RESELLER".
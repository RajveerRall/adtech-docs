The main goal of IVT reports is to help you track and analyze impressions, clicks, and potentially other actions that have been flagged as suspicious or fraudulent due to the presence of invalid traffic (IVT). This includes things like bot traffic, click farms, hidden ads, and other forms of non-human activity that undermine the integrity of your ad ecosystem.

### Use Cases

* **Investigating Suspicious Activity**:  When you notice unexplained spikes in impressions, low CTRs (click-through rates), or other red flags, IVT reports help you pinpoint the source. You can see if invalid traffic is isolated to a specific publisher, advertiser, campaign, or website.
* **Protecting Revenue**:  Invalid traffic artificially inflates metrics, dilutes the value of legitimate ad impressions,  and can negatively impact both publisher and advertiser earnings. IVT reports help you mitigate potential losses.
* **Taking Action**:  Armed with the insights from IVT reports, you can take steps like blocking specific endpoints, adjusting campaign targeting, working with advertisers or publishers to address potential issues, or implementing more robust fraud detection measures.

## Key Parameters Explained

* **PUB ID / ADV ID**: Unique identifiers for publishers (SSP side) and advertisers (DSP side).
* **PUB EPID/ ADV EPID:** Unique identifiers for the specific endpoints associated with a publisher or advertiser.
* **GROUP BY**: Allows you to organize the report data by various criteria, making it easier to spot patterns.
* **DATA:** Standard performance metrics, although in this case they represent invalid activity: Impressions, Clicks, Revenue (Note: revenue here likely refers to revenue that would have been generated if the traffic was valid.) Cost (the estimated cost associated with the invalid traffic).
* **DATE RANGE**: Lets you filter data to focus on specific time periods.

## Additional Parameters

* IS DIRECT: Indicates if the invalid traffic occurred in a direct campaign deal or within real-time bidding.
* DOMAIN: Shows the websites or apps where fraudulent activity was detected.
* TYPE: Likely refers to the type of ad format (banner, video, etc.).
* AD SIZES: The dimensions of the ads.

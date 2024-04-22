This feature provides admins with fine-grained control over where an advertiser's ads can appear. It empowers you to define specific websites, apps, and ad formats (endpoints) that align with an advertiser's campaign goals and targeting.

* Precision Targeting: Ensure an advertiser's ads only display on the most relevant and suitable websites, apps, and within specific ad placements.
* Brand Safety: Protect an advertiser's reputation by proactively excluding endpoints with undesirable content or those that don't fit their brand values.
* Budget Optimization: Focus ad spend on endpoints that have historically performed well for an advertiser, avoiding wasted impressions on unsuitable placements.

### Explain Key Parameters

* ADV ID: Unique identifier for the advertiser.
* ADV EPID: Unique identifier for a specific endpoint created for the advertiser.
* TYPE: The format and platform of the ad placement (APP_ANDROID_BANNER, SITE_VIDEO, etc.).
* AD SIZE: The dimensions of the ad creative (300x50, 320x100, etc.).
* END POINT URL: The specific website address or app identifier where the ad will display.
* AUCTION / PRICING Details (AT, IS PMP, DEAL ID, etc.): Technical settings determining how those ad placements will be bought and sold.
* USER / IP FCAP: Frequency capping controls.
* BID MARGIN: Possible additional markup/margin the platform might take.
* GZIP: Potential setting related to compression to reduce ad load times.
* STATUS: Controls whether the endpoint is ACTIVE, PENDING approval, or BLOCKED.
* ACTION: Likely dictates whether the endpoint is included in current ad requests (RUNNING) or paused (STOPPED).

### Admin Workflow

Campaign Setup: During an advertiser's campaign creation, the admin collaborates to define the desired target environments (types of apps, websites).
Endpoint Creation: The admin creates specific endpoints tailored to the advertiser, including websites, apps, and compatible ad formats.
Technical Setup: The admin configures the endpoint details (pricing models, bidding parameters, any special instructions via TAG ID).
Monitoring & Optimization: The admin tracks the performance of each endpoint, potentially disabling poorly performing ones and adjusting settings to improve campaign results.

### Use Cases

* Niche Advertiser: Create highly targeted endpoints for an advertiser promoting a hiking app, focusing on outdoor blogs, fitness apps, and relevant websites.
* Competitor Avoidance: Explicitly block an advertiser's endpoints from appearing on their competitor's websites or apps.
* Performance-based Refinement: Pause endpoints that consistently have low click-through rates or poor conversion performance.
* Troubleshooting: If an advertiser's campaign unexpectedly has no impressions, investigate endpoint status and settings.

---
This feature gives admins fine-grained control over the specific websites and apps ("endpoints") where a publisher's ad inventory can be displayed through your platform. This includes the ability to verify a publisher's endpoints, as well as directly create or edit them as needed.

* Inventory Control: Ensures publishers' ads only appear on approved websites or within approved apps. This is critical for upholding quality standards, adhering to a publisher's preferences, and for brand safety reasons.
* Transparency: Provides a centralized view to see what kind of ad placements a publisher offers (e.g., banner, video) and understand technical setup details.
* Customization: Allows for tailored settings on a per-publisher and per-endpoint basis, such as specific countries where their placements can appear or pricing/auction customizations.

### Key Parameters Explained

* PUB ID: Unique identifier for the publisher.
* PUB EPID: A unique identifier for each specific endpoint offered by the publisher.
* TYPE: The format and platform of the ad placement:
  * APP_ANDROID_(Banner, Video, Native, etc. for Android apps)
  * APP_IOS_(Banner, Video, etc. for iOS apps)
  * SITE_(For website placements)
  * CTV_(Connected TV placements)
* END POINT URL: The specific web address or app identifier where the ad will be displayed.
* STATUS: Controls whether the endpoint is ACTIVE, PENDING approval, or BLOCKED.
* ACTION: Likely controls if the endpoint is included in ad requests (RUNNING) or excluded (STOPPED).
* AUCTION / PRICING Details (AT, IS PMP, DEAL ID, etc.): Technical settings determining how those ad placements will be bought and sold.
* USER / IP FCAP: Frequency capping controls to limit how often ads are shown to a single user or IP address.
* MAX, THROTTLE, COUNTRY ALLOWED: Additional controls to refine targeting or manage ad delivery.

### Admin Workflow

* Publisher Onboarding: During the setup process, a publisher would submit their available endpoints (websites and apps where they want to display ads).
* Admin Verification: Admins carefully review each endpoint, verifying it aligns with platform standards and any publisher-specific agreements.
* Endpoint Creation (If Needed): Admins might directly create endpoints for a publisher, especially for specific deal types or unique customizations.
* Ongoing Management: Admins can edit settings, enable/disable endpoints, or change pricing models as required.

### Use Cases

* Brand Safety: Block a publisher's endpoint if it's discovered to be a website with objectionable content.
* Customization: Create special endpoints tied to specific deals negotiated with a high-profile publisher.
* Traffic Management: Use throttling controls on an endpoint if a specific website or app is receiving far more impressions than desired.
* Troubleshooting: If a publisher's ads aren't appearing as expected, the admin can check the endpoint status and settings for any issues.
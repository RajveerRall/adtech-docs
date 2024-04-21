The primary function of this feature is to give admins or POCs direct control over the apps and websites (domains) approved for publishers to display ads on. Whitelisting is a crucial mechanism for ensuring ad quality, brand safety, and the overall integrity of your ad ecosystem.

### Use Cases:

* Quality Control: Prevent ads from appearing on apps or sites with objectionable content, low traffic, or a history of fraudulent activity. Establish a baseline standard for your network.
* Brand Safety: Protect advertisers by ensuring their ads are only displayed on apps or websites that align with their brand values and target audience.
* Compliance: Adhere to industry regulations and best practices regarding content suitability by allowing admins to proactively curate whitelists.
* Targeted Ad Delivery: Align specific publishers and advertisers by whitelisting compatible apps or websites, potentially optimizing campaign performance.

### Key Parameters Explained

* PUB ID / EPID: Identifiers that associate the whitelisted app/domain with a specific publisher and their endpoint.
* APPID: Unique ID for the mobile app (if applicable).
* DOMAIN / APP BUNDLE ID: Either the website domain or the app's identifying bundle ID (e.g., com.domain.appname).
* URL / STORE URL: The full website address or the app's page on an app store (Google Play, Apple App Store, etc.).
* APP/SITE NAME: Descriptive name for easy identification.
* PRIMARY / SECONDARY CATEGORY: Detailed content classification based on IAB (Interactive Advertising Bureau) taxonomy, which helps refine targeting and filtering.
* STATUS: Controls whether the whitelisted app/domain is ACTIVE, PENDING for review, or BLOCKED.
* ACTION: Additional control, likely to 'stop' the serving of ads on the whitelisted entity (while still maintaining it on the whitelist).

### Admin Panel Whitelist Feature Workflow

* Publisher Submits Whitelist: Publishers suggest new apps/domains where they'd like to display ads.
* Admin Verification: Admins carefully review each submission, checking the URL, content categories, and potentially other factors.
* Approval or Rejection: Based on the review, an admin approves (ACTIVE), sets to PENDING for further investigation, or BLOCKS the app/domain.
* Targeting: The whitelisting system integrates with ad serving logic to ensure ads are only displayed on approved domains from the whitelist.

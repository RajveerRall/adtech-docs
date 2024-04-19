
***
> **Note:** This section is under construction. Please check back soon for updates.
***

Whitelisting allows you to exert granular control over the ad requests you receive for your ad placements (endpoints). By creating a whitelist, you approve specific domains (websites) or app bundle IDs (mobile applications) as authorized to send bid requests for your inventory. 
Additionally, you can often IAB content categories to further refine targeting and ensure the content aligns with your preferences.

![](assets/appsdomain.gif)

## Whitelist any app bundle or site domain

To Whitelist End points, you have to configure the below parameters:

- **EPID**: Each endpoint in your SSP has a unique Endpoint ID. These are used internally to manage the ad spaces.

- **"Want to whitelist?**: SINGLE / MULTIPLE": This allows you to whitelist either:
SINGLE: One specific domain or app bundle.
MULTIPLE: A list of domains or app bundles.

- **DOMAIN / APP BUNDLE ID**: The actual domain (e.g., www.example.com) or app bundle ID of the advertiser's property you want to whitelist.

- **URL / STORE URL**: Depending on if it's a website or app, you'll provide a web address or a link to the application on the app store.

- **APP/SITE NAME**: A descriptive name, making it easier to manage your whitelist.

- **PRIMARY CATEGORY/SECONDARY CATEGORY**: You'll select IAB content categories to help with targeting and to ensure the content aligns with your preferences.


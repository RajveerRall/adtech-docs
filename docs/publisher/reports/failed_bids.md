Failed Bid Reports are diagnostic tools that shed light on why your ad inventory didn't get sold for certain ad requests. Essentially, they highlight the auctions you didn't win. This is tremendously valuable for troubleshooting and optimization.

## Parameters Explained

Selec the End points and parameters you wish to see in the generated report.

Hourly Similar to monetization reports, this indicates a high level of granularity in the data.
EPID Filter failed bids down to a specific endpoint (ad placement) for focused analysis.
GROUP BY
EPID Analyze failure patterns across each of your endpoints individually.
DATE Track how bidding failures fluctuate over time.
FAILED REASON This is the most crucial one – it categorizes why your bids weren't successful.
DATA
REQUEST The number of ad requests your SSP received but failed to sell.
DATE RANGE Standard date picker for historical analysis (note the 2-day limit for hourly).
Typical FAILED REASONs

No Bid: No advertisers were interested in your ad slot.
Floor Price Not Met: Your minimum bid (floor price) wasn't met by any bidders.
Targeting Mismatch: The targeting criteria for the endpoint were too restrictive, eliminating potential advertisers.
Timeout: The bidding process took too long, and some advertisers may have dropped out.
Creative Issues: The ad creative may have been rejected due to quality concerns or policy violations.
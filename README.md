# Twitter (X) Followers Scraper API Alternative

Looking for a fast and scalable **Twitter follower scraper** for growth, lead generation, and audience research?

This project points to our production Apify actor:

## [Open Twitter (X) Follower Scraper on Apify](https://console.apify.com/actors/bIYXeMcKISYGnHhBG/source)

If you need to **scrape Twitter followers**, **scrape Twitter following**, and export clean datasets with usernames or user IDs, this is built for that workflow.

## What this Twitter/X scraper does

- Scrapes **followers** from Twitter/X accounts
- Scrapes **following** (friends) from Twitter/X accounts
- Accepts input as:
  - usernames
  - numeric user IDs
- Returns output as:
  - usernames
  - user IDs
- Streams results progressively during the run

## Pricing

- **$0.10 per 1,000 results**
- Plus standard Apify platform usage charges

## Limits

- Up to **5,000,000** results per request (plan-dependent)
- Free-plan users may have lower caps in actor logic

## Why teams use this actor

- High-volume scraping for large audience datasets
- Cost-efficient pricing compared to many alternatives
- No user-side cookie setup required
- No external API key required from the end user
- Suitable for agency and B2B data workflows

## Best use cases

### 1. Audience intelligence
Analyze competitor followers and following networks to understand account positioning and adjacent audiences.

### 2. Lead generation enrichment
Build Twitter/X lead lists and enrich existing contact pipelines with social graph data.

### 3. Creator and influencer research
Discover real audience overlap and map communities around target profiles.

### 4. Market and niche mapping
Identify active clusters by collecting relationships around key accounts in a niche.

## How to use

1. Open the actor page:
   - [Twitter (X) Follower Scraper on Apify](https://console.apify.com/actors/bIYXeMcKISYGnHhBG/source)
2. Add usernames and/or user IDs
3. Choose followers, following, or both
4. Choose output format (usernames or IDs)
5. Run and export dataset

## Input schema (quick reference)

| Field | Type | Description | Example |
|---|---|---|---|
| `userNameList` | `string[]` | Twitter/X usernames (without `@`) | `["elonmusk","nasa"]` |
| `userIdList` | `string[]` | Numeric Twitter/X user IDs (optional) | `["44196397"]` |
| `maxFollowers` | `number` | Max followers to collect per target | `10000` |
| `maxFollowing` | `number` | Max following to collect per target | `10000` |
| `getFollowers` | `boolean` | Enable followers collection | `true` |
| `getFollowing` | `boolean` | Enable following collection | `true` |
| `outputMode` | `string` | Output format: `usernames` or `ids` | `"ids"` |

### Example input JSON

```json
{
  "userNameList": ["elonmusk", "nasa"],
  "userIdList": [],
  "maxFollowers": 10000,
  "maxFollowing": 10000,
  "getFollowers": true,
  "getFollowing": true,
  "outputMode": "ids"
}
```

## Related actor (email extraction)

If you also need email discovery from Twitter/X profiles, use:

- [Twitter (X.com) Email Scraper](https://console.apify.com/actors/mSaHt2tt3Z7Fcwf0o/source)

## FAQ

### Is this a Twitter API alternative?
Yes. For many scraping workflows, it can be used as a practical alternative when you need follower/following datasets.

### Can I scrape both followers and following in one run?
Yes.

### Can I output only user IDs?
Yes, you can choose output format.

### Is login required from the user side?
No manual login flow is required in the actor input.

### Can I run large jobs like 100K+?
Yes. The actor supports high-volume runs and is designed for large datasets.

## SEO keywords

twitter follower scraper, twitter followers scraper, x follower scraper, x.com followers scraper, scrape twitter followers, scrape twitter following, twitter audience scraper, twitter lead generation scraper, twitter usernames scraper, twitter user ids scraper, twitter api alternative, social graph scraper

---

## Start here

### [Run the actor now on Apify](https://console.apify.com/actors/bIYXeMcKISYGnHhBG/source)

# 9proxy vs decodo: Per-IP Unlimited Bandwidth or a 115M-IP Pool — How to Pick Without Overpaying

Most people comparing these two arrive with the same problem: a proxy bill that doesn't match how they actually use proxies. One provider charges you for gigabytes you burn through and then charges you again. The other charges for IPs and lets you pump unlimited traffic through them. The pricing models are different enough that "which is cheaper" has no single answer, and the wrong pick can cost you several times more than the right one.

So let's do the comparison properly. 9Proxy and Decodo are structurally different businesses, and the numbers below come from what both companies currently publish plus third-party testing where it exists.

## The two providers, in one paragraph each

9Proxy is a residential-only provider. It sells IPs, mostly on a prepaid balance model, with unlimited bandwidth attached to each IP it allocates. The network is advertised at 20M+ residential IPs across 90+ countries, with HTTP/HTTPS and SOCKS5 support, and geo-targeting down to country, state, city, ZIP and ISP level. There's no datacenter, ISP or mobile product line — the focus is residential plus a set of management tools (a desktop app, auto-refresh, auto-rotation, port configuration, a browser-based proxy utility).

Decodo is the company formerly known as Smartproxy, rebranded in 2025. It's a full-stack provider: rotating residential, static residential (ISP), mobile, datacenter, plus scraping and SERP APIs. Decodo advertises 115M+ residential IPs across 195+ locations, with country, state, city, ZIP and ASN targeting included at no extra cost.

That difference in scope matters more than the brand names. One is a budget residential specialist. The other is a general-purpose data-collection platform that happens to sell residential proxies.

## The billing model is 90% of the decision

This is where the two diverge, and where most budget spreadsheets go wrong.

**9Proxy charges per IP. Bandwidth on those IPs is not metered.** A 100-IP package costs $24 and you can push as much traffic through those 100 IPs as the targets will accept. The tradeoff: an IP-based package gives you a fixed number of addresses with a limited lifespan (typically a few hours, up to roughly 24), not unlimited access to the whole pool.

**Decodo charges per gigabyte.** Residential starts at $11.25 for 3 GB ($3.75/GB) and the published rate drops as you commit more: $275 for 100 GB works out to $2.75/GB. Pay-as-you-go is $4.00/GB with no monthly commitment.

Run the arithmetic on a realistic job. If your scraper pulls 500 GB a month through a few hundred stable IPs, 9Proxy's 500-IP package at $72 is a rounding error next to Decodo's 250 GB tier at $625. Flip the scenario: if you need requests to fan out across hundreds of thousands of distinct addresses in 195 locations with tiny per-request payloads, Decodo's per-GB model is the one that won't bankrupt you, because you're paying for the data, not for addresses you'd have to keep replenishing.

The honest summary: **9Proxy is cheaper for chatty, IP-stable workloads. Decodo is better when pool breadth matters more than per-IP cost.**

## 9Proxy pricing: every package currently listed

9Proxy raised prices on IP-based and bundle packages for the first time in its history on June 1, 2026. GB-based packages were left unchanged. IP-based purchases are balance-based rather than a monthly subscription, and according to the company's own announcement, purchased IPs don't expire.

### IP-based packages (unlimited bandwidth per IP)

| Package | Effective price per IP | Total | Purchase |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | [Start with the 100-IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $0.144 | $72 | [Get the 500-IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus IPs | $0.084 | $126 | [Grab the 1,000 + 500 bonus IP package](https://bit.ly/9-Proxy) |
| 2,500 IPs | $0.084 | $210 | [Buy the 2,500-IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | $0.072 | $360 | [Buy the 5,000-IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $0.048 | $720 | [Buy the 15,000-IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | $0.035 | $863 | [Buy the 25,000-IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | $0.029 | $1,438 | [Buy the 50,000-IP package](https://bit.ly/9-Proxy) |

### Business IP packages (high volume)

| Package | Effective price per IP | Total | Purchase |
| --- | --- | --- | --- |
| 100,000 IPs | $0.023 | $2,300 | [Get the 100,000-IP business package](https://bit.ly/9-Proxy) |
| 200,000 IPs | $0.021 | $4,140 | [Get the 200,000-IP business package](https://bit.ly/9-Proxy) |
| 500,000 IPs | $0.018 | $8,625 | [Get the 500,000-IP business package](https://bit.ly/9-Proxy) |

### GB-based residential packages

| Package | Price per GB | Total | Validity | Purchase |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | [Buy the 5 GB package](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $2.10 | $105 | 180 days | [Buy the 50 + 5 GB package](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | 180 days | [Buy the 100 GB package](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | 180 days | [Buy the 200 GB package](https://bit.ly/9-Proxy) |
| 1,000 GB | $0.80 | $800 | 180 days | [Buy the 1,000 GB package](https://bit.ly/9-Proxy) |
| 2,000 GB | $0.75 | $1,500 | 180 days | [Buy the 2,000 GB package](https://bit.ly/9-Proxy) |

### Enterprise GB packages (no expiry)

| Package | Price per GB | Total | Validity | Purchase |
| --- | --- | --- | --- | --- |
| 3,000 GB | $0.72 | $2,160 | Unlimited | [Buy the 3,000 GB enterprise package](https://bit.ly/9-Proxy) |
| 6,000 GB | $0.70 | $4,200 | Unlimited | [Buy the 6,000 GB enterprise package](https://bit.ly/9-Proxy) |
| 10,000 GB | $0.68 | $6,800 | Unlimited | [Buy the 10,000 GB enterprise package](https://bit.ly/9-Proxy) |

### Bundle packages (IPs + bandwidth)

| Bundle | Total | Purchase |
| --- | --- | --- |
| 100 IPs + 5 GB | $30 | [Buy the Starter bundle](https://bit.ly/9-Proxy) |
| 1,500 IPs + 50 GB | $180 | [Buy the Popular bundle](https://bit.ly/9-Proxy) |
| 5,000 IPs + 500 GB | $720 | [Buy the Pro bundle](https://bit.ly/9-Proxy) |

Two things stand out in that list. The 1,000 + 500 IP tier is where the per-IP price craters from $0.144 to $0.084, which is why 9Proxy labels it the most popular package. And the 5 GB tier at $3.00/GB is expensive relative to Decodo's entry rate of $3.75/GB — only marginally cheaper — which means 9Proxy's GB pricing is not where its value lives. If you're buying gigabytes, you're buying the wrong product from this vendor.

## Decodo pricing: what the "$2/GB" headline actually involves

Decodo's residential page leads with "from $2/GB." That rate sits on the enterprise tier. The self-service tiers look like this:

| Plan | Price per GB | Notes |
| --- | --- | --- |
| Pay as you go | $4.00/GB | No monthly commitment |
| 3 GB | $3.75/GB ($11.25) | Entry tier |
| 10 GB | $3.50/GB | Self-service |
| 25 GB | $3.25/GB | Self-service |
| 50 GB | $3.00/GB | Self-service |
| 100 GB | $2.75/GB ($275) | Top self-service tier |
| 250 GB | $2.50/GB ($625) | Enterprise |
| 1 TB | $2.00/GB ($2,000) | Enterprise |

All prices exclude VAT. Unused bandwidth on subscription plans expires monthly, which is the opposite of 9Proxy's 180-day window on GB packages. Decodo also sells static residential (ISP) proxies from $0.27/IP, mobile proxies, datacenter proxies and a web scraping API, and a trial exists: 100 MB for 3 days, along with a 14-day money-back guarantee on paid plans — though using the free trial voids that refund.

AIMultiple's 2026 pricing benchmark rated Decodo the cost-efficiency leader across volumes from 10 GB to 10 TB. In independent live testing by Shifter, Decodo returned 281,121 active residential IPs across five countries, including 138,914 US addresses, with median response times between 536 ms and 636 ms. The same test flagged its weaker spot: addresses came from 2,284 distinct networks versus the 2,441 the benchmark network registered, and anti-bot systems fingerprint the network an IP belongs to, not just the IP.

## Side-by-side specs

|  | 9Proxy | Decodo |
| --- | --- | --- |
| Residential IP pool (advertised) | 20M+ across 90+ countries | 115M+ across 195+ locations |
| Product lines | Residential only | Residential, static ISP, mobile, datacenter, scraping APIs |
| Pricing models | Per IP (unlimited bandwidth), per GB, bundles | Per GB, plus per-IP static residential |
| Geo-targeting | Country, state, city, ZIP, ISP | Country, state, city, ZIP, ASN (included) |
| Protocols | HTTP, HTTPS, SOCKS5 | HTTP(S), SOCKS5 |
| Session control | Sticky IPs lasting hours up to ~24, rotating on GB plans | Rotating plus sticky presets (1/10/30/60 min, custom) |
| Concurrent sessions | Not published as a headline figure | Unlimited |
| Bandwidth expiry | 180 days on GB packages, unlimited on enterprise GB | Monthly on subscriptions |
| Entry price | $24 (IP) / $15 (GB) | $11.25 for 3 GB |

## Which one to pick, by job

**Large scraping jobs with heavy per-request payloads.** 9Proxy. Unlimited bandwidth per IP removes the meter entirely, and if a job burns 800 GB a month off 300 IPs, the $126 tier handles it. Paying Decodo for 500 GB would cost more than a thousand dollars.

**Broad-footprint collection across many geographies.** Decodo. 195+ locations, ASN-level targeting included, and a pool an order of magnitude larger. If your target sites differ by region and you need to test how pages render across cities, Decodo's coverage depth is the practical advantage.

**Multi-account management and long sessions.** Both work, differently. 9Proxy's IP-based plans hand you individual addresses you can hold and rebind, and sticky sessions on GB plans keep an IP consistent across multi-step flows. Decodo offers sticky presets from one minute to an hour with custom durations and unlimited concurrency.

**Teams that also need mobile, ISP or datacenter proxies.** Decodo. 9Proxy doesn't sell these at all, so you'd be running two vendors and two dashboards.

**Streaming and media access.** Check terms before you buy. 9Proxy has signalled that media streaming (YouTube being the example cited) is no longer supported on IP-based plans under an updated acceptable use policy. This is exactly the kind of restriction that's easy to miss and then argue about with support.

## The caveats nobody puts in the comparison table

9Proxy's replacement policy sounds generous until you read the clock. If an IP dies within the first 60 seconds of activation, you get it credited back or swapped. After that minute, a dead IP is a consumed IP. Residential addresses are inherently unstable, and the recurring complaint on 9Proxy's Trustpilot profile — currently sitting at 2 out of 5 — comes from buyers who bought in, found the service didn't fit their targets, and couldn't recover the spend. Review-site scores for the same company range from 3.9 to 4.3 depending on who's rating. There's also no clearly advertised free trial, so you're effectively buying before you can validate IP quality against your own targets. Budget for a small test package first and treat it as the cost of due diligence.

Decodo's caveats are structural rather than policy-based. Unused bandwidth expiring monthly punishes irregular workloads. Pay-as-you-go at $4/GB is far more expensive than a subscription if you use more than a few gigabytes. The $2/GB figure requires a 1,000 GB monthly commitment, and the free trial cancels your refund window. Also verify tax treatment: residential prices are quoted excluding VAT, so the invoice total depends on where you're billed.

## Quick answers

**Is 9Proxy cheaper than Decodo?** Only for bandwidth-heavy work. 9Proxy's per-IP model starts at $24 for 100 IPs with unlimited traffic, while Decodo's cheapest residential plan is $11.25 for 3 GB. For light traffic on a massive pool, Decodo is cheaper.

**Does 9Proxy have mobile or datacenter proxies?** No. It's residential-only, which is a real limitation if your workflow needs device-specific or datacenter IPs.

**How long does a 9Proxy IP last?** Residential IPs are unpredictable. 9Proxy's own documentation allows up to roughly 24 hours, with much shorter lifespans common. The Today List lets you reuse any proxy accessed in the last 24 hours at no extra charge when it comes back online.

**Which has a free trial?** Decodo: 100 MB for 3 days. 9Proxy doesn't clearly advertise one, so ask support before assuming.

## The bottom line

If your work is bandwidth-hungry and you don't need more than a few thousand stable residential addresses at a time, 9Proxy's per-IP packages are the cheaper structure and the gap isn't small — $126 for 1,500 IPs with unlimited data is a different order of magnitude from paying per gigabyte. Start small, verify the IPs work against your actual targets, then scale into the tier where the per-IP rate drops, which is 1,000 IPs plus the 500 bonus.

👉 [Compare 9Proxy's IP and GB packages and pick your tier](https://bit.ly/9-Proxy)

If instead you need geographic breadth, ASN targeting, unlimited concurrency, or ISP and mobile proxies from one dashboard, Decodo is the better fit, and its per-GB pricing is defensible at high volumes. You'll pay more per gigabyte at low usage and lose unused bandwidth each month, but you're buying coverage those budget IP packages can't match.

The mistake to avoid is buying gigabytes from the per-IP vendor or buying IP volume from the per-GB vendor. Both charge you for the thing you're not using.

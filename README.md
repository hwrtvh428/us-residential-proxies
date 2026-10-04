# Buy US Proxies: How to Get Clean US Residential IPs by State and City Without Paying Per-Gigabyte Prices

Most people who type "buy US proxies" already know why they need an American IP. What they don't know yet is what a fair price looks like, how much geographic precision they can actually get, or why two providers quoting "US residential" can differ by 6x in cost.

That's the gap this article fills. It walks through the pricing models, the targeting options that matter, what independent testing has found, and a full breakdown of one residential provider — 9Proxy — whose per-IP billing changes the math for anyone moving serious volume through US addresses.

## What you're actually buying

"US proxy" is a category, not a product. Four types sit under it, and picking the wrong one is the fastest way to waste money.

| Proxy type | What the IP looks like | Typical speed | Flagged by anti-bot systems |
| --- | --- | --- | --- |
| Datacenter | Server hosting range (AWS, DigitalOcean, etc.) | Fastest | Often, within a few requests |
| ISP / static residential | Residential range, hosted on datacenter hardware | Fast | Rarely |
| Rotating residential | Real home connection | Moderate | Rarely |
| Mobile | Carrier network (4G/5G) | Slowest | Almost never |

If your targets are plain websites with no bot protection, datacenter IPs are cheap and fast and you should buy those. If you're dealing with Amazon, eBay, ticketing platforms, sneaker sites, social platforms or Google SERPs, datacenter IPs get blocked quickly — a comparison test run on the same request pattern through a datacenter pool produced a 34% block rate on the first pass, against 0.6% for residential.

Worth flagging: 9Proxy sells residential only. No datacenter, no mobile, no static ISP as separate products. If your workflow needs a mix, you're running two providers or looking elsewhere.

## Per-IP vs per-GB: the decision that actually drives your bill

There are two ways residential providers charge, and the wrong pick can double your effective cost.

**Per IP, unlimited bandwidth.** You buy a fixed number of addresses and route as much traffic through each as you want during its lifetime. This suits tasks where bandwidth is hard to predict — long scraping jobs, browser sessions, video, bulk downloads, or anything where a single endpoint might push hundreds of megabytes.

**Per GB.** You buy traffic and generate as many endpoints as you like from it. This suits high-rotation work where each request is small: SERP checks, price lookups, ad verification, geo-testing. A single page fetch might be 40–80 KB. Rotating through thousands of IPs while burning 2 GB a week costs almost nothing under this model and a fortune under per-IP if you're paying for addresses you use once.

The failure case is buying 100 IPs for a job that only needs 5 GB of traffic spread across 50,000 rotating endpoints. The second failure case is buying 20 GB for a scraper that pulls 300 GB a month.

A rough rule: if you can name the number of concurrent sessions you need, buy IPs. If you can only name the monthly data volume, buy GB. If you genuinely need both, bundles exist.

## How deep does US targeting actually go?

This is where providers separate. Country-level targeting on "United States" is table stakes. The useful tiers are:

- **State** — for anything checking regional pricing or state-specific listings
- **City** — for local SEO, local pack ranking, and metro-level ad verification
- **ZIP code** — for hyper-local checks, delivery estimates, store availability
- **ISP** — for matching specific carriers like Comcast, AT&T, Verizon, or Frontier

Latency also varies by region. Ashburn, Virginia hosts a large share of US cloud infrastructure, so providers routing traffic directly through Virginia typically see response times 0.4–0.6 seconds faster than providers routing elsewhere in the country. On high-frequency collection jobs, that gap matters more than raw bandwidth.

9Proxy supports country, state, city, ZIP and ISP filtering on its GB-based plans, and country/city/ISP/ZIP on the IP-based side via its desktop app. Coverage is 90+ countries — not 195 — so if you need a long tail of small markets, verify before committing. For the US, UK, Western Europe and Southeast Asia, coverage is solid.

## A full look at 9Proxy's current plan lineup

9Proxy launched in 2023 and builds on a network the company describes as 20 million+ residential IPs across 90+ countries and 8,000+ servers. On June 1, 2026 it raised prices on IP-based and bundle packages for the first time; GB-based pricing was left untouched.

Here's the complete lineup as currently published.

| Plan | What you get | Price (USD) | Effective rate | Buy |
| --- | --- | --- | --- | --- |
| IP-Based — 100 IPs | 100 residential IPs, unlimited bandwidth | $24 | $0.24/IP | [Get the 100-IP starter package](https://bit.ly/9-Proxy) |
| IP-Based — 500 IPs | 500 IPs, unlimited bandwidth | $72 | $0.144/IP | [Buy 500 US-ready IPs](https://bit.ly/9-Proxy) |
| IP-Based — 1,000 + 500 bonus | 1,500 IPs total, unlimited bandwidth | $126 | $0.084/IP | [Take the 1,500-IP package](https://bit.ly/9-Proxy) |
| IP-Based — 2,500 IPs | 2,500 IPs, unlimited bandwidth | $210 | $0.084/IP | [Compare the 2,500-IP tier](https://bit.ly/9-Proxy) |
| IP-Based — 5,000 IPs | 5,000 IPs, unlimited bandwidth | $360 | $0.072/IP | [Get 5,000 IPs](https://bit.ly/9-Proxy) |
| IP-Based — 15,000 IPs | 15,000 IPs, unlimited bandwidth | $720 | $0.048/IP | [Scale to 15,000 IPs](https://bit.ly/9-Proxy) |
| IP-Based — 25,000 IPs | 25,000 IPs, unlimited bandwidth | $863 | $0.035/IP | [Buy the 25,000-IP pack](https://bit.ly/9-Proxy) |
| IP-Based — 50,000 IPs | 50,000 IPs, unlimited bandwidth | $1,438 | $0.029/IP | [Get the 50,000-IP package](https://bit.ly/9-Proxy) |
| Business IP — 100,000 IPs | 100,000 IPs, unlimited bandwidth | $2,300 | $0.023/IP | [See the 100,000-IP business tier](https://bit.ly/9-Proxy) |
| Business IP — 200,000 IPs | 200,000 IPs, unlimited bandwidth | $4,140 | $0.021/IP | [Check the 200,000-IP tier](https://bit.ly/9-Proxy) |
| Business IP — 500,000 IPs | 500,000 IPs, unlimited bandwidth | $8,625 | $0.018/IP | [Buy 500,000 IPs in bulk](https://bit.ly/9-Proxy) |
| GB-Based — 5 GB | 5 GB of rotating traffic, 180-day validity | $15 | $3.00/GB | [Start with a 5 GB test balance](https://bit.ly/9-Proxy) |
| GB-Based — 50 + 5 bonus GB | 55 GB of traffic, 180-day validity | $105 | $2.10/GB | [Get the 55 GB traffic pack](https://bit.ly/9-Proxy) |
| GB-Based — 100 GB | 100 GB, 180-day validity | $150 | $1.50/GB | [Buy 100 GB of US traffic](https://bit.ly/9-Proxy) |
| GB-Based — 200 GB | 200 GB, 180-day validity | $200 | $1.00/GB | [Take 200 GB](https://bit.ly/9-Proxy) |
| GB-Based — 1,000 GB | 1,000 GB, 180-day validity | $800 | $0.80/GB | [Get the 1,000 GB tier](https://bit.ly/9-Proxy) |
| GB-Based — 2,000 GB | 2,000 GB, 180-day validity | $1,500 | $0.75/GB | [Buy 2,000 GB](https://bit.ly/9-Proxy) |
| GB-Based — Enterprise volume | Down to $0.68/GB at the 10,000 GB tier | Quoted on request | $0.68/GB | [Request the enterprise rate](https://bit.ly/9-Proxy) |
| Starter Bundle | 100 IPs + 5 GB | $30 | — | [Get the Starter bundle](https://bit.ly/9-Proxy) |
| Popular Bundle | 1,500 IPs + 50 GB | $180 | — | [Get the Popular bundle](https://bit.ly/9-Proxy) |
| Pro Bundle | 5,000 IPs + 500 GB | $720 | — | [Get the Pro bundle](https://bit.ly/9-Proxy) |
| Enterprise (GB) | Custom traffic volume, unlimited data validity, team of 1 owner + 5 members, per-member controls, VIP pricing | Quoted on request | — | [Talk to 9Proxy about enterprise](https://bit.ly/9-Proxy) |

Three things about that table that matter more than the numbers.

First, nothing here is a subscription. It's a prepaid balance. Unused IPs don't expire until you activate them, and GB traffic stays valid for 180 days — unlimited on enterprise plans. There's no monthly auto-renewal to cancel.

Second, the per-IP column is where the volume discount lives. Going from 100 IPs to 50,000 IPs cuts the unit price from $0.24 to $0.029 — roughly 88% — and the jump from 1,000 IPs to 25,000 barely moves the total bill relative to what you get.

Third, if you mainly need US addresses for scraping, compare the 1,500-IP package at $126 against 100 GB at $150. The second gives you unlimited rotating endpoints and roughly double the nominal size, but it runs out. The first doesn't.

## What independent testing found

Published marketing numbers are easy to write. Actual results against protected targets are not.

A Geekflare test ran 300 sequential requests through 9Proxy's rotating residential IPs against a major e-commerce site sitting behind Cloudflare. Results: 293 successful responses (97.7%), 5 CAPTCHA challenges (1.7%) and 2 hard blocks (0.6%), with an average response time of 0.63 seconds. All five CAPTCHAs came from the same IP range, and rotating out of it cleared them immediately. The same test pattern through a datacenter pool produced a 34% block rate.

A separate case-study writeup reported roughly 99.5% success and about 0.6 seconds average response across its own tests. A third-party comparison directory lists 9Proxy at a 97% success rate and around 1,300 ms response time, which is a less flattering figure but roughly the same neighborhood. Different targets, different days.

On Trustpilot the service sits at 4.6/5. One caveat worth knowing: a meaningful share of those reviews date from 2024, and the negative ones cluster around the refund policy rather than connection quality — people who bought the wrong plan type and couldn't get money back. Geekflare reached the same conclusion independently.

## How to buy and get your first US IPs

1. **Create an account.** Sign-up runs on an invite code.
2. **Top up your balance.** Accepted payment methods include credit cards, bank cards, USDT, BTC, ETH, LTC, DOGE, Alipay, Apple Pay and Google Pay.
3. **Pick a package.** Small entry packages are the cheapest way to test the network against your actual targets before committing.
4. **Choose how you'll connect.** GB-based plans work entirely in the dashboard — username/password or IP whitelist authentication, no software needed. IP-based plans traditionally required the desktop app (Windows, macOS, Linux); the newer Proxy2Web interface lets you pull IPs straight from a browser, which removes the app dependency for tablets, remote machines and locked-down systems.
5. **Set your target.** Filter down to the United States, then state, city, ZIP or ISP depending on how specific your target audience is.
6. **Pick a session mode.** Sticky holds the same IP for a set number of minutes — necessary for logins and multi-step forms. Rotating issues a fresh IP every request or session, which is what you want for broad collection.
7. **Export and deploy.** Endpoints come out as .txt or .csv, with code samples in several languages.

👉 [Start a 9Proxy account and test US residential IPs](https://bit.ly/9-Proxy)

## Limits worth knowing before you pay

**IP lifetime is short by design.** A residential IP-based address stays live anywhere from a few hours to about 24 hours, averaging around three. That's normal for residential — it reflects how real home connections behave — but it rules out long-term account binding on the IP-based product. There's no static ISP tier to fall back on.

**No free trial.** 9Proxy does not currently offer one. There is a 60-second refund policy: if an IP fails within the first minute of activation, you get credit back automatically. The Today List covers the rest — any IP you've used in the last 24 hours can be reused at no extra charge if it comes back online. Longer-lived failures need manual replacement requests. You can also ask support for a test balance, which is worth doing before a large purchase.

**Pool size is mid-market.** 20 million+ addresses is plenty for most scraping and automation work, but it's a different tier from providers running 70–100 million. One published breakdown of 9Proxy's per-country counts puts the US at roughly 572,600 IPs, with Canada at 530,800 and the UK at 446,080. That's deep enough for US-focused work and thin for niche geographies.

**Reliability has a spotty chapter.** Independent directories reported 9Proxy going offline in June 2026 for around two weeks, and again briefly later that year, with support channels silent during both. The service came back both times, and none of the major 2026 reviews treat the network as low quality when it's up. But it's a real consideration: if your pipeline depends on uninterrupted proxy access, don't park your entire budget in one wallet, and don't design a workflow with no fallback.

**Peak-hour slowdowns in some regions.** Southeast Asia in particular. US and Western European targets perform better.

Put together, that points to starting small: buy the entry package, point it at your actual target sites for a week, and let the results decide. That's a cheaper experiment than discovering after a $720 bundle that residential was the wrong category for your job.

## FAQ

**How much should US residential proxies cost?**
Entry tiers run $0.20–$0.30 per IP or $3–$5 per GB. At volume, per-IP pricing drops below $0.03 and per-GB below $1.00. Anything above $5/GB for Tier 1–2 US targets is paying for enterprise tooling you may not need.

**Is it legal to buy and use US proxies?**
Buying and using proxies for legitimate research, ad verification, SEO monitoring, price comparison and fraud prevention is generally lawful. What matters is what you do through them: respecting target sites' terms of service, avoiding authenticated or non-public data, and complying with applicable privacy law such as CCPA. This is not legal advice.

**Do I need a desktop app?**
For GB-based plans, no — everything runs in the browser dashboard. For IP-based plans, the desktop app (Windows, macOS, Linux) has been the standard route, though Proxy2Web now allows browser-based IP retrieval.

**How many US IPs do I need?**
Match IP count to concurrent sessions, not to total requests. If you run 50 browser profiles or scraper threads at once, 100 IPs gives you headroom. If your traffic rotates per request, buy GB instead and generate endpoints freely.

**Can I target a specific US state or city?**
Yes — state, city, ZIP and ISP filtering are supported. Verify your specific combination against the pool before a large purchase, since not every city has meaningful inventory.

**Do unused IPs expire?**
On the IP-based product, no. IPs stay in your balance until activated, and once activated they run for their natural lifetime. GB-based traffic is valid for 180 days, and unlimited on enterprise plans.

<style>
</style>

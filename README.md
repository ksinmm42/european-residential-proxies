# european proxies: country-accurate residential IPs for DE, FR and UK price checks, SERP tracking and ad verification

Europe is not one market with one set of prices. It's a few dozen markets stacked next to each other, and the IP you connect from decides which one you see.

Try to pull pricing from Amazon.de while routing through a US address and you'll get dollars, wrong stock levels, and probably a CAPTCHA. Point the same script at Amazon.fr from a German IP and the numbers are still wrong — just in euros this time. The same logic applies to `google.de` versus `google.fr` SERPs, to Allegro in Poland, bol.com in the Netherlands, and to any ad you're trying to verify in a country you don't live in.

That's the real reason people search for European proxies: they need an exit node that looks like a normal household in a specific European country, for a specific task. This guide covers what to actually check before buying, and how 9Proxy's per-IP and per-GB models line up with that work — including the current price list after their June 2026 adjustment.

## What "European proxies" should mean in practice

Handled badly, it means a provider that lists "Europe" as a region and hands you whatever IP is free — sometimes Frankfurt, sometimes Bucharest, occasionally London when you asked for Berlin. Handled properly, it means country-level targeting you can set per request, plus city, ZIP and ISP filters for cases where it matters.

The difference shows up fast:

- **Cross-border e-commerce intelligence.** Amazon, Zalando, Otto, El Corte Inglés, PcComponentes, Allegro and bol.com all price against the visitor's country and currency. A French IP on a German store returns data you can't use.
- **Local SERP tracking.** Google shows different results per country domain and often per city. Tracking three countries with one shared "EU" IP gives you a blended average that matches nothing.
- **Ad verification.** Confirming a campaign actually runs in the country you bought means checking from that country — geo-fenced creatives simply don't render otherwise.
- **Multi-account and marketplace work.** Marketplaces and social platforms tie account trust to IP reputation. Datacenter ranges get flagged quickly; residential IPs registered to local ISPs behave like ordinary shoppers.

There's also the compliance layer, and it's worth being blunt about it. GDPR applies across the EU, but enforcement intensity differs by country — Spain's AEPD and Italy's Garante have historically issued the most decisions, while France's CNIL is known for large adtech fines. Publicly available, non-personal data (prices, listings, rankings, ad placements) is generally the defensible zone. Personal data is where the risk actually sits, so keep names, profiles and contact details out of the pipeline.

## Four checks that separate usable European coverage from a wasted invoice

**1. Country depth, not headline pool size.** A network advertising 100 million IPs tells you nothing about whether 40,000 of them are live in Poland at 3 a.m. your time. Ask how many endpoints a provider can hand back in your specific target countries, and test that yourself before you scale a budget onto it.

**2. Targeting granularity.** Country-level filtering is the minimum. City and ZIP targeting matter for delivery estimates and regional pricing; ISP targeting matters when a retailer or platform treats one carrier's ranges differently from another's.

**3. Session behaviour.** Some jobs want the same IP held for hours (logged-in sessions, carts, multi-account work). Others want a fresh IP on every request (broad scraping, geo-checks). A provider that only does one of those forces you into workarounds.

**4. Billing model.** Per-IP billing with unlimited bandwidth and per-GB billing with unlimited endpoints fail in opposite directions. Pick wrong and you either waste money on bandwidth you never used or burn gigabytes on a job where IP count was the only thing you needed.

9Proxy sells both models on the same account, which is the main reason it comes up in this conversation at all.

## How 9Proxy fits European workloads

9Proxy runs a residential pool of 20M+ IPs across 90+ countries, with HTTP/HTTPS and SOCKS5 support and filtering down to country, state, city, ZIP and ISP. European markets are covered, and you set the location per endpoint rather than accepting whatever the pool assigns.

The two products behave very differently, and that matters more than the marketing copy:

**Residential by IP** gives you a fixed number of dedicated residential IPs with no traffic cap. Each IP stays alive for a few hours up to roughly 24 hours, and any IP you haven't used yet doesn't expire. It routes through the desktop client (Windows, macOS, Linux), which forwards IPs to local ports — so any application that accepts a proxy can use them. There's an Auto Rotation Proxy for rotating on custom intervals on selected ports, and a Today List that lets you reuse an IP you already used in the last 24 hours without spending another one. Confirmed dead IPs can be replaced.

**Residential by GB** charges for traffic and lets you generate unlimited endpoints. Sticky or rotating sessions, username/password or IP whitelist authentication, and it all runs from the dashboard — no app install. Traffic is valid for 180 days, and Enterprise packages remove the expiry entirely.

Two practical notes before the tables. First, the desktop client is required for IP-based plans but not for GB-based ones, so if you're running everything from a cloud server or a script, the GB model is the shorter path. Second, 9Proxy raised IP-based and Bundle prices on 1 June 2026 — the first increase since launch — while GB-based pricing stayed where it was.

👉 [Check the current 9Proxy packages and get started](https://bit.ly/9-Proxy)

## The full 9Proxy price list

### Residential by IP — unlimited bandwidth per IP

| Package | Price per IP | Total | Billing | Get it |
| --- | --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | One-off top-up | [Buy 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | $0.144 | $72 | One-off top-up | [Buy 500 IPs](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $0.084 | $126 | One-off top-up | [Buy 1,000 IPs](https://bit.ly/9-Proxy) |
| 2,500 IPs | $0.084 | $210 | One-off top-up | [Buy 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | $0.072 | $360 | One-off top-up | [Buy 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | $0.048 | $720 | One-off top-up | [Buy 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | $0.035 | $863 | One-off top-up | [Buy 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | $0.029 | $1,438 | One-off top-up | [Buy 50,000 IPs](https://bit.ly/9-Proxy) |

Business tiers, for teams running six-figure IP volumes:

| Package | Price per IP | Total | Billing | Get it |
| --- | --- | --- | --- | --- |
| 100,000 IPs | $0.023 | $2,300 | One-off top-up | [Buy 100,000 IPs](https://bit.ly/9-Proxy) |
| 200,000 IPs | $0.021 | $4,140 | One-off top-up | [Buy 200,000 IPs](https://bit.ly/9-Proxy) |
| 500,000 IPs | $0.018 | $8,625 | One-off top-up | [Buy 500,000 IPs](https://bit.ly/9-Proxy) |

Unused IPs don't expire, so buying ahead doesn't cost you anything while they sit on your balance.

### Residential by GB — unlimited endpoints

| Package | Price per GB | Total | Validity | Get it |
| --- | --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days | [Buy 5 GB](https://bit.ly/9-Proxy) |
| 50 GB + 5 bonus | $2.10 | $105 | 180 days | [Buy 50 GB](https://bit.ly/9-Proxy) |
| 100 GB | $1.50 | $150 | 180 days | [Buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $1.00 | $200 | 180 days | [Buy 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | $0.80 | $800 | 180 days | [Buy 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | $0.75 | $1,500 | 180 days | [Buy 2,000 GB](https://bit.ly/9-Proxy) |

Enterprise GB packages trade a higher spend for traffic that never expires, plus team access:

| Package | Price per GB | Total | Validity | Get it |
| --- | --- | --- | --- | --- |
| 3,000 GB | $0.72 | $2,160 | No expiry | [Buy 3,000 GB](https://bit.ly/9-Proxy) |
| 6,000 GB | $0.70 | $4,200 | No expiry | [Buy 6,000 GB](https://bit.ly/9-Proxy) |
| 10,000 GB | $0.68 | $6,800 | No expiry | [Buy 10,000 GB](https://bit.ly/9-Proxy) |

Enterprise also adds a team mode with one owner and up to five members, per-member traffic controls, activity logs and unlimited share-code creation.

### Bundles — IPs plus bandwidth

| Bundle | What's included | Price | Traffic validity | Get it |
| --- | --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | 180 days | [Buy the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | 180 days | [Buy the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | 180 days | [Buy the Pro bundle](https://bit.ly/9-Proxy) |

All of these are balance top-ups, not recurring subscriptions. Nothing renews on its own.

## Matching the plan to the European job

**Light, wide EU scraping and geo-checks → GB plan.** If you're hitting 20 different country domains to compare listing pages and each request pulls maybe 60 KB, per-request rotation over a per-GB plan is the cheaper structure by a wide margin. Entry is $15 for 5 GB with $3.00/GB pricing, dropping to $0.75/GB at 2 TB.

**Long sticky sessions in one or two countries → IP plan.** Logged-in marketplace sessions, cart flows, account management — those want the same exit IP held for hours. The 100-IP tier at $24 covers a modest multi-account setup, and unlimited bandwidth means a heavy session doesn't cost extra.

**Both at once → a bundle.** Starter at $30 (100 IPs + 5 GB) is the practical way to run stable sessions for a small set of countries while leaving bandwidth-based rotation for the high-volume crawl. It's more per unit than buying either alone at scale, but it removes the "which one do I need" question.

**Agency or reseller work → Business IP or Enterprise GB.** Share codes and sub-accounts let you hand clients their own slice without sharing your own credentials, and Business IP rates fall to $0.018 per IP at 500,000.

One thing to keep in mind regardless of tier: European coverage depth isn't uniform across providers, and thin pools in smaller markets are a common complaint. Test the exact countries you care about before committing a large balance.

## Setting up a German or French exit node

**On the IP-based model**

1. Install the desktop client on Windows, macOS or Linux and sign in.
2. Open the proxy forwarding view (`9proxy proxy -u` in the CLI) and filter the list — press F to filter by country, state, city, ZIP or ISP, then apply.
3. Forward the IP you want to a local port, either to a single port or across your configured range.
4. Point your tool at `127.0.0.1:<port>`.

Command-line equivalents work fine for automation. `9proxy proxy -c US -p 60000` forwards a US IP to port 60000; swap the two-letter code for your European target, and `-n` reuses an IP from your Today List instead of consuming a new one.

**On the GB-based model**

1. Open the dashboard and head to the Proxy Generator.
2. Choose the country — and the state, city, ZIP or ISP if you need that precision.
3. Select sticky or rotating mode. Sticky holds one IP for the session; rotating swaps per request.
4. Create sub-users or whitelist your server IP for authentication.
5. Export the endpoint list as `.txt` or `.csv`, or grab the ready-made code sample in your language.

Both models let you keep separate credential sets per project, which is worth doing: one group of endpoints for price monitoring, another for ad verification. Mixing traffic across the same identity defeats the point of buying country-specific IPs.

👉 [Set up your 9Proxy account and pick a European location](https://bit.ly/9-Proxy)

## Questions that come up before buying

**Do I need a different provider for each European country?**
No. You need IPs located in each country, which is a targeting setting, not a separate purchase. One account with country switching handles a fifteen-market project. What you should avoid is using a German IP to collect French data — you'll get French pages rendered with the wrong currency and inventory signals.

**Which model is cheaper for European SERP tracking?**
It depends on payload size. A SERP check is a small response, so a per-GB plan usually wins — the same GB budget buys far more requests than a per-IP plan buys sessions. If you're holding sessions open to scrape logged-in dashboards, per-IP with unlimited bandwidth flips the math.

**What happens when a residential IP drops?**
IP-based residential IPs live somewhere between a few hours and about 24 hours, which is normal for real consumer connections. When one goes dead, you can check its status in the Today List; if it's used within the last 24 hours and comes back online, reusing it costs nothing extra, and confirmed dead IPs are refunded to your balance.

**Is any of this legal in the EU?**
Collecting publicly available, non-personal data — prices, listings, search results, ad placements — is a defensible position across the EU. GDPR's heavier rules attach to personal data, and enforcement appetite varies by country. Keep personal data out of the pipeline and you avoid the part that actually carries fines.

If your work needs country-accurate European IPs without an enterprise contract attached, the entry points are small: $15 for 5 GB if you lean on rotation, $24 for 100 IPs if you lean on sessions. Start with the country you care about most, verify the geolocation against a real target site, then scale the balance.

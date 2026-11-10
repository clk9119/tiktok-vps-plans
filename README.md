# VPS for TikTok: Native or Residential IP, Which Plan to Buy, and What the Monthly Bill Actually Looks Like

WePC's two Singapore plans run on identical hardware: 2 cores, 1 GB RAM, 10 GB NVMe, a 200 Mbps port and 2 TB of monthly traffic. One carries a native Singapore IP and lists between AUD 14.90 and 16.90 depending on which plan snapshot you read; the other carries an ISP residential IP and has held at AUD 24.90. That gap is the whole purchase decision for most TikTok operators, because TikTok's risk system grades the network you connect from before it grades anything you upload.

Below is every plan WePC currently lists with starting prices, what the discount codes actually save over twelve months, what a mainland-China setup costs once a relay hop is added, and how to use the 3-day refund window to test an IP before you commit an aged account to it.

> **Quick pick:** Take the Singapore native IP plan if you post, warm up accounts, or run short livestreams you can afford to lose. Go straight to the Singapore residential plan at AUD 24.90 if you livestream for hours, run aged accounts, or manage several profiles where one flag costs real money. On annual billing the `WePCYEAR80` code brings that residential plan to roughly **AUD 19.92/month equivalent**.
>
> 👉 [See current WePC TikTok VPS pricing](https://wepc.au/aff.php?aff=300)

## Every WePC TikTok VPS plan, with starting prices

WePC is an Australian-registered host (ZGX PTY LTD, Melbourne) that sells region-specific TikTok VPS instead of general cloud. Coverage runs past 15 regions, each line ships with a dedicated IPv4 in the target country, and the product pages talk about livestreaming and account nurturing rather than CPUs and IOPS.

One thing to read carefully in the table: the word "Dedicated" in a plan name means the IP is yours alone. It does not mean the IP is residential. Singapore, Korea and the two US dual-ISP lines are explicitly residential; Malaysia is listed as a hosting IP; the rest are native commercial IPs. If residential status is what you're buying, confirm it per line.

| Plan (region) | CPU / RAM / disk | Port / traffic | IP and relay | From (AUD/mo) | Order |
| --- | --- | --- | --- | --- | --- |
| UK TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 200 Mbps / 1 TB | Native IPv4, not residential | 8.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Germany TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 200 Mbps / 1 TB | Native IPv4, relay for Telecom | 8.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Canada TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 200 Mbps / 1 TB | Native IPv4 | 12.90 | [Order](https://wepc.au/aff.php?aff=300) |
| US New York Dual-ISP Residential | 1C / 0.5 GB / 10 GB SSD | 200 Mbps / 1.5 TB | Dual-ISP residential, 4837 | 12.90 | [Order](https://wepc.au/aff.php?aff=300) |
| US Los Angeles Dual-ISP Residential | 1C / 0.5 GB / 10 GB SSD | 200 Mbps / 1.5 TB | Dual-ISP residential, 4837 | 12.90 | [Order](https://wepc.au/aff.php?aff=300) |
| France TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 100 Mbps / 1 TB | Native IPv4, relay recommended | 14.90 | [Order](https://wepc.au/aff.php?aff=300) |
| UK Commercial Bandwidth TK | 1C / 0.5 GB / 10 GB SSD | 200 Mbps / 2 TB | UK native business IPv4 | 14.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Australia TK Dedicated | 2C / 1 GB / 10 GB SSD | 200 Mbps / 2 TB | Native, Telecom needs relay | 14.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Singapore TK Dedicated | 2C / 1 GB / 10 GB SSD | 200 Mbps / 2 TB | Native Singapore, Telecom needs relay | 14.90 | [Order](https://wepc.au/aff.php?aff=300) |
| US Los Angeles 9929 Residential | 2C / 768 MB / 10 GB SSD | 200 Mbps / 1.5 TB | Residential, 9929 optimized | 15.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Taiwan TK Live Dedicated | 2C / 1 GB / 10 GB SSD | 200 Mbps / 2 TB | Native, multi-hop, relay required | 16.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Vietnam TK Dedicated | 2C / 0.5 GB / 10 GB SSD | 50 Mbps / 2 TB | Native, Telecom requires relay | 16.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Japan TK Dedicated | 2C / 1 GB / 10 GB SSD | 200 Mbps / 2 TB | Native, direct, no relay | 18.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Korea Residential TK Live | 2C / 1 GB / 10 GB SSD | 100 Mbps / 2 TB | Residential, direct, no relay | 18.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Malaysia TK Dedicated | 2C / 768 MB / 10 GB NVMe | 100 Mbps / 2 TB | Hosting IP, Telecom requires relay | 18.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Spain TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 100 Mbps / 1 TB | Native IPv4, relay required | 19.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Indonesia TK Dedicated | 2C / 1 GB / 10 GB SSD | 50 Mbps / 2 TB | Native, relay for Telecom/Unicom | 19.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Philippines TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 50 Mbps / 1 TB | Native, relay in some regions | 19.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Thailand TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 100 Mbps / 1 TB | Native residential IPv4 | 19.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Singapore Residential TK Live | 2C / 1 GB / 10 GB SSD | 200 Mbps / 2 TB | Singapore ISP residential | 24.90 | [Order](https://wepc.au/aff.php?aff=300) |
| UAE TK Dedicated | 1C / 0.5 GB / 10 GB SSD | 100 Mbps / 2 TB | Native IPv4, relay for streaming | 24.90 | [Order](https://wepc.au/aff.php?aff=300) |
| Shenzhen–Hong Kong IEPL Relay | relay add-on | 300 Mbps / 500 GB at 2x metering | No IP, SOCKS/HTTP/TLS disabled | 19.90 | [Order](https://wepc.au/aff.php?aff=300) |

Three caveats on those numbers. Prices are AUD per month at list, before any code; WePC bills in AUD and lets you toggle the display to CNY at checkout, and the conversion the cart uses is not the live mid-market rate (one snapshot showed AUD 24.90 as RMB 117.13). Second, two different plan snapshots disagree by a couple of dollars on the Singapore native line and the Thailand entry line, so treat the table as a starting point and the cart total as the binding figure. Third, a Thailand Pro tier (2 cores, 500 Mbps, 2 TB) has appeared at AUD 14.90 in restock batches; it is cheaper than the entry tier and that is exactly why it sells out. Don't plan a budget around it.

### Which lines reach mainland China without a relay

Direct, no relay needed: Japan, Korea Residential, US New York, US Los Angeles (both the 4837 dual-ISP and the 9929 line).

Relay required or recommended: Singapore (both plans, and especially for livestreaming), Thailand, Vietnam, Australia, Germany, Spain, Taiwan, the Philippines in some regions, and the UAE for streaming. Indonesia and Vietnam run better on China Unicom and China Mobile than on Telecom. China Telecom users outside Shanghai are the ones the relay advice is really aimed at.

The relay itself is a separate AUD 19.90/month SKU: Shenzhen to Hong Kong, 300 Mbps, 500 GB measured at a 2x multiplier (so the allowance goes half as far), and it explicitly disables SOCKS, HTTP and TLS. It is not a general-purpose proxy. On the Thailand line there is an additional rule from WePC's own setup docs: don't run Shadowsocks bare without a relay, use the protocol in their install guide.

## Native IP vs residential IP: what the 50% buys

TikTok scores the ASN behind your connection. Addresses owned by hosting companies sit in ranges the platform can identify as datacenter space, and accounts logging in from them get throttled, or worse, quietly stop reaching the For You feed. A four-core machine on a flagged datacenter subnet loses to a one-core box on a clean residential range, which is why operators pay a premium for the second kind.

The Singapore pair makes that premium easy to price. Same 2 cores, same 1 GB RAM, same 10 GB NVMe, same 200 Mbps port, same 2 TB of traffic. The native plan has been listed at AUD 16.90 (RMB 79.49 on the plan page) in one snapshot and AUD 14.90 in another. The residential plan is AUD 24.90. You are paying roughly 50% more for a broadband IP from a Singapore ISP and getting an identical server.

Where that 50% earns its keep: hours-long livestreams where TikTok is watching the connection closely, aged accounts you can't rebuild, and multi-profile setups where one ban takes several accounts with it. Where it doesn't: posting, account warmup, and short test streams on accounts you're still building. Start on the native plan, and move to residential when the account is worth more than the price difference.

Residential stock is the other half of that decision. Singapore is a country of six million people; the pool of broadband subnets available to sell is finite, and the residential SKU is the one that shows zero during demand spikes. If you need it for a scheduled campaign, order before you need it rather than the morning of.

## The discount codes and the actual math

Two codes apply to the Singapore and Thailand lines:

- `WePCMON90` — 10% off, monthly and quarterly billing
- `WePCYEAR80` — 20% off, annual billing

Two more are US-only and won't touch Singapore or Thailand: `WePC9929MON85` (15% off monthly, US 9929/CN2 GIA plans) and `WePC9929YEAR70` (30% off annual, same line). Codes don't stack; you enter one in the promo field at checkout and it applies automatically.

On the AUD 24.90 residential plan, `WePCMON90` brings it to **AUD 22.41/month**. Twelve months on that basis is AUD 268.92. `WePCYEAR80` brings the effective rate to **AUD 19.92/month**, or AUD 239.04 paid up front. Annual billing saves about AUD 29.88 a year against monthly-with-code, and about AUD 59.76 against list price. Account nurturing is a multi-month project, so the annual code is usually the right call unless you're still deciding whether the IP works for you.

These codes circulate through 2026 community posts rather than an official coupon page. Confirm they still apply in the cart before paying, and note that discounted orders are sometimes excluded from the refund terms.

👉 [Check whether the annual code still applies to the Singapore residential plan](https://wepc.au/aff.php?aff=300)

## What a working setup costs per month

Singapore residential at list is AUD 24.90. Add the IEPL relay at AUD 19.90 and a China Telecom operator is at **AUD 44.80/month** before any discount. That is the honest number for a stable livestream setup from the mainland, and it's the cost most "cheap Singapore VPS" comparisons leave out. Unicom and Mobile users in many provinces can skip the hop and stay at AUD 24.90.

If you'd rather not configure any of it, WePC lists a done-for-you deployment at AUD 10 and a guided setup session including relay configuration at AUD 25. Neither is refundable, and neither includes the relay server itself.

## What 1 GB of RAM will and won't do

The whole lineup tops out at 2 cores and 1 GB of RAM, with Malaysia and the US 9929 line at 768 MB. That runs one browser profile comfortably, or a single headless posting setup for one or two accounts. It does not run several browser automation instances at once, and a five-account TikTok Shop livestream matrix will not fit on one box. You'd need multiple Singapore instances or a different region's higher tier. Budget for the second box rather than discovering the limit mid-stream.

## The refund window is 3 days and 10 GB

WePC's terms, as published across its policy pages and checkout: a machine provisioned within the last three days and under 10 GB of traffic can be refunded. To account credit the refund is full; to the original payment method or a nominated account it's minus a CNY 10 processing fee per machine. Between day three and day ten the remainder goes back to credit with 6% deducted per day used. After ten days there is nothing. Refunds are capped at three per day and five per month, top-ups are non-refundable, and the checkout terms are what actually bind — discounted plans are often excluded.

Ten gigabytes is not a stress test. It is enough to confirm the IP resolves to your target country inside TikTok, publish one video, and run one short livestream while watching whether the stream gets pushed or buried. Do that in the first 48 hours, not the third day, and keep the traffic low enough to leave room.

👉 [Start a Singapore plan and test the IP inside the refund window](https://wepc.au/aff.php?aff=300)

## How the alternatives compare

VPS Mart sells US TikTok VPS with a dedicated static native IP, Windows images for account management workflows, GPU plans for Android emulator streaming, bandwidth up to 1 Gbps and a 1-day free trial. It publishes no plan prices or configurations on its TikTok page, so you can't compare cost without going through checkout. Its own FAQ is honest about the legal question: using a VPS for TikTok is fine, the risk comes from breaking platform terms.

Server Gigabit lists four TikTok VPS tiers — 1 GB/1 vCPU/20 GB up to 8 GB/8 vCPU/160 GB — all unmetered on 100 Mbps shared bandwidth with one IP, Lite Management and free SSL, 99.95% uptime claimed. No prices either, and the page is dated April 2024.

HostKey, iShosting and No-Ack sell Bangkok datacenter VPS around USD 2 to 5 a month. Those are IDC IPs. They are fine for a website or a bot that doesn't care about IP reputation and useless for the thing you're actually buying here.

What separates WePC from that group is disclosure: the IP tier is printed per plan instead of appearing at checkout. What it lacks is headroom, published renewal pricing, and any trial shorter than the 3-day refund.

## When a cheap datacenter VPS is the right buy

If the server is for a landing page, a scraper, a bot, a mirror, or anything that isn't logging into a social account, buy the USD 3 box. IP reputation is irrelevant to that workload and WePC's pricing is not built for it. The same applies if you need 4+ GB of RAM to run emulators or several browser profiles at once: this lineup will not get you there at any price.

## Which plan to order

- **Posting, warmup, or occasional short lives into Southeast Asia** → Singapore native IP, AUD 14.90 to 16.90 list, `WePCMON90` if you're month to month.
- **Sustained livestreaming, aged accounts, multiple profiles** → Singapore residential, AUD 24.90, `WePCYEAR80` at about AUD 19.92/month equivalent.
- **US audience on China Telecom** → the Los Angeles 9929 residential line at AUD 15.90 with `WePC9929MON85` or `WePC9929YEAR70`.
- **No relay, no configuration hassle** → Japan or Korea Residential, both direct from the mainland.
- **Testing whether a region works at all before spending on residential** → any native plan, used inside the first 48 hours.

Before you pay, open the cart and confirm four things: the final AUD total (the CNY figure uses a cart rate, not the market rate), live stock on the residential SKU, whether your province needs the AUD 19.90 relay hop, and the refund wording shown at checkout for the plan you picked.

👉 [Compare the current WePC TikTok VPS plans and start with the Singapore line](https://wepc.au/aff.php?aff=300)

# BandwagonHost Restock Always Missed? How to Catch Limited Edition Plans Before They Sell Out — Notification Channels, Stock Monitoring, Full Plan Pricing Compared, and Which VPS to Grab (With Latest Promo Codes)

Anyone who has hovered over the "Order" button on a freshly restocked BandwagonHost limited edition plan knows the feeling. The page loads, the plan is there, you reach for your card — and by the time the checkout form opens, the stock counter has already hit zero. That is the BandwagonHost restock experience in a nutshell, and it is not a glitch. It is the reality of a provider that runs lean inventory on premium CN2 GIA routes and sells them at prices the Asian-market VPS crowd considers a steal.

This guide is for the person who keeps missing the restock. We are going to talk about why these plans disappear so fast, which notification channels actually work, what the limited edition plans look like, and — most importantly — the full BandwagonHost plan catalog with pricing so you can decide in advance which VPS to grab the second stock comes back. We will also fold in the latest promo codes and the recent hardware updates that change the restock calculus.

## Why BandwagonHost Restocks Sell Out in Minutes

There is no mystery here, but there is a mechanism worth understanding. BandwagonHost (sometimes written as BWH, and known to its Chinese user base as 搬瓦工) sells a small number of premium-network VPS plans that ride on China Telecom's CN2 GIA and CN2 GIA-E backbone routes, plus CN2 GIA into Hong Kong, Tokyo, Osaka, and Singapore. These routes are genuinely scarce at the datacenter level — the upstream capacity is finite, and the price per megabit is high. So BandwagonHost does not over-provision.

When a limited edition plan like MINICHICKEN ($19/year on Fremont HE) or BiggerBox Pro ($39/year on DC1 with CN2 GIA + CMIN2) gets restocked, the inventory is typically a few hundred units. The notification goes out on Telegram, the stock page at the official monitoring site flips to "in stock", and a few hundred people who have been waiting for exactly that configuration all click at the same time. The window is often under ten minutes. For the most popular CN2 GIA-E configurations it can be shorter.

> The plans are not "limited" as a marketing trick. The underlying transit is limited. That is why the restock rhythm exists and why waiting for one is a real strategy, not a gimmick.

The practical takeaway: if you want a specific limited edition plan, you need to be on a notification channel and you need to have your account already registered and payment method ready. Thinking about it during the restock is already too late.

## How to Actually Catch a BandwagonHost Restock

There are a handful of notification channels, and they are not equally fast. Here is the order of responsiveness, based on what the community has converged on:

1. **Telegram channels.** The fastest path. BandwagonHost-adjacent news channels typically push a restock message within minutes of inventory appearing. The official newsroom also posts to its news feed, and community aggregators relay quickly. If you only set up one channel, make it Telegram.
2. **The official stock monitoring page.** This is the community-maintained stock tracker that aggregates every plan's in-stock / out-of-stock status across KVM, CN2, CN2 GIA-E, Hong Kong, Japan, and Singapore lines. Bookmark it and refresh during known restock windows.
3. **The BandwagonHost news page.** The official news section posts hardware updates, new node launches, and partnership announcements. It is not a restock alert per se, but it tells you when new capacity is coming online — which is usually a precursor to a restock. Recent examples: AMD EPYC NVMe RAID-10 servers went live in New York (USNY_6, USNY_8), in Hong Kong (HK3, HK8), and in Los Angeles DC9.
4. **Community forums and aggregator sites.** Slower than Telegram, but useful for context — what people are buying, what they are paying, and whether a given restock is worth chasing.

The honest advice: layer at least two of these. Telegram for speed, the stock page for confirmation. Relying on refreshing the order page yourself is the slowest possible method and is why most people miss restocks.

## Limited Edition Plans That Disappear Fast

These are the plans that create the restock frenzy. They are not always available — that is the whole point — so the table below reflects what has been restocked recently and what to watch for next. When a plan is out of stock, the linked AFF order page will show the current availability status.

| Plan | Config | Route / Datacenter | Price | Stock Pattern | Order |
| --- | --- | --- | --- | --- | --- |
| MINICHICKEN | 1 vCPU, 1 GB RAM, 20 GB SSD, 1 TB transfer, 1 Gbps | Fremont HE | $19/year | Sells out within minutes of restock | [Check MINICHICKEN](https://bit.ly/BandwagonHost) |
| BiggerBox Pro | 1 AMD vCPU, 1 GB RAM, 20 GB SSD, 1 TB transfer, 2.5 Gbps | DC1 CN2 GIA + CMIN2 | $39/year | Sells out fast, restocked multiple times | [Check BiggerBox Pro](https://bit.ly/BandwagonHost) |
| The DC9 Plan | 1 vCPU, 768 MB RAM, 15 GB SSD, 750 GB transfer, 1.5 Gbps | DC9 CN2 GIA | $38/year (promo) | Periodic restock, popular with low-budget buyers | [Check DC9 Plan](https://bit.ly/BandwagonHost) |

These three are the ones the community talks about most. MINICHICKEN is the cheapest entry point but rides a non-CN2 HE line, so it is best for light, non-latency-critical workloads. BiggerBox Pro is the sweet spot — a CN2 GIA + CMIN2 route at $39/year is genuinely hard to find elsewhere. The DC9 Plan is the budget CN2 GIA option when it is in stock.

> If you only have time to chase one restock, chase BiggerBox Pro. The route quality at that price is the reason it sells out first.

For these limited edition plans, dedicated product IDs are not published in the standard catalog, so the links above point to the AFF landing page where current availability is shown.

## BandwagonHost Regular Plan Catalog: Always Available vs. Scarce

Not every BandwagonHost plan is a restock chase. The standard KVM VPS line is generally in stock, and the CN2 GIA-E, Hong Kong, Japan, Singapore, and Dubai lines sit somewhere in between — usually orderable, but the lower-tier configurations can dip in and out of stock during demand spikes.

What follows is the complete plan catalog as currently listed, grouped by line, with the AFF-linked order page for each individual plan. Every plan below has its own product ID, so each link points to that specific plan's checkout rather than a generic landing page.

## Standard KVM VPS Plans (Multiple Locations)

These are the workhorse plans. Multiple US and EU datacenters, 1 Gbps uplink, no CN2 routing. Best for non-Asia-traffic workloads, development boxes, and users who do not need the premium routing.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Locations | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 20G KVM | 1 GB | 2 | 20 GB | 1 TB/mo | 1 Gbps | DC2 AO, DC4 MCOM, DC8 ZNET, FMT, USNJ, USNY_2, USNY_6, CABC_1, EUNL_3 | $49.99/year | [Order 20G KVM](https://bwh81.net/aff.php?aff=79616&pid=44) |
| 40G KVM | 2 GB | 3 | 40 GB | 2 TB/mo | 1 Gbps | Same as above | $52.99/half year or $99.99/year | [Order 40G KVM](https://bwh81.net/aff.php?aff=79616&pid=45) |
| 80G KVM | 4 GB | 4 | 80 GB | 3 TB/mo | 1 Gbps | Same as above | $19.99/mo or $199.99/year | [Order 80G KVM](https://bwh81.net/aff.php?aff=79616&pid=46) |
| 160G KVM | 8 GB | 5 | 160 GB | 4 TB/mo | 1 Gbps | Same as above | $39.99/mo or $399.99/year | [Order 160G KVM](https://bwh81.net/aff.php?aff=79616&pid=47) |
| 320G KVM | 16 GB | 6 | 320 GB | 5 TB/mo | 1 Gbps | Same as above | $79.99/mo or $799.99/year | [Order 320G KVM](https://bwh81.net/aff.php?aff=79616&pid=48) |
| 480G KVM | 24 GB | 7 | 480 GB | 6 TB/mo | 1 Gbps | Same as above | $119.99/mo or $1199.99/year | [Order 480G KVM](https://bwh81.net/aff.php?aff=79616&pid=49) |

If you are not chasing a CN2 restock and just want a solid KVM box, the 20G at $49.99/year is the cheapest real entry point and is usually in stock.

## CN2 GIA-E Plans (Los Angeles DC6 / DC9, Plus Free Migration)

This is the line most restock hunters are actually after. CN2 GIA-E (the Ecommerce tier) rides China Telecom's premium GIA backbone into Los Angeles DC6 and DC9, with free migration to JPOS_1 (Japan), EUNL_9 (Netherlands), DC3 CN2, DC8 ZNET, and a long list of standard US/EU datacenters. Uplink steps from 2.5 Gbps at the low end up to 10 Gbps at the top.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CN2 GIA-E 20G | 1 GB | 2 | 20 GB | 1 TB/mo | 2.5 Gbps | $49.99/quarter or $169.99/year | [Order CN2 GIA-E 20G](https://bwh81.net/aff.php?aff=79616&pid=87) |
| CN2 GIA-E 40G | 2 GB | 3 | 40 GB | 2 TB/mo | 2.5 Gbps | $89.99/quarter or $299.99/year | [Order CN2 GIA-E 40G](https://bwh81.net/aff.php?aff=79616&pid=88) |
| CN2 GIA-E 80G | 4 GB | 4 | 80 GB | 3 TB/mo | 2.5 Gbps | $56.99/mo or $549.99/year | [Order CN2 GIA-E 80G](https://bwh81.net/aff.php?aff=79616&pid=89) |
| CN2 GIA-E 160G | 8 GB | 6 | 160 GB | 5 TB/mo | 5 Gbps | $86.99/mo or $879.99/year | [Order CN2 GIA-E 160G](https://bwh81.net/aff.php?aff=79616&pid=90) |
| CN2 GIA-E 320G | 16 GB | 8 | 320 GB | 8 TB/mo | 5 Gbps | $159.99/mo or $1599.99/year | [Order CN2 GIA-E 320G](https://bwh81.net/aff.php?aff=79616&pid=91) |
| CN2 GIA-E 640G | 32 GB | 10 | 640 GB | 10 TB/mo | 10 Gbps | $289.99/mo or $2759.99/year | [Order CN2 GIA-E 640G](https://bwh81.net/aff.php?aff=79616&pid=92) |
| CN2 GIA-E 1280G | 64 GB | 12 | 1280 GB | 12 TB/mo | 10 Gbps | $549.99/mo or $5399.99/year | [Order CN2 GIA-E 1280G](https://bwh81.net/aff.php?aff=79616&pid=93) |

The 20G at $49.99/quarter is the most-restock-watched plan in BandwagonHost's entire catalog. It is the cheapest legitimate CN2 GIA-E entry, and when stock dips, this is the one people refresh for.

## Singapore CN2 GIA Plans

Singapore on CN2 GIA. Useful for users who want lower latency to Southeast Asia and southern China without going through Hong Kong or Tokyo.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Singapore 40G | 2 GB | 2 | 40 GB | 0.5 TB/mo | 1.5 Gbps | $49.99/quarter or $499.99/year | [Order SG 40G](https://bwh81.net/aff.php?aff=79616&pid=173) |
| Singapore 80G | 4 GB | 4 | 80 GB | 1 TB/mo | 1.5 Gbps | $86.99/quarter or $869.99/year | [Order SG 80G](https://bwh81.net/aff.php?aff=79616&pid=174) |
| Singapore 160G | 8 GB | 6 | 160 GB | 2 TB/mo | 2.5 Gbps | $165.99/mo or $1665.99/year | [Order SG 160G](https://bwh81.net/aff.php?aff=79616&pid=175) |
| Singapore 320G | 16 GB | 8 | 320 GB | 4 TB/mo | 2.5 Gbps | $329.99/mo or $3199.99/year | [Order SG 320G](https://bwh81.net/aff.php?aff=79616&pid=176) |
| Singapore 640G | 32 GB | 10 | 640 GB | 6 TB/mo | 5 Gbps | $549.99/mo or $5549.99/year | [Order SG 640G](https://bwh81.net/aff.php?aff=79616&pid=177) |
| Singapore 1280G | 64 GB | 12 | 1280 GB | 8 TB/mo | 5 Gbps | $1059.99/mo or $10559.99/year | [Order SG 1280G](https://bwh81.net/aff.php?aff=79616&pid=178) |

## Osaka CN2 GIA Plans

Osaka on CN2 GIA, 1.5 Gbps across the board. A middle-ground Japan option — less expensive than Tokyo, slightly higher latency than Tokyo for some routes, but solid for Japan-anchored workloads.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Osaka 40G | 2 GB | 2 | 40 GB | 0.5 TB/mo | 1.5 Gbps | $49.99/quarter or $499.99/year | [Order Osaka 40G](https://bwh81.net/aff.php?aff=79616&pid=134) |
| Osaka 80G | 4 GB | 4 | 80 GB | 1 TB/mo | 1.5 Gbps | $86.99/quarter or $869.99/year | [Order Osaka 80G](https://bwh81.net/aff.php?aff=79616&pid=135) |
| Osaka 160G | 8 GB | 6 | 160 GB | 2 TB/mo | 1.5 Gbps | $165.99/mo or $1665.99/year | [Order Osaka 160G](https://bwh81.net/aff.php?aff=79616&pid=136) |
| Osaka 320G | 16 GB | 8 | 320 GB | 4 TB/mo | 1.5 Gbps | $329.99/mo or $3279.99/year | [Order Osaka 320G](https://bwh81.net/aff.php?aff=79616&pid=137) |
| Osaka 640G | 32 GB | 10 | 640 GB | 6 TB/mo | 1.5 Gbps | $549.99/mo or $5549.99/year | [Order Osaka 640G](https://bwh81.net/aff.php?aff=79616&pid=138) |
| Osaka 1280G | 64 GB | 12 | 1280 GB | 8 TB/mo | 1.5 Gbps | $1059.99/mo or $10559.99/year | [Order Osaka 1280G](https://bwh81.net/aff.php?aff=79616&pid=139) |

## Tokyo CN2 GIA Plans

Tokyo on CN2 GIA, 1.2 Gbps. The premium Japan option — lowest latency into East China and the choice when Osaka is not enough. Pricier than Osaka across the board.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Tokyo 40G | 2 GB | 2 | 40 GB | 0.5 TB/mo | 1.2 Gbps | $89.99/quarter or $899.99/year | [Order Tokyo 40G](https://bwh81.net/aff.php?aff=79616&pid=108) |
| Tokyo 80G | 4 GB | 4 | 80 GB | 1 TB/mo | 1.2 Gbps | $155.99/quarter or $1559.99/year | [Order Tokyo 80G](https://bwh81.net/aff.php?aff=79616&pid=109) |
| Tokyo 160G | 8 GB | 6 | 160 GB | 2 TB/mo | 1.2 Gbps | $299.99/mo or $2999.99/year | [Order Tokyo 160G](https://bwh81.net/aff.php?aff=79616&pid=110) |
| Tokyo 320G | 16 GB | 8 | 320 GB | 4 TB/mo | 1.2 Gbps | $589.99/mo or $5899.99/year | [Order Tokyo 320G](https://bwh81.net/aff.php?aff=79616&pid=111) |
| Tokyo 640G | 32 GB | 10 | 640 GB | 6 TB/mo | 1.2 Gbps | $989.99/mo or $9989.99/year | [Order Tokyo 640G](https://bwh81.net/aff.php?aff=79616&pid=123) |
| Tokyo 1280G | 64 GB | 12 | 1280 GB | 8 TB/mo | 1.2 Gbps | $1889.99/mo or $18989.99/year | [Order Tokyo 1280G](https://bwh81.net/aff.php?aff=79616&pid=125) |

## Hong Kong CN2 GIA Plans

Hong Kong on CN2 GIA, 1 Gbps. The lowest-latency option for southern China and a status symbol in the community. Hong Kong capacity is the scarcest of all the lines, so restocks here, when they happen, vanish fastest.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HK 40G | 2 GB | 2 | 40 GB | 0.5 TB/mo | 1 Gbps | $89.99/quarter or $899.99/year | [Order HK 40G](https://bwh81.net/aff.php?aff=79616&pid=95) |
| HK 80G | 4 GB | 4 | 80 GB | 1 TB/mo | 1 Gbps | $155.99/quarter or $1559.99/year | [Order HK 80G](https://bwh81.net/aff.php?aff=79616&pid=96) |
| HK 160G | 8 GB | 6 | 160 GB | 2 TB/mo | 1 Gbps | $299.99/mo or $2999.99/year | [Order HK 160G](https://bwh81.net/aff.php?aff=79616&pid=97) |
| HK 320G | 16 GB | 8 | 320 GB | 4 TB/mo | 1 Gbps | $589.99/mo or $5899.99/year | [Order HK 320G](https://bwh81.net/aff.php?aff=79616&pid=98) |
| HK 640G | 32 GB | 10 | 640 GB | 6 TB/mo | 1 Gbps | $989.99/mo or $9989.99/year | [Order HK 640G](https://bwh81.net/aff.php?aff=79616&pid=122) |
| HK 1280G | 64 GB | 12 | 1280 GB | 8 TB/mo | 1 Gbps | $1889.99/mo or $18989.99/year | [Order HK 1280G](https://bwh81.net/aff.php?aff=79616&pid=124) |

## Dubai Ecommerce Plans

A newer line — Dubai with free migration to CN2 GIA-E (DC6, DC9), JPOS_1, EUNL_9, DC3 CN2, DC8 ZNET, and the full standard US/EU datacenter list. Useful as a Middle East anchor or as a back door into the CN2 GIA-E network at a slightly different price ladder.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Dubai 20G | 1 GB | 2 | 20 GB | 0.5 TB/mo | 1 Gbps | $19.99/mo or $169.99/year | [Order Dubai 20G](https://bwh81.net/aff.php?aff=79616&pid=114) |
| Dubai 40G | 2 GB | 3 | 40 GB | 1 TB/mo | 1 Gbps | $32.99/mo or $299.99/year | [Order Dubai 40G](https://bwh81.net/aff.php?aff=79616&pid=115) |
| Dubai 80G | 4 GB | 4 | 80 GB | 2 TB/mo | 1 Gbps | $56.99/mo or $549.99/year | [Order Dubai 80G](https://bwh81.net/aff.php?aff=79616&pid=116) |
| Dubai 160G | 8 GB | 6 | 160 GB | 3 TB/mo | 1 Gbps | $86.99/mo or $879.99/year | [Order Dubai 160G](https://bwh81.net/aff.php?aff=79616&pid=117) |
| Dubai 320G | 16 GB | 8 | 320 GB | 4 TB/mo | 1 Gbps | $159.99/mo or $1599.99/year | [Order Dubai 320G](https://bwh81.net/aff.php?aff=79616&pid=118) |
| Dubai 640G | 32 GB | 10 | 640 GB | 5 TB/mo | 1 Gbps | $289.99/mo or $2759.99/year | [Order Dubai 640G](https://bwh81.net/aff.php?aff=79616&pid=119) |
| Dubai 1280G | 64 GB | 12 | 1280 GB | 6 TB/mo | 1 Gbps | $549.99/mo or $5399.99/year | [Order Dubai 1280G](https://bwh81.net/aff.php?aff=79616&pid=120) |

## SLA Plans (DC5, 99.99% Uptime, Premium IP)

A distinct line on DC5 with a 99.99% SLA and premium IP addresses, 2.5 Gbps uplink, and free migration across the CN2 GIA-E and standard datacenter list. For workloads where uptime guarantees matter more than shaving a few dollars off the bill.

| Plan | RAM | vCPU | SSD | Transfer | Uplink | Price | Order |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLA 20G | 1 GB | 2 | 20 GB | 1 TB/mo | 2.5 Gbps | $65.89/quarter or $239.99/year | [Order SLA 20G](https://bwh81.net/aff.php?aff=79616&pid=164) |
| SLA 40G | 2 GB | 3 | 40 GB | 2 TB/mo | 2.5 Gbps | $116.99/quarter or $399.99/year | [Order SLA 40G](https://bwh81.net/aff.php?aff=79616&pid=165) |

## Current Promo Codes Worth Applying

Promo codes at BandwagonHost come and go, and the ones that look the best do not always last. Here is the current state, verified against the most recent aggregator updates.

| Code | Discount | Status | Notes |
| --- | --- | --- | --- |
| BWHCGLUKKB | 6.77% recurring | Live | Currently the strongest widely-available code; applies to standard plans |
| BWH1ZBPVK | 6% | Live | Solid fallback if the above is rejected |
| BWH1XZOBK | 5.5% | Live | Alternative lower-tier code |
| ireallyreadtheterms8 | 5.5% | Live | Long-standing community code |
| BWH1NJJHL | 4.5% | Live | Lower discount, kept as a backup |
| ireadtheterms8 | 4.4% | Live | Lower discount, kept as a backup |
| NODESEEK2026 | 6.77% recurring | Expired | Was live briefly; no longer working — listed so you do not waste time trying it |

A couple of honest notes. The 6.77% recurring discount sounds small, but it compounds across the billing cycle and is genuinely recurring — it stays applied on renewals, which is where the real saving shows up over a year or two. The bigger event-driven codes (Black Friday, Double Eleven) historically beat these, but they only appear during those windows. If you are buying now, apply BWHCGLUKKB and move on.

> Do not waste checkout time trying expired codes. NODESEEK2026 had a short run and is gone — if you see it referenced in older posts, it no longer works.

## Which Plan Should You Grab When It Restocks?

This is the question that matters, and the answer depends on what you are actually doing with the box. A few decision paths:

**You want the cheapest possible CN2 GIA-E entry.** Wait for the CN2 GIA-E 20G restock at $49.99/quarter (pid 87). It is the lowest rung on the premium ladder and the one most worth refreshing for. Apply BWHCGLUKKB at checkout. 👉 [Order CN2 GIA-E 20G](https://bwh81.net/aff.php?aff=79616&pid=87)

**You want the cheapest possible plan, full stop, and do not care about routing.** Either grab the 20G KVM at $49.99/year (pid 44) — usually in stock — or wait for a MINICHICKEN restock at $19/year if you can catch it. The KVM plan is the safer bet because you do not have to wait. 👉 [Order 20G KVM](https://bwh81.net/aff.php?aff=79616&pid=44)

**You want a CN2 GIA-E plan that you will not outgrow in a year.** Skip the 20G and go straight to the 40G at $89.99/quarter or $299.99/year (pid 88). The doubled RAM and transfer cover most personal and small-business workloads, and you avoid the upgrade-restock dance later. 👉 [Order CN2 GIA-E 40G](https://bwh81.net/aff.php?aff=79616&pid=88)

**You need lowest latency into southern China.** Hong Kong 40G (pid 95) is the answer, and you should be on the Telegram alert the moment HK stock returns — Hong Kong restocks are the rarest of all. 👉 [Order HK 40G](https://bwh81.net/aff.php?aff=79616&pid=95)

**You need a guaranteed uptime SLA.** Skip the restock chase entirely and take the SLA 20G (pid 164) on DC5. The 99.99% SLA and premium IP cost more, but you are paying for predictability, not for hunting. 👉 [Order SLA 20G](https://bwh81.net/aff.php?aff=79616&pid=164)

**You want a Middle East presence with CN2 GIA-E migration rights.** Dubai 20G (pid 114) at $19.99/month is the cheapest Dubai entry and gives you the same migration network as the CN2 GIA-E line. 👉 [Order Dubai 20G](https://bwh81.net/aff.php?aff=79616&pid=114)

## Recent Hardware and Network Updates That Affect Restocks

Restock patterns are not random — they track hardware deployments. When BandwagonHost lights up new nodes, capacity follows. The official news page is the leading indicator. The most recent updates worth knowing about:

- **AMD EPYC servers with NVMe RAID-10 storage went live in Los Angeles DC9 (USCA_9).** This is the same datacenter that hosts the DC9 CN2 GIA line, so new DC9 capacity is the most likely restock candidate in the near term. If you have been waiting on a DC9 CN2 GIA-E plan, watch the alerts closely.
- **AMD EPYC NVMe RAID-10 servers also went live in Hong Kong (HK3 and HK8).** Hong Kong is the tightest-inventory line in the catalog, so any new node deployment there is significant. A Hong Kong restock after this rollout is plausible.
- **New hardware live in New York (USNY_6 and USNY_8).** Affects the standard KVM line, not the CN2 lines, but it means New York KVM capacity is healthy and unlikely to be a restock bottleneck.
- **Ubuntu 26.04 and Debian 13 added to KiwiVM.** OS template updates — not a restock event, but worth knowing if you want a modern base image on a freshly deployed box.

The pattern to internalize: watch the news page for node deployments on the line you care about, then watch the Telegram and stock channels for the restock that follows. Hardware first, restock second.

## A Few Things That Are Not Worth Doing

Some common restock-chasing behaviors waste time. Worth naming them:

- **Refreshing the order page manually.** Too slow. By the time you see stock, hundreds of people on Telegram already saw it.
- **Stockpiling accounts.** One account is enough. The bottleneck is speed of checkout, not number of accounts.
- **Waiting for a "better" promo code before buying a plan you actually need.** The 6.77% recurring code is fine. The marginal saving from holding out for a rare event code is usually smaller than the months of usage you lose waiting.
- **Buying a limited edition plan you do not need just because it restocked.** FOMO is real, but a $19/year MINICHICKEN on HE routing is not a substitute for a CN2 GIA-E box if CN2 GIA-E is what your workload actually needs.

## The Short Version

BandwagonHost restocks sell out fast because the underlying CN2 GIA and CN2 GIA-E transit is genuinely scarce, not because of artificial scarcity. To catch one, get on Telegram alerts and the stock monitoring page, know which plan you want before the restock happens, have your account and payment ready, and apply BWHCGLUKKB at checkout for the 6.77% recurring discount. The CN2 GIA-E 20G (pid 87) is the plan most worth waiting for; Hong Kong 40G (pid 95) is the rarest; BiggerBox Pro is the limited edition worth chasing when it appears. Watch the official news page for new node deployments — DC9 and Hong Kong just got fresh AMD EPYC hardware, which is the leading indicator that restocks on those lines are coming.

If you already know which line you want, the per-plan AFF order links in the tables above take you straight to that plan's checkout, so you do not have to navigate the catalog mid-restock. Pick the plan now, bookmark its order link, and when the alert fires, you click once.

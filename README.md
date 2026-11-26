# US West VPS: What Do SixtyNet's Los Angeles Plans Cost, Which Plan Fits a Small Production App, and When Are Residential IPs the Wrong Choice? (Full Table With Monthly Equivalents)

SixtyNet's cheapest LAX plan is the LAX-STARTER at **$200 per year**, about **$16.67 per month**. Most small production workloads should start one tier up: LAX-MICRO costs **$400 per year**, about **$33.33 per month**, and doubles the RAM to 4 GB, the vCPU count to 4, the NVMe storage to 80 GB and the traffic allowance to 10 TB. The prices are annual, in USD, and the monthly figures are arithmetic, not a month-to-month billing option.

SixtyNet's US West VPS page is not a generic cheap-LA menu. It mixes standard LAX plans, residential-IP plans with ports 80 and 443 closed, Irvine plans with AS9929 China routing, and a China Unicom bandwidth product. The plan you pick depends on which of those you actually need.

> **Quick pick:** For a small app or API, **LAX-MICRO at $400/year (≈$33.33/mo)** is the sensible default. For a control panel, test box or single low-traffic service, **LAX-STARTER at $200/year (≈$16.67/mo)** is enough. Skip the residential plans unless you specifically need a US residential IP and can work without ports 80 and 443. 👉 [See all SixtyNet VPS plans and annual prices](https://sixtynet.net/aff.php?aff=39)

## What does a US West VPS cost at SixtyNet?

All prices below are USD and annual. “List” is the higher price shown next to the discount. Monthly equivalents are annual ÷ 12. The page does not show a monthly billing option for these plans.

| Plan | vCPU / RAM / NVMe | Network and traffic | Annual price (USD) | Order |
| --- | --- | --- | --- | --- |
| LAX-STARTER | 2 cores / 2 GB / 40 GB, 12,500 IOPS | 2G premium network, 5 TB, DDoS protection | $240 list → **$200/yr** (≈$16.67/mo) | [Order LAX-STARTER](https://sixtynet.net/aff.php?aff=39) |
| LAX-MICRO | 4 cores / 4 GB / 80 GB, 12,500 IOPS | 4G premium network, 10 TB, DDoS protection | $480 list → **$400/yr** (≈$33.33/mo) | [Order LAX-MICRO](https://sixtynet.net/aff.php?aff=39) |
| LAX-MEDIUM | 8 cores / 8 GB / 160 GB, 25,000 IOPS | 10G premium network, 20 TB, DDoS protection | $960 list → **$800/yr** (≈$66.67/mo) | [Order LAX-MEDIUM](https://sixtynet.net/aff.php?aff=39) |
| LAX-LARGE | 8 cores / 16 GB / 320 GB, 25,000 IOPS | 10G premium network, 40 TB, DDoS protection | $1,920 list → **$1,600/yr** (≈$133.33/mo) | [Order LAX-LARGE](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage-500G | 4 cores / 4 GB / 300 GB + 200 GB bonus RAID 10, 12,500 IOPS | 10G premium network, 10 TB, DDoS protection | $480 list → **$400/yr** (≈$33.33/mo) | [Order LAX-Storage-500G](https://sixtynet.net/aff.php?aff=39) |
| Residential-STARTER | 2 cores / 2 GB / 40 GB, 12,500 IOPS | 2G premium network, 5 TB, residential IP, 80/443 closed | $300 list → **$260/yr** (≈$21.67/mo) | [Order Residential-STARTER](https://sixtynet.net/aff.php?aff=39) |
| Residential-MICRO | 4 cores / 4 GB / 80 GB, 12,500 IOPS | 4G premium network, 10 TB, residential IP, 80/443 closed | $540 list → **$460/yr** (≈$38.33/mo) | [Order Residential-MICRO](https://sixtynet.net/aff.php?aff=39) |
| Residential-MEDIUM | 8 cores / 8 GB / 160 GB, 25,000 IOPS | 10G premium network, 20 TB, residential IP, 80/443 closed | $1,020 list → **$860/yr** (≈$71.67/mo) | [Order Residential-MEDIUM](https://sixtynet.net/aff.php?aff=39) |
| Residential-LARGE | 16 cores / 16 GB / 320 GB, 25,000 IOPS | 10G premium network, 40 TB, residential IP, 80/443 closed | $1,980 list → **$1,660/yr** (≈$138.33/mo) | [Order Residential-LARGE](https://sixtynet.net/aff.php?aff=39) |
| IRVINE-PRO-STARTER | 2 cores / 2 GB / 40 GB, 12,500 IOPS | 2G premium network, AS9929 China optimization, 5 TB, residential IP, restricted access | $420 list → **$350/yr** (≈$29.17/mo) | [Order IRVINE-PRO-STARTER](https://sixtynet.net/aff.php?aff=39) |
| IRVINE-PRO-MICRO | 4 cores / 4 GB / 80 GB, 12,500 IOPS | 4G premium network, AS9929 China optimization, 10 TB, residential IP, restricted access | $660 list → **$550/yr** (≈$45.83/mo) | [Order IRVINE-PRO-MICRO](https://sixtynet.net/aff.php?aff=39) |

The page also lists a larger LAX storage configuration with 8 cores, 8 GB RAM, 700 GB plus 300 GB bonus RAID 10 and 15 TB traffic. The price block for that configuration was incomplete in the page text I verified, so confirm the current annual price before comparing it with LAX-Storage-500G.

The Los Angeles China Unicom-Premium plan is priced separately because it is not a normal app VPS:

| Plan | What the page lists | Annual price (USD) | Order |
| --- | --- | --- | --- |
| Los Angeles China Unicom-Premium | China Unicom Premium AS9929, free BGP session, limited BGP technical support, 100M basic network, 3x burst rate, 95th-percentile billing | $3,000 list → **$2,500/yr** (≈$208.33/mo) | [Order China Unicom-Premium](https://sixtynet.net/aff.php?aff=39) |

That plan does not list vCPU, RAM or storage in the same block as the LAX plans. Treat it as a bandwidth and routing product. If you do not need BGP or 95th-percentile billing, it is the wrong plan.

## What the “Save 17%” badge actually means

SixtyNet's “Save 17%” badge compares the annual price with a higher list price on the same page, not with a monthly rate. LAX-STARTER shows $240 list and $200 annual. If you keep the server for one year, you pay $200. If you leave after three months, you still pay $200, because no monthly rate is shown. The annual commitment is the real decision, not the discount badge.

For a second year, the page does not publish a separate renewal price. Ask support whether the annual price stays at $200 or returns to $240. On a two-year view, the difference between those two outcomes is $40 on the smallest plan and $320 on LAX-LARGE. Get that answer in writing before you pay.

Competitor pricing uses the same badge logic. Cloudzy's Los Angeles page shows 50% off and displays both the promotional and list prices, so its $2.48/mo entry is a promotional rate against $4.95. VeloxMedia gives two months free on annual billing, about 16.7%. SixtyNet's 17% is in the same range. Budget the list or renewal price, not the badge.

## US West VPS location: Los Angeles, Irvine, or Phoenix?

SixtyNet uses two California labels. LAX is the airport code for Los Angeles, and the China Unicom Premium plan is explicitly named Los Angeles. Irvine is in Orange County, south of Los Angeles. The residential plans do not name a city. The page does not give a street address or a region code, so if you need a specific building or carrier hotel, ask support before ordering.

Phoenix is the other kind of US West. Liquid Web's USA VPS page, dated March 31, 2025, places its western US VPS in Phoenix, Arizona, and markets it for the western US and Central America. Phoenix is inland. For Asia-Pacific traffic, Los Angeles is the more direct coast. Do not compare a Phoenix quote with an LA quote as if they were the same location.

SixtyNet does not publish latency figures for its LAX plans. Vendor claims from other Los Angeles providers give a rough range. BrainHost says 1 to 5 ms to California, Oregon, Washington, Nevada and Arizona, 67 ms to the US East Coast and 112 to 160 ms to Asia. NetGrid says 5.0 ms regional latency. Cloudzy says single-digit milliseconds to Los Angeles peering. These are self-reported and use different test methods. They are useful for judging location, not for ranking providers.

Los Angeles fits West Coast and Asia-Pacific traffic. It is the wrong choice for a user base in Europe or the US East Coast. BrainHost's own 67 ms figure for LA to the East Coast shows the penalty. If most of your users are in New York or London, a US West VPS is the wrong product category.

## The US West VPS details that change the decision

SixtyNet's LAX plans list 2G, 4G and 10G “Premium Network”. The page does not define whether those are dedicated port speeds, shared uplinks or a network tier. Ask. Traffic is clearer: 5 TB on LAX-STARTER, 10 TB on LAX-MICRO, 20 TB on LAX-MEDIUM and 40 TB on LAX-LARGE. There is no “unlimited” claim on the page, so you can budget egress.

Competitors publish 1 Gbps, 10 Gbps and 40 Gbps ports, which shows how wide the market range is. If you run video, game servers or a mirror, port specification matters. If you run a control panel or a small API, 2G is unlikely to be the first bottleneck. RAM and disk I/O will usually hit first.

The same logic applies to “unmetered” versus fixed traffic. VeloxMedia and NetGrid advertise unmetered or unlimited transfer on their US West plans. SixtyNet gives a fixed TB allowance. Fixed traffic is easier to budget if you know your monthly egress. “Unlimited” still has a fair-use or port limit in practice, so read the terms either way.

## Residential IPs: the plans most likely to be bought for the wrong reason

SixtyNet's residential plans look like normal VPS plans until you read the notice. The page states that residential IP products do not open ports 80 and 443 because of IP risk control. That rules out normal web hosting, HTTPS APIs and HTTP-based certificate validation. The plans still include 2 to 16 cores, 2 to 16 GB RAM, 40 to 320 GB NVMe and 5 to 40 TB traffic.

Buy them only if you need a US residential IP for outbound work. If your project needs a public website, choose a LAX plan instead. A residential IP is not a free upgrade for general hosting, and the closed ports are not a temporary promotion.

IRVINE-PRO adds AS9929 China optimization and a residential IP. It also has a stricter security model. The page says it rejects all external probes and scans, and access is restricted unless configured, with only whitelisted or port-forwarded devices allowed. Refunds are only valid on the website balance. That is a plan for someone who knows how to configure firewall rules, not a first VPS.

Is AS9929 worth it? If your users are in mainland China and you have been dealing with congested default routes, it is the reason this lineup exists. If your users are in California, a standard LAX plan is simpler and cheaper. 👉 [Check the residential and Irvine plan terms before you order](https://sixtynet.net/aff.php?aff=39)

## How SixtyNet compares on price

The market entry prices below are published prices at the time of writing, not quotes. They show the range SixtyNet is competing against.

| Provider | US West location | Published entry price | What the entry price includes | Notes |
| --- | --- | --- | --- | --- |
| Cloudzy | Los Angeles (`us-lax-1`) | $2.48/mo (50% off; list $4.95) | 40 Gbps uplink, 1 TB traffic | 99.95% SLA, 14-day money-back |
| VeloxMedia | California | $5/mo | 1 Gbps unmetered, 2 GB RAM | Annual billing gives two months free |
| BrainHost | Los Angeles | $7.99/mo | 10 Gbps port, NVMe | 99.9% SLA |
| NetGrid Host | Los Angeles | €2.98/mo | 1 Gbps port, unlimited transfer | 99.9% SLA; prices in euros |
| Liquid Web | Phoenix, Arizona | $11/mo (page dated March 31, 2025) | Cloud VPS, managed options available | SSAE-18 and HIPAA-compliant facility |

On entry price, SixtyNet's LAX-STARTER at $16.67/mo equivalent is several times Cloudzy's promotional $2.48/mo or VeloxMedia's $5/mo. A roughly like-for-like 4 GB comparison narrows the gap. Cloudzy's 4 GB plan is $14.48/mo at 50% off, or $28.95 at list. SixtyNet's 4 GB LAX-MICRO is $33.33/mo equivalent. VeloxMedia's 4 GB plan is $7/mo. SixtyNet is not the low-price option in Los Angeles.

The extra money buys three specific things: China routing on Irvine Pro and China Unicom Premium, residential IPs, and DDoS-protected LAX plans with large traffic allowances. If none of those is on your list, a cheaper Los Angeles provider is the rational choice. If one is, compare the total annual cost rather than the monthly equivalent. 👉 [Compare SixtyNet's current annual prices](https://sixtynet.net/aff.php?aff=39)

## Who should avoid SixtyNet's US West VPS

A $5/month blog should not buy these plans. The cheapest LAX plan is $200 per year, and the annual commitment is inflexible if you shut the project down in month three.

Monthly billing is another reason to look elsewhere. The page displays annual prices. No monthly rate is shown for the LAX, residential or Irvine plans.

Windows is not listed on the VPS Hosting page. If you need Windows Server, ask support before ordering. A Linux-only plan is not a good surprise after payment.

Managed support is not mentioned either. Liquid Web's USA VPS page lists managed options and starts at $11/mo on a page dated March 31, 2025. If you want someone else to handle the server, SixtyNet's self-managed plans are the wrong fit.

Finally, a European or US East Coast audience should not buy a Los Angeles VPS. The location adds round-trip time for users who are nowhere near the West Coast or Asia-Pacific routes.

## FAQ

**Is SixtyNet's LAX VPS actually in Los Angeles?**
The plan names use LAX, and the China Unicom Premium plan is explicitly named Los Angeles. The page does not publish a street address or region code. Confirm the exact facility with support if the building matters to you.

**Can I host a website on a residential plan?**
No. The page states that residential IP products do not open ports 80 and 443. That blocks normal HTTP and HTTPS websites. Use a LAX plan for public web hosting.

**What is the difference between LAX and Irvine Pro?**
LAX plans are standard DDoS-protected VPS plans with fixed traffic. Irvine Pro adds AS9929 China optimization, a residential IP and a default-deny security model with whitelisting or port forwarding. Irvine Pro refunds go to website balance only.

**Is there a monthly billing option?**
The page shows annual prices for these plans. No monthly rate is displayed. Ask support if you need a shorter billing cycle.

**Can I install Windows?**
Windows is not listed on the VPS Hosting page. Ask support before you order if Windows is a requirement.

**Do I need the China Unicom Premium plan?**
Only if you need China Unicom AS9929, a BGP session and 95th-percentile billing. It is a bandwidth and routing product, not a standard app VPS.

**What happens after the first year?**
The page does not publish a separate renewal price. Ask whether the annual price renews at the discounted rate or returns to the list price.

**Can I get a refund?**
The LAX plans do not state a refund window on the page. Irvine Pro refunds are valid only on the website balance. Do not assume a 14-day money-back guarantee.

## Pick by workload, then confirm the details

A control panel, test box or single low-traffic service → **LAX-STARTER at $200/year**. A small production app or API with 4 GB RAM → **LAX-MICRO at $400/year**. A China-facing service that needs AS9929 → **Irvine Pro**, but budget time for firewall setup and read the refund-to-balance rule. A residential IP for outbound work → **Residential-STARTER at $260/year**, never for a public website. A large storage box → **LAX-Storage-500G at $400/year**, with the larger storage configuration priced by support.

Before you pay, confirm three things in writing: the exact city or facility, whether the annual price renews at the same rate, and whether your plan allows the ports you need. Those three answers matter more than the discount badge.

👉 [Start with the LAX-MICRO plan and check the current annual price](https://sixtynet.net/aff.php?aff=39)

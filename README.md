# Best VPS hosting from $1.99 a month: JustHost's full plan list, what size your workload needs, and what "unmetered" really means

JustHost's cheapest KVM server is **$1.99 a month** for one core, 512 MB RAM and 5 GB NVMe. The plan most people should buy is **Bright Star: 4 cores, 4 GB RAM, 30 GB NVMe and a 300 Mbps port at $9.80 a month, or $7.84 a month when you pay for 12 months**. Everything between those two prices comes down to how much RAM, disk and port speed you need, and the answer is usually smaller than the pricing page implies.

Below you get the full tariff list with prices, the arithmetic behind the "unmetered traffic" claim, a workload-to-plan table, and the parts JustHost's site doesn't spell out. There is no managed tier, no published backup price and no published refund window, so those go on your pre-order checklist rather than in the marketing copy.

> **Quick pick**
> **One site, or a few small WordPress installs:** Bright Star, 4 cores / 4 GB / 30 GB NVMe, **$7.84 a month on a 12-month term**.
> **Testing, DNS, monitoring, a proxy node:** Promo, **$1.99 a month**, 512 MB / 5 GB.
> **A store or 20+ sites:** the 4 cores / 8 GB / 200 GB build at **$12.96 a month on 12 months**.
> 👉 [Compare every JustHost VPS tariff in one list](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## The full JustHost VPS lineup, priced

Every plan below is a KVM virtual server with NVMe storage. The first price is the month-to-month rate, the second is what you pay per month on a 12-month term (a flat 20% off across the range).

| Plan | Cores / RAM / NVMe | Port (fair-share) | Price (monthly → 12 months) | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 core / 512 MB / 5 GB | 10 Mbps (≈4 TB) | $1.99 | [Promo plan](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 core / 1 GB / 10 GB | 100 Mbps (≈31 TB) | $3.81 → $3.05 | [New Star plan](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 core / 1 GB / 20 GB | 300 Mbps (≈93 TB) | $4.85 → $3.88 | [Sirius plan](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 core / 2 GB / 30 GB | 300 Mbps (≈93 TB) | $6.92 → $5.53 | [Arcturus plan](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 cores / 2 GB / 20 GB | 200 Mbps (≈62 TB) | $7.08 → $5.67 | [Double Star plan](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB / 40 GB | 400 Mbps (≈124 TB) | $8.99 → $7.19 | [Alpha Centauri plan](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 cores / 4 GB / 30 GB | 300 Mbps (≈93 TB) | $9.80 → $7.84 | [Bright Star plan](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 cores / 4 GB / 80 GB | 500 Mbps (≈155 TB) | $13.44 → $10.75 | [Vega plan](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 cores / 4 GB / 120 GB | 750 Mbps (≈232 TB) | $18.30 → $14.64 | [Capella plan](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

Three notes on the table. New Star, Double Star and Bright Star require an order of at least three months; the other plans are listed with both a monthly rate and the 12-month rate. The tariff list continues past Capella with Rigel (4 cores / 8 GB / 200 GB NVMe), which you can reach from the full list. And the traffic figures in brackets assume the port runs at full speed 24 hours a day, which almost no workload does.

**Bigger builds.** JustHost's VPS landing page also carries a "Special offers" block with larger configurations:

| Build | Cores / RAM / NVMe | Port | Price (monthly → 12 months) | Order |
| --- | --- | --- | --- | --- |
| Yildun Special | 4 cores / 8 GB / 200 GB | 750 Mbps | $16.20 → $12.96 | [Yildun Special](https://justhost.asia/en/vps?ref=196392) |
| Betelgeuse Special | 6 cores / 12 GB / 400 GB | 750 Mbps | $26.40 → $21.12 | [Betelgeuse Special](https://justhost.asia/en/vps?ref=196392) |
| Altair Special | 8 cores / 24 GB / 600 GB | 750 Mbps | $47.40 → $37.92 | [Altair Special](https://justhost.asia/en/vps?ref=196392) |

**Two more product lines.** A "constructor" lets you pick HDD, SSD or NVMe at the same core/RAM/disk size, and the price difference is real:

| Build | HDD | SSD | NVMe |
| --- | --- | --- | --- |
| 1 core / 512 MB / 5 GB | $3.25 → $2.60 | $3.90 → $3.12 | $4.22 → $3.38 |
| 2 cores / 2 GB / 25 GB | $11.00 → $8.80 | $13.20 → $10.56 | $14.30 → $11.44 |
| 4 cores / 4 GB / 50 GB | $22.00 → $17.60 | $26.40 → $21.12 | $28.60 → $22.88 |

Saving $2.64 a month by taking HDD over NVMe at 4 cores / 4 GB is the kind of economy you notice again the first time the disk is the bottleneck.

There are also IPv4+IPv6 servers from $2.60 a month and **IPv6-only servers from $1.60**. The IPv6-only line is cheaper for one reason: a large share of the internet still can't reach an IPv6-only address. If you don't know why that matters for your use case, don't buy that line.

👉 [Open the VPS constructor and pick your storage type](https://justhost.asia/en/vps?ref=196392)

## What each price step actually buys

Compare neighbouring plans instead of staring at the $1.99 headline, because the steps are uneven.

Moving from New Star ($3.05 on 12 months) to Sirius ($3.88) costs 83 cents and buys 10 GB more disk plus a 300 Mbps port instead of 100 Mbps, on the same single core and 1 GB of RAM. That's the best small upgrade on the list if your bottleneck is network rather than memory.

Sirius to Arcturus ($5.53) costs $1.65 and doubles RAM to 2 GB. Arcturus to Alpha Centauri ($7.19) costs $1.66 more and adds a second core, 10 GB of disk and a 400 Mbps port. Bright Star then jumps to 4 cores and 4 GB for $7.84, but drops back to 30 GB of disk and a 300 Mbps port.

Vega ($10.75) is the odd one out in a useful way: $2.91 more than Bright Star, two fewer cores, but 80 GB of disk and a 500 Mbps port. Capella ($14.64) is $6.80 more than Bright Star for the same 4 cores and 4 GB, with 120 GB of disk and a 750 Mbps port.

**Capella is where most people start overpaying.** An extra $6.80 a month for 90 GB more disk and a faster port only pays off if you're serving large files, running a database that outgrows 30 GB, or pushing serious outbound traffic. It adds no RAM, and RAM is what a WordPress or WooCommerce install runs out of first.

## "Unmetered" is a port speed, not a data allowance

JustHost advertises "unmetered port, fair-share" with a monthly equivalent next to it: 300 Mbps ≈ 93+ TB, 500 Mbps ≈ 155+ TB, 750 Mbps ≈ 232+ TB. Those numbers assume the port is saturated every second of a 30-day month. Your site won't do that.

What constrains you in practice is the port at any given moment. 300 Mbps moves about 37 MB per second, 100 Mbps about 12 MB, and the $1.99 Promo's 10 Mbps about 1.25 MB. That last figure describes the Promo plan honestly: it suits a monitoring agent, a DNS resolver, a small proxy, a backup target or a test box. It does not serve pages to a crowd.

"Fair-share" is the second half of the caveat. You get a share of the host's bandwidth as it's available, not a dedicated line, so peak-hour throughput can sit below the advertised number.

The traffic allowance does matter in bursts. Backups, media libraries and package mirrors move tens of GB at a time: at 100 Mbps, a 20 GB transfer takes roughly half an hour.

## How much server your workload needs

Spec sizing guidance from Liquid Web's VPS comparison and HostAdvice's capacity estimates maps cleanly onto JustHost's pricing:

| What you're running | Sensible starting spec | Which JustHost plan |
| --- | --- | --- |
| One small business site or blog | 2 vCPU, 4 GB RAM | Bright Star, $7.84 on 12 months |
| 5–10 lightweight sites | 1–2 GB RAM, 1 core | Arcturus, $5.53 |
| 20–50 sites, or several WordPress installs with staging | 4 vCPU, 8 GB RAM | Yildun Special, $12.96 |
| Ecommerce with a real catalogue | 4+ vCPU, 8 GB+ | Yildun or Betelgeuse, $21.12 |
| Dev/test, CI runner, proxy, DNS | anything small | Promo $1.99 or New Star $3.05 |

Two thresholds are worth keeping in mind. HostAdvice puts the point where a site should consider moving up to a VPS at around **90,000 monthly visits**; below that, a decent shared plan is usually cheaper than the admin time a VPS costs you. And a 1–2 GB / single-core server handles roughly 5–10 lightweight sites, which is why Arcturus is enough for a freelancer with a portfolio and a few client brochure sites.

The opposite direction matters just as much. If you're still learning your way around FTP, WordPress and a control panel, an unmanaged KVM server will cost you more in lost evenings than a managed plan costs in dollars. The same applies if the site is low-traffic and non-critical.

## Monthly rate or 12 months: the only discount on the page

JustHost publishes exactly one discount: 20% for paying 12 months up front. The saving is easy to check.

- Bright Star: $9.80/month = $117.60 a year, or $7.84/month = $94.08 a year. You save $23.52.
- Double Star: $84.96 versus $68.04, a saving of $16.92.
- Vega: $161.28 versus $129.00, a saving of $32.28.
- Capella: $219.60 versus $175.68, a saving of $43.92.

Nothing on the tariff page advertises a longer lock-in, and the gap between the monthly rate and the yearly rate is 20%, not the 70–90% teaser discounts common in shared hosting. That makes the arithmetic honest, and it also means a $7.84 plan is genuinely an entry-level server: PCMag's VPS roundup puts typical plans at **$20–$100 a month**, so you're buying a small unmanaged box, not a $50 managed one at a discount.

**Check the Specials block before you order.** The same specs appear at two prices on JustHost's own site. Sirius is listed at $4.85 monthly / $3.88 on 12 months in the main tariff list, while the VPS landing page's Specials block lists Sirius Special at $2.81 / $2.25. Vega shows the same pattern: $13.44 / $10.75 in the tariff list, $7.79 / $6.23 as Vega Special. Vega Special is the standout: 2 cores, 4 GB RAM, 80 GB NVMe and a 500 Mbps port for $6.23 a month on a year, which beats Bright Star on RAM, disk and port by $1.61 while giving up two cores.

## You are the administrator

There's no managed tier listed next to these plans. JustHost sells KVM servers with an OS image chosen at checkout, and everything above that layer is yours: patching, firewall rules, the web stack, TLS, monitoring, backups and troubleshooting. PCMag's definition is the one to keep in mind: unmanaged means the provider hosts your data and you run the server, while managed means the host takes on that work and charges notably more for it.

If you do end up comparing managed offers elsewhere, read the scope line by line. "Managed" can stop at the operating system and leave the control panel, web server, database, mail service and applications to you, and Liquid Web itself sells a middle "core-managed" tier precisely because the word covers so much ground.

## What to confirm before you pay

Seven things, in the order they're likely to cost you money:

1. **Backups.** Where are they stored, how often, and is there an off-server copy? Backups kept on the same box fail with the box.
2. **Refund window and trial.** Neither is published alongside these plans. Get the terms in writing before the first payment.
3. **IPv4 or IPv6.** The IPv6-only line is cheaper and unreachable from a lot of networks. Confirm which address family your plan includes.
4. **OS templates.** Check that your exact distribution and version is on the list at checkout rather than assuming it.
5. **Location and switching.** At least one location is documented (São Paulo, SAO1), and a March 2026 review of that location reports one-click data-centre and IP switching, up to 50 switches per VM. Confirm the location you want is available for your plan.
6. **The renewal rate.** The 20% term discount is published; whether the monthly rate itself changes later is not. Ask.
7. **Upgrade path.** Whether growing means resizing the existing server or rebuilding on a new one decides how painful next year is.

A missing uptime commitment deserves its own line. JustHost's plan listings don't carry a published SLA figure, while competitors publish 99.9%, 99.95% or stronger guarantees. If your site's downtime has a price, that absence is a real cost.

## When another host is the better buy

JustHost's case is cheap KVM servers with fast ports and a lot of configuration freedom. It is not the right pick if you need someone else to run the server, need Windows, need cPanel, or need a support phone number.

| Provider | Listed starting price | Management | OS | Where it wins |
| --- | --- | --- | --- | --- |
| Hostinger | $5.52/month | Self-managed | Linux | 1–8 vCPU, 4–32 GB RAM, 74 one-click apps and OS images, dashboard plus AI-assisted admin tools. PCMag rates its support highly |
| IONOS | $2.00/month | Mostly self-managed | Linux and Windows | Cheapest route to a Windows VPS, unlimited bandwidth. Plesk costs extra |
| Kamatera | $4.00/month | Managed and self-managed | Linux and Windows | Pick your own CPU/RAM/disk combination, 20+ data centres, hourly or monthly billing, 99.95% uptime claim |
| Bluehost | $4.69/month | Managed and self-managed | Linux | WordPress-tuned images, unlimited bandwidth, cheapest on a three-year term |

Starting prices are entry-tier promotional figures from a HostAdvice roundup updated in October 2026; renewal rates differ. Two more names come up repeatedly in editorial testing: Hostwinds, PCMag's Editors' Choice, sells managed and unmanaged VPS on Linux or Windows with RAM up to 96 GB, and Liquid Web backs its servers with a 100% power and network uptime guarantee and a 59-second support response pledge, at enterprise prices.

Short version: if you want a control panel, Windows, or a human to fix things at 2 a.m., pay someone else. If you want four cores and a 300 Mbps port for under $8 and you can administer it yourself, JustHost's numbers are hard to beat.

## Which plan to order

- **A single site, a blog, or a handful of small WordPress installs:** Bright Star at $7.84 on 12 months, unless the Specials block still has Vega Special at $6.23 for more RAM and disk.
- **20+ sites, or a store:** Yildun Special, 4 cores / 8 GB / 200 GB, $12.96 on 12 months.
- **Testing, DNS, a proxy or a monitoring node:** Promo at $1.99, and accept the 10 Mbps port for what it is.
- **Anything that needs managing for you:** none of the above. Look at the managed column in the table.

Before you pay, get two answers in writing: what you'll be charged after the first term, and how many days you have to cancel for a refund. Neither is on the pricing page, and both decide whether a cheap plan stays cheap.

👉 [Start with the $1.99 Promo plan or size up from the full tariff list](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

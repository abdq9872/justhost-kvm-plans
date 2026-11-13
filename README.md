# KVM VPS from $2.25 a month: which JustHost plan fits your workload, what the 20% annual discount really saves, and where "unmetered" stops meaning unlimited

JustHost's cheapest KVM VPS is **$2.25 a month on the 12-month term**: 1 core, 1 GB RAM, 20 GB NVMe and a 300 Mbit fair-share port. Pay month to month and the same plan is $2.81. That is a real KVM box with root access, not a container, and it is cheaper than most of the market's entry tier.

The plan most people should actually buy is the **Vega Special at $6.23 a month** on the same annual term ($7.79 monthly). Two cores, 4 GB RAM, 80 GB NVMe and a 500 Mbit port is the smallest configuration where Docker, a database and a website can share one machine without fighting over memory.

Below is every JustHost plan with a published price, the annual-versus-monthly arithmetic for year one and year two, the workloads each tier suits, and the limits that only show up once you read the port descriptions and third-party benchmarks.

> **Quick pick:** Vega Special, $6.23/month on the 12-month term. 2 cores, 4 GB RAM, 80 GB NVMe, 500 Mbit fair-share port. The right size for a Docker stack or a small app with its own database.
> **Cheapest usable entry:** Sirius Special, $2.25/month on the 12-month term. Fine for a static site, a reverse proxy or a VPN endpoint.

👉 [Check the Vega Special and the rest of the VPS range](https://justhost.asia/en/vps?ref=196392)

## Every JustHost KVM plan with a published price

JustHost splits its VPS range into two groups. The Special plans come with unmetered traffic and NVMe storage. The second group lets you pick HDD, SSD or NVMe at the same CPU and RAM level, and those are the plans that include both IPv4 and IPv6.

**Unmetered NVMe Special plans**

| Plan | vCPU / RAM / NVMe | Port (fair-share) | Monthly | 12-month (per month) | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Sirius Special | 1 core / 1 GB / 20 GB | 300 Mbit | $2.81 | **$2.25** | [Order Sirius](https://justhost.asia/en/vps?ref=196392) |
| VPS Arcturus Special | 1 core / 2 GB / 30 GB | 300 Mbit | $4.01 | **$3.21** | [Order Arcturus](https://justhost.asia/en/vps?ref=196392) |
| VPS Vega Special | 2 cores / 4 GB / 80 GB | 500 Mbit | $7.79 | **$6.23** | [Order Vega](https://justhost.asia/en/vps?ref=196392) |
| VPS Yildun Special | 4 cores / 8 GB / 200 GB | 750 Mbit | $16.20 | **$12.96** | [Order Yildun](https://justhost.asia/en/vps?ref=196392) |
| VPS Betelgeuse Special | 6 cores / 12 GB / 400 GB | 750 Mbit | $26.40 | **$21.12** | [Order Betelgeuse](https://justhost.asia/en/vps?ref=196392) |
| VPS Altair Special | 8 cores / 24 GB / 600 GB | 750 Mbit | $47.40 | **$37.92** | [Order Altair](https://justhost.asia/en/vps?ref=196392) |

**IPv4 + IPv6 plans with a storage choice**

| Plan | vCPU / RAM / Storage | Monthly | 12-month (per month) | Order |
| --- | --- | --- | --- | --- |
| HDD VPS Start | 1 core / 512 MB / 5 GB HDD | $3.25 | **$2.60** | [Order HDD Start](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Start+ | 1 core / 512 MB / 5 GB SSD | $3.90 | **$3.12** | [Order SSD Start+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Start++ | 1 core / 512 MB / 5 GB NVMe | $4.22 | **$3.38** | [Order NVMe Start++](https://justhost.asia/en/vps?ref=196392) |
| HDD VPS Standard | 2 cores / 2 GB / 25 GB HDD | $11.00 | **$8.80** | [Order HDD Standard](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Standard+ | 2 cores / 2 GB / 25 GB SSD | $13.20 | **$10.56** | [Order SSD Standard+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Standard++ | 2 cores / 2 GB / 25 GB NVMe | $14.30 | **$11.44** | [Order NVMe Standard++](https://justhost.asia/en/vps?ref=196392) |
| HDD VPS Super | 4 cores / 4 GB / 50 GB HDD | $22.00 | **$17.60** | [Order HDD Super](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Super+ | 4 cores / 4 GB / 50 GB SSD | $26.40 | **$21.12** | [Order SSD Super+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Super++ | 4 cores / 4 GB / 50 GB NVMe | $28.60 | **$22.88** | [Order NVMe Super++](https://justhost.asia/en/vps?ref=196392) |

There is a third line as well: an IPv6-only KVM range advertised from $1.60, sold in the same HDD/SSD/NVMe variants. It is worth a look only if you have IPv6 connectivity at your end and no need for an IPv4 address.

Two things about this price list are easy to misread. The 12-month column is the same plan with 20% taken off for paying a year up front, not a bigger machine. And the IPv4 + IPv6 plans are listed without a port-speed figure next to the price, so check the network terms for those before you order one.

## What the 20% annual discount costs you over two years

JustHost publishes two rates per plan and no separate renewal price. That makes the arithmetic simple, and it also means the discount does not disappear after year one.

| Plan | Year 1, annual | Year 1, monthly | Difference | Year 2, annual |
| --- | --- | --- | --- | --- |
| VPS Sirius Special | $27.00 | $33.72 | $6.72 | $27.00 |
| VPS Vega Special | $74.76 | $93.48 | $18.72 | $74.76 |
| VPS Altair Special | $455.04 | $568.80 | $113.76 | $455.04 |

The 20% is a term discount, available every time you renew on a 12-month term. If you renew annually, your second year costs the same as your first. If you drop to monthly billing, you pay the monthly column instead. That is a different risk profile from hosts that advertise a cheap first term and a much higher renewal: here the exposure is paying a full year up front to a provider whose refund window is not stated on the plan or FAQ pages. For a $27 plan that is a small bet. For the Altair, you are handing over $455 before you know whether the São Paulo or Hong Kong routing suits your users. Test on the monthly rate first if you are unsure.

👉 [Compare both rates on the full JustHost VPS list](https://justhost.asia/en/vps?ref=196392)

## Choosing by workload, not by core count

**Static site, reverse proxy, WireGuard endpoint, small Discord bot.** Sirius Special at $2.25. One core and 1 GB is plenty for Nginx serving flat files or a tunnel. The 20 GB NVMe is your real ceiling, not the CPU. Arcturus at $3.21 doubles the RAM and gives you 30 GB, which is worth the extra dollar if you plan to run a build step on the same box.

**Docker plus a database plus a site.** Vega Special at $6.23. Docker images, Postgres and a PHP or Node process together will use 2 GB before you have done anything interesting, so the 2 GB plans in the second table are a false economy for this shape of stack. 80 GB of NVMe also means you are not deleting logs every week.

**Several services, a staging copy, or a two-person team.** Yildun Special at $12.96. Four cores and 8 GB with 200 GB of disk covers a production app, a CI runner and a staging environment on one machine.

**12 GB and 24 GB plans.** Betelgeuse and Altair exist for memory-hungry workloads such as Elasticsearch, a large MySQL instance or a busy game backend. A WordPress site, an API and a handful of cron jobs will not come close. Most readers should stop reading the table at Yildun.

**Anything sensitive to single-core speed.** JustHost does not publish CPU models next to its plans. Independent reviews of two locations give a sense of what to expect: Geekbench 6 single-core 705 in São Paulo and 592 in Hong Kong, on Xeon E5 v4 hardware. That is fine for web serving and background jobs, and it is not the profile you want for a game server where tick timing or per-request latency matters.

**The storage-picker plans.** These make sense when you specifically want HDD capacity, want IPv4 and IPv6 on the cheapest possible box (HDD VPS Start at $2.60), or want to avoid an annual commitment. Otherwise the Special range gives you more RAM and NVMe for less money at every level.

## KVM versus OpenVZ: the difference you will actually notice

KVM runs any operating system, while OpenVZ runs Linux only. KVM also keeps resources isolated and private, where OpenVZ shares them with other users on the same node. That is the standard summary, and it holds for JustHost's range.

The practical version matters more. On KVM you can load your own kernel modules, set your own sysctl values and run your own container runtime. On a container-based host you cannot, because you are sharing the host kernel. If your application needs WireGuard, a custom filesystem module, or a Docker daemon with specific networking requirements, KVM is the difference between it working and a support ticket.

KVM is not a guarantee of speed. It is a guarantee that the box behaves like a machine you control, and that a noisy neighbour on the same physical host cannot eat your RAM.

## Where JustHost is the wrong choice

**You need a documented refund window.** Neither the VPS page nor the FAQ states a refund period. Ask support in writing before paying for a year.

**You need bandwidth you can actually saturate.** "Unmetered" means no traffic quota. The 300 Mbit and 750 Mbit figures are fair-share ports, and the page's own conversion shows what full utilisation would look like: 300 Mbit sustained for a month equals 93+ TB. Treat that as arithmetic rather than an allowance, because the port is shared with other customers on the same hardware.

**You need low latency into mainland China or Hong Kong.** A review of the Hong Kong location reports that outbound traffic for all three Chinese networks routes through the US, and recommends a relay for that reason. Buying a Hong Kong VPS for the Hong Kong location may not give you the latency you are picturing.

**You need multiple regions and a contractual uptime credit.** OVHcloud, for reference, runs 30+ datacentres, offers unlimited traffic with Asia-Pacific locations excluded from that promise, caps bandwidth at 3 Gbps and backs it with a 99.9% SLA. InstantNode runs a single Dutch datacentre in Eygelshoven, sells custom builds from €2.00/month, deploys in about 60 seconds and publishes a 99.9% SLA with pro-rata credits. JustHost's strength is the price per gigabyte of RAM and the unmetered port, not geographic coverage.

One feature worth knowing about, reported in reviews of both the São Paulo and Hong Kong locations: the control panel supports one-click datacentre switching and one-click IP switching, capped at 50 switches per VM. If you regularly need a different country's IP, that is unusual at this price point and worth confirming with support for the location you want.

## FAQ

**Is a KVM VPS faster than OpenVZ?**
KVM isolates resources and keeps them private, while OpenVZ shares them with other users on the node, so performance is more predictable on KVM under load. It also runs any OS, including Windows with your own licence.

**Can I install my own kernel or run Docker?**
Yes on both counts, because KVM is full virtualisation rather than a slice of a shared kernel. JustHost's FAQ says you can install any software and run tasks that need a custom configuration. Check the template list at the order step for your distribution.

**Can I run Windows?**
KVM makes it technically possible if you supply your own licence. JustHost's plan pages do not advertise Windows templates, so confirm support before buying a plan for that purpose.

**Can I upgrade later?**
Yes. JustHost's FAQ states you can add CPU cores, RAM or disk space at any time without migrating your data, with changes applied quickly and minimal downtime.

**Can I change datacentre after ordering?**
Reviews of the São Paulo and Hong Kong locations describe one-click datacentre and IP switching from the control panel, capped at 50 switches per VM. Verify the policy for your chosen location before you commit to an annual term.

**What payment methods are accepted?**
Reviews of both locations list cryptocurrencies, credit cards, PayPal, Alipay and UnionPay.

## Before you click order

Match the plan to the job rather than to the biggest number in the table: a static site or reverse proxy runs fine on Sirius at $2.25, a Docker stack with a database needs Vega at $6.23, several services on one box point to Yildun at $12.96, and the 24 GB Altair is for workloads you already know are memory-bound. If you need a specific country's IP for streaming or region-locked services, check that location's routing first, because the port speed and the plan specs say nothing about how traffic leaves the network.

Two things to confirm at checkout: whether you are paying monthly or for 12 months, since that single choice moves the price by 20%, and which datacentre you selected, since that determines your latency far more than the core count does.

👉 [Start with the Sirius Special at $2.25/month, or size up to Vega](https://justhost.asia/en/vps?ref=196392)

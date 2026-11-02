# rent vps: What $21.99 a Year Actually Buys You, and How to Pick the Right KVM Plan

Renting a VPS comes down to two questions: how much server you get per dollar, and what happens after the first billing cycle. On the first question, RackNerd's current KVM specials are hard to beat — a usable 1 GB KVM server costs **$21.99 per year**, which works out to roughly $1.83 a month, with full root access and a dedicated IPv4 included. On the second question, the answer is unusually clean: these special pricing stays the same at renewal for as long as you keep the service. But there are real trade-offs — it's an unmanaged server, and refunds are not automatic — and this article walks through all of it so you can decide in one sitting.

> **Quick pick:** For most people renting a VPS for self-hosting, a personal project, or a lightweight AI tool, the **2 GB KVM VPS at $35.99/year** is the sweet spot — 2 vCPU cores, 35 GB SSD, and 5 TB of monthly transfer. If you just need a sandbox, the 1 GB plan at $21.99/year is enough. Want to compare all five plans in one place? 👉 [Check RackNerd's current VPS specials and prices](https://racknerd.com/specials?aff=11397)

## RackNerd's full plan lineup

RackNerd's special pricing page currently shows five KVM VPS plans, all billed annually. Every plan includes full root access, 1 dedicated IPv4, a 1Gbps network port, the ctrl control panel, and your choice of datacenter. Provisioning happens automatically after payment.

| Plan | vCPU | RAM / SSD | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS (most popular) | 1 | 1 GB / 20 GB | 3 TB | $21.99/yr | [Order the 1 GB plan](https://my.racknerd.com/cart.php?a=add&pid=952&aff=11397) |
| 2 GB KVM VPS | 2 | 2 GB / 35 GB | 5 TB | $35.99/yr | [Order the 2 GB plan](https://my.racknerd.com/cart.php?a=add&pid=953&aff=11397) |
| 4 GB KVM VPS | 3 | 4 GB / 60 GB | 7 TB | $59.99/yr | [Order the 4 GB plan](https://my.racknerd.com/cart.php?a=add&pid=954&aff=11397) |
| 6 GB KVM VPS | 6 | 6 GB / 100 GB | 12 TB | $89.99/yr | [Order the 6 GB plan](https://my.racknerd.com/cart.php?a=add&pid=955&aff=11397) |
| 8 GB KVM VPS | 7 | 8 GB / 150 GB | 20 TB | $119.99/yr | [Order the 8 GB plan](https://my.racknerd.com/cart.php?a=add&pid=956&aff=11397) |

Beyond these specials, RackNerd's standard KVM line starts at $26.99/year for 512 MB RAM, 1 vCPU, 30 GB of RAID-10 SSD storage, and 500 GB of bandwidth, scaling up to 12 GB RAM and 7 vCPU cores. The hardware underneath is the same category: Intel Xeon processors, SSD storage with RAID-10 protection, and 1Gbps ports.

## What renting actually costs over two or three years

The sticker price is only half the story — the renewal price is where budget VPS deals usually fall apart. Many providers hook you with a first-term discount, then triple the price at renewal. RackNerd's official FAQ addresses this directly: these specials are "lifetime recurring," meaning you renew at the same rate for as long as you keep the service. Pay $35.99 for year one, pay $35.99 for year two, and so on.

That makes the math simple. The 2 GB plan costs about **$3 per month** if you spread the annual fee across twelve months. A comparable-spec server at a hyperscaler typically runs several times that — one independent review put the 2 GB special at roughly a third of what you'd pay a big-cloud provider for similar specs — and managed hosts charge more still, because you're also paying for their support layer.

The flip side of the annual model: you pay upfront, and there's no monthly escape hatch. If you're not sure whether a VPS fits your workload, that's a real consideration. RackNerd does sell standard monthly KVM plans, so a low-risk path is to trial a month-to-month server first, then switch to the annual special once you know the box handles what you run. If you've already done that math and just want the annual rate: 👉 [lock in the 2 GB KVM VPS at $35.99/year](https://my.racknerd.com/cart.php?a=add&pid=953&aff=11397)

## The fine print most reviews skip

Three terms live in the FAQ and terms of service rather than on the pricing cards, and each one should shape your decision.

**Refunds are not automatic.** RackNerd's terms state: "Refunds are issued on a case-by-case basis since by default no refunds are provided once payment is received." In plain terms, once you pay, don't count on getting the money back — support may work with you on a case, but there's no guaranteed 14-day or 30-day window. This is the single biggest difference between RackNerd and monthly-first providers like Cloudzy, which offers a 14-day no-questions refund.

**It's unmanaged.** You get full root access and platform support from the 24/7 team, but nobody is going to configure your web server, debug your application, or patch your CMS for you. If you want someone else to handle the server administration, a managed host is the better category — UltaHost, for example, sells both managed and unmanaged plans with a 30-day money-back guarantee.

**Cancellations need lead time.** At least one detailed third-party review notes a seven-day notice requirement before renewal. Even if you take that number loosely, the practical advice holds: if you decide to leave, cancel well before the renewal date rather than on it, and keep a calendar reminder for the anniversary of your order.

If you've read those three points and they're acceptable — which they are for most self-hosters — the annual rate is where the value is: 👉 [see the current specials and grab a plan](https://racknerd.com/specials?aff=11397)

## What you can actually run on these plans

The current specials are pitched at self-hosting and AI workloads, and the ctrl control panel backs that up with one-click apps. Install Ollama, AnythingLLM, LibreChat, n8n, Coolify, or Docker with Portainer from the panel; credentials show up in-panel once the app is ready. WordPress is covered too, via AdminBolt, CyberPanel, or CloudPanel.

The RAM requirements are worth checking before you pick a plan, because they map neatly onto the lineup:

- **n8n, Coolify:** comfortable from 2 GB — the $35.99/year plan handles them
- **Hermes Agent, AnythingLLM, Ollama, LibreChat:** want at least 4 GB — the $59.99/year plan
- **OpenClaw:** wants at least 8 GB — the $119.99/year plan

Since every plan includes full root SSH access, you're never limited to the one-click catalog; bring your own stack over SSH, upload a custom ISO by opening a support ticket, or run whatever else fits the disk and RAM. Supported operating systems out of the box include CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, and Ubuntu.

If your target is the AI end of that list, the 4 GB plan is the minimum sensible entry point: 👉 [order the 4 GB KVM VPS at $59.99/year](https://my.racknerd.com/cart.php?a=add&pid=954&aff=11397)

## Datacenter locations: 20 options across three continents

Where your server lives matters as much as its specs if you care about latency. RackNerd operates 20 datacenter locations across North America, Europe, and Asia, and you choose the location during checkout.

In the United States: Los Angeles, San Jose, Seattle, Utah, Chicago, Dallas, New York, New Jersey, Atlanta, Tampa, Miami, and Ashburn. Outside the US: Montreal and Toronto in Canada, London, Amsterdam, Strasbourg, Frankfurt, Singapore, and Dublin. The official guidance is to pick the location closest to your users for faster response times — a Los Angeles server for a West Coast audience, Frankfurt or Amsterdam for Europe, and so on.

One honest caveat: RackNerd doesn't publish a public uptime SLA percentage on the specials page, so if a contractual uptime guarantee is a hard requirement for your project, that's a question to raise with support before ordering.

## How this compares with monthly-first rental providers

"Rent VPS" searches often surface providers built around month-to-month flexibility, and they genuinely serve a different need. Here's how the verified numbers stack up:

| Provider | Entry price | Billing | Refund policy | Notable points |
| --- | --- | --- | --- | --- |
| RackNerd | $21.99/yr (1 GB KVM) | Annual specials; monthly plans available | Case-by-case; none by default | Same price at renewal, 20 datacenters, unmanaged |
| Cloudzy | $2.48/mo (512 MB, 1 vCPU, 20 GB NVMe) | Monthly, no contract | 14-day full refund | 13 regions, cancel from dashboard anytime |
| UltaHost | Varies by plan | Monthly | 30-day money-back | Managed and unmanaged options, Windows VPS for .NET stacks |
| HOSTKEY | €2.46/mo (1 vCPU, 1 GB, 40 GB SSD) | Monthly | Not stated on page | GPU servers from €70/mo up to H100 at €1,590/mo |

The practical read: if you need a server for a two-week hackathon or a proof of concept you'll tear down afterward, a monthly provider with a short refund window is the safer shape of purchase. If the server will run for a year or more — a personal blog, a home-lab-style stack, a bot, a VPN endpoint — the annual special costs less per month by a wide margin, and the renewal-price lock removes the usual year-two sting.

Neither model is universally better; they just price risk differently. RackNerd shifts risk to you (pay upfront, minimal refunds) and rewards you with a low fixed rate. Monthly hosts absorb that risk and charge for it.

## Ordering a VPS at RackNerd, step by step

The purchase flow is short, and knowing it in advance helps you avoid the one genuine gotcha.

1. **Configure.** Pick a plan, choose your datacenter location and operating system, and select a billing cycle (monthly, quarterly, semi-annually, or annually on the standard line; the specials are annual).
2. **Checkout.** Fill in your details, agree to the terms of service, and complete the order. You can add notes to the order, but for time-sensitive requests the official advice is to open a ticket after ordering instead.
3. **Payment.** PayPal, credit card, cryptocurrency, and bank wire are accepted.
4. **Deployment.** Provisioning is automatic, and most deployments complete within 5 to 15 minutes.
5. **Check your email — twice.** You'll get an order confirmation, then a separate "KVM VPS Login Information" email containing your IP address, root SSH credentials, and the URL plus login for the ctrl panel. Here's the gotcha: **ctrl panel credentials are separate from your Client Area login**, and the Client Area is where you handle reboots, reinstalls, and bandwidth monitoring. If you lose the login email, the "View Email Log" section in the Client Area has it.

For the SSH connection itself, Windows users can grab Bitvise SSH Client; macOS and Linux have Terminal built in. One small thing that trips up newcomers: some SSH clients don't display characters when you paste the root password, for security. Paste it, press Enter, and you're in.

## Common questions

**Does the renewal price really stay the same?**
Yes — the official FAQ states the specials are lifetime recurring and can be renewed at the same rate for as long as you keep the service. The condition is continuity: if the service lapses, you'd be re-ordering at whatever the current promotion is.

**Can I get a refund if I change my mind?**
Not by default. Refunds are handled case-by-case, and the terms say no refunds are provided once payment is received. If refund flexibility matters to you, that points toward a monthly plan or a provider with a money-back guarantee.

**Can I run Windows on these plans?**
The specials are Linux KVM servers, with CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, and Ubuntu available at checkout and custom ISO installs available by ticket. RackNerd does sell separate Windows VPS plans on Ryzen hardware with full Administrator access and RDP, but those are a different product line.

**Is this a good first server for learning Linux?**
The price makes it a low-stakes way to break things, and the ctrl panel handles reinstallations and password resets so you can start over freely. Just go in knowing support won't configure things for you — that's part of the learning.

**How fast is setup?**
Automatic after payment, with most deployments finished in 5 to 15 minutes.

## Which plan should you actually order

Here's the decision path, based on the verified specs:

- **Light sandbox, DNS tool, small bot, or learning server:** the 1 GB plan at $21.99/year. Don't pay for RAM your workload won't touch.
- **Self-hosted apps, n8n automation, Coolify, a personal site with real traffic:** the 2 GB plan at $35.99/year. This is the plan that fits most people renting a VPS for the first time.
- **Ollama, AnythingLLM, LibreChat, or a small database with actual users:** the 4 GB plan at $59.99/year — the minimum for the AI one-click apps.
- **Multiple services running side by side:** the 6 GB plan at $89.99/year, with 6 cores and 12 TB of transfer.
- **OpenClaw or anything RAM-hungry:** the 8 GB plan at $119.99/year, with 150 GB SSD and 20 TB of transfer.

Two things to confirm before you click order: pick the datacenter closest to whoever uses the server, and set a reminder for your renewal date so a service you meant to keep doesn't lapse, or one you meant to cancel doesn't auto-renew. Ready when you are: 👉 [browse all five RackNerd specials and order your plan](https://racknerd.com/specials?aff=11397)

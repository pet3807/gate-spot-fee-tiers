# gate io spot fees: Every VIP Tier, the GT Discount, and What One Trade Actually Costs

Most people searching for gate io spot fees are trying to answer one of three questions: what does a normal account pay, how do I pay less, and is the number on the marketing page the number that shows up on my bill. Those have three different answers, and the third one is where most fee guides quietly get it wrong.

Here's the short version. A standard account pays **0.1% maker and 0.1% taker** on spot. Turn on GT deduction and both drop to **0.09%**. Everything above that is a 17-step ladder from VIP 0 to VIP 16 that you climb with trading volume, GT holdings, or account assets — and the schedule was last reworked on 9 April 2026, so any guide showing a clean 0.2% starting rate is quoting either the wrong product or a two-year-old page.

## What the base spot fee actually is

At VIP 0, Gate charges 0.1% on both sides. There is no tiered break between maker and taker at the bottom of the ladder — placing a limit order that rests on the book costs exactly the same as crossing the spread. The maker/taker split doesn't open up until VIP 4, where it becomes 0.095% maker against 0.096% taker.

Fees are charged only on the filled portion of an order, and they're deducted automatically at execution. Unfilled orders cost nothing. The arithmetic itself is boring, which is the point:

- Trade value = price × quantity
- Fee = trade value × your rate

Sell 2 ETH at $2,000 and you've traded $4,000. At the VIP 0 taker rate that's **$4**. Round trip, you've spent $8 to move in and out, or 0.2% of your capital — before slippage, before any funding costs on derivatives, before withdrawal fees.

That round-trip 0.2% is the number that matters for anyone trading more than a few times a month. It's also the number that makes the tier ladder worth understanding.

## Maker vs taker: the same trade at two different prices

Maker fee applies when your limit order adds liquidity — it sits in the book and waits. Taker fee applies when your order removes liquidity, which covers market orders and limit orders priced aggressively enough to fill immediately.

On Gate the two rates converge at the low tiers and diverge higher up. By VIP 9 the spread is 0.07% maker against 0.075% taker. By VIP 16 it's 0% maker against 0.0175% taker. If your strategy is mostly market orders, most of the ladder's maker-side improvements do nothing for you, and the gap between the two columns is the fee you're paying for speed.

The practical takeaway: if you're indifferent between entering now and entering at your price, the maker side of the table is where the discount lives.

## The full Gate spot fee table, VIP 0 to VIP 16

Every tier currently published on Gate's fee schedule, with the standard rate and the rate you get when GT deduction is active.

| VIP tier | 30-day spot volume to qualify (USD) | VIP maker / taker | With GT deduction (maker / taker) |  |
| --- | --- | --- | --- | --- |
| VIP 0 | $0 | 0.1% / 0.1% | 0.09% / 0.09% | [ Open a Gate account](https://bit.ly/GateVIP) |
| VIP 1 | $60,000 | 0.099% / 0.099% | 0.089% / 0.089% | [ Start trading](https://bit.ly/GateVIP) |
| VIP 2 | $120,000 | 0.098% / 0.098% | 0.088% / 0.088% | [ Register and check your tier](https://bit.ly/GateVIP) |
| VIP 3 | $240,000 | 0.097% / 0.097% | 0.087% / 0.087% | [ Sign up](https://bit.ly/GateVIP) |
| VIP 4 | $500,000 | 0.095% / 0.096% | 0.086% / 0.086% | [ Get started](https://bit.ly/GateVIP) |
| VIP 5 | $1,000,000 | 0.09% / 0.095% | 0.081% / 0.085% | [ Create your account](https://bit.ly/GateVIP) |
| VIP 6 | $3,000,000 | 0.085% / 0.09% | 0.076% / 0.081% | [ Join Gate](https://bit.ly/GateVIP) |
| VIP 7 | $8,000,000 | 0.08% / 0.085% | 0.07% / 0.076% | [ Register now](https://bit.ly/GateVIP) |
| VIP 8 | $20,000,000 | 0.075% / 0.08% | 0.06% / 0.072% | [ Open an account](https://bit.ly/GateVIP) |
| VIP 9 | $50,000,000 | 0.07% / 0.075% | 0.05% / 0.068% | [ Start here](https://bit.ly/GateVIP) |
| VIP 10 | $100,000,000 | 0.04% / 0.058% | No separate GT rate | [ Sign up and trade](https://bit.ly/GateVIP) |
| VIP 11 | $120,000,000 | 0.03% / 0.045% | No separate GT rate | [ Register](https://bit.ly/GateVIP) |
| VIP 12 | $240,000,000 | 0.02% / 0.037% | No separate GT rate | [ Get your fee tier](https://bit.ly/GateVIP) |
| VIP 13 | $440,000,000 | 0.01% / 0.03% | No separate GT rate | [ Open your account](https://bit.ly/GateVIP) |
| VIP 14 | $800,000,000 | 0.008% / 0.023% | No separate GT rate | [ Join and verify](https://bit.ly/GateVIP) |
| VIP 15 | $1,600,000,000 | 0% / 0.02% | No separate GT rate | [ Sign up](https://bit.ly/GateVIP) |
| VIP 16 | $3,000,000,000 | 0% / 0.0175% | No separate GT rate | [ Create account](https://bit.ly/GateVIP) |

Two things are worth flagging in that table.

The schedule publishes a separate GT-paid rate only through VIP 9. From VIP 10 upward the token stops buying you a lower rate — the two columns collapse into one. If you're holding GT purely to shave fees, that stops working at exactly the point where fee differences start to matter most.

VIP 15 and VIP 16 are not something a retail account can be upgraded into. Gate's fee page states that regular VIP users cannot be upgraded to those two levels; accounts reaching them are handled as senior institutional users. So for anyone reading this as an individual trader, VIP 14 is the practical ceiling.

## How you move up a tier — and which path is cheapest

Gate doesn't require you to hit all three thresholds. Meeting any one of them qualifies you, and the system re-evaluates roughly every six hours, so a tier change can land the same day your volume crosses the line.

The three tracks:

1. **30-day volume.** Spot volume counts at 100%, futures volume at 40%, options at 20%, and CFD volume at 10%. Spot copy-trading and Convert volume are included in the spot figure.
2. **14-day average GT holdings.** This is a daily average, not a balance you can hold for an afternoon — buying GT the day before the snapshot won't qualify you. Gate counts GT and GT2.
3. **Account asset value.** Representative published thresholds run $2,000 for VIP 1, $40,000 for VIP 5, $2,000,000 for VIP 10, and $30,000,000 for VIP 14.

The GT path is the one that trips people up. It's also the one with a cost the fee table doesn't show: reaching VIP 10 on holdings alone requires around 100,000 GT averaged over two weeks, which is a real capital position in a token that moves. You're trading fee savings for token price exposure. That's a defensible trade if you already wanted the exposure, and a bad one if you didn't.

## GT deduction: how to switch it on, and where it stops helping

GT deduction uses your GT balance to pay spot fees at the discounted rate. Once enabled, GT is consumed first; if the balance runs out, the system silently falls back to your standard VIP rate. If you've told your account to use the VIP rate instead, no GT is touched at all.

Enabling it takes a few clicks on the VIP or fee page — in the app it sits under your profile, alongside the fee schedule itself. Whether it's worth it depends on the tier:

- At VIP 0, the GT rate is **0.09% against 0.1%** — roughly a tenth off.
- At VIP 5, it's **0.081% / 0.085% against 0.09% / 0.095%**, a wider gap.
- At VIP 10 and above, there's no separate GT rate to move to.

On a $10,000 spot trade, 0.1% versus 0.09% is $10 versus $9. In and out, $20 versus $18. Two dollars is nothing until you scale it: at $1,000,000 of monthly spot volume, that one-tenth difference is $1,000 versus $900. That's the entire argument for bothering with the token, and also the reason to check whether your holdings qualify you for a tier first — the tier discount is usually the bigger of the two levers.

[👉 Turn on GT deduction and check your own rate tier](https://bit.ly/GateVIP)

## What the spot fee table leaves out

The fee schedule is one line item in a longer bill, and the rest of the bill is where budget accounts get surprised.

- **Withdrawals.** Priced separately from trading and quoted per coin and network. Gate's own fee page attaches a 24-hour withdrawal limit to each tier — $3,000,000 at VIP 0, $5,000,000 at VIP 5, up to $50,000,000 at VIP 16 — which is a limit, not a cost, but the cost itself is dynamic. Fee-comparison sites that track Gate have flagged stablecoin withdrawal charges as a recurring user complaint, with reports of amounts above the posted figure. Check the live withdrawal fee for your specific network before moving funds off the exchange, especially if your deposit was small.
- **Alpha trading.** A flat 0.8% at every tier, VIP 16 included. If you're trading Alpha tokens, none of the ladder applies to you.
- **Futures funding rates.** Separate from maker/taker commission and charged repeatedly while a position is open. On a multi-day position these can exceed the entry and exit commission.
- **Deposits.** Free, as on most major exchanges.

There's also a low-tier trap worth naming. From VIP 0 through VIP 3, maker and taker rates are identical, so resting an order on the book saves you exactly nothing. The maker discount only becomes real at VIP 4 and stays below one basis point until VIP 9.

## Checking your own rate takes about a minute

Posted schedule versus charged rat…, and you should confirm which applies to you before assuming a fee change helped.

On web: **Assets → Billing Details → Unified Account**, then pick the coin to see the fees actually deducted. Or go to **Spot → Trade History** for a per-trade breakdown. The current schedule is at the bottom of the homepage under the fee standard link. If the charged amount doesn't match your calculation, the usual causes are a tier change you didn't notice or GT deduction quietly kicking in — or having silently run out of GT and reverted to the standard rate.

[Rates are revised periodically — 👉 check the current Gate fee schedule before your next order](https://bit.ly/GateVIP)

## Is Gate cheap on spot, or just cheap-looking?

At VIP 0, 0.1% maker and taker is mid-pack for a major exchange — not the lowest headline number, but not the highest either. What differs is how fast the ladder moves once you're trading seriously. Reaching 0.09%/0.095% takes $1,000,000 of 30-day volume at VIP 5; the same tier also unlocks at 2,000 GT held on a 14-day average or $40,000 in account assets, which is a much lower bar for someone sitting on capital rather than churning it.

That's the honest read on gate.io spot fees: the base rate is unremarkable, the top of the ladder is genuinely competitive, and the interesting question is which of the three qualifying paths gets *you* there without changing how you trade.

Practical order of operations, roughly in order of return:

1. Enable GT deduction. Immediate, free, no lockup.
2. Check whether your existing balance qualifies you for a tier you're not on. A lot of people are sitting on an asset threshold and paying VIP 0.
3. Only then consider trading more volume to climb — and only if the volume was going to happen anyway.
4. Move off the spot fee entirely if you're trading Alpha tokens. That 0.8% is unaffected by any of this.

## FAQ

**Does Gate charge 0.1% or 0.2% on spot?**
0.1% per side at VIP 0, so 0.2% for a full round trip. The 0.2% figure you'll see quoted online is almost always a round-trip number, not a per-trade rate.

**Do spot fees go down if I hold GT?**
Yes, up to VIP 9. Past VIP 10 the schedule lists no separate GT rate, so holding the token no longer lowers the rate on top of your tier.

**Are maker and taker the same on Gate?**
At VIP 0 through VIP 3, yes — 0.09% vs 0.09% with GT, 0.1% vs 0.1% without. The split starts at VIP 4 and widens up the ladder.

**How often does Gate recalculate VIP levels?**
Roughly every six hours. Hitting a threshold can change your rate the same day, and dropping below it costs you the tier again.

**Are there signup bonuses that offset fees?**
Gate's Rewards Hub runs a starter task set — register, complete identity verification, make a first deposit, place a first spot or futures trade — with coupon rewards that change between campaigns and regions. Read the live page rather than a screenshot in someone's blog post, including this one.

[👉 Register on Gate and see which fee tier you land in](https://bit.ly/GateVIP)

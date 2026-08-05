---
source: notes
source_path: sources/podcasts/invest-like-the-best/2026-08-04-gavin-baker-ai-market-jitters-invest-like-the-best-ep-485.md
source_title: "Gavin Baker - AI Market Jitters - [Invest Like the Best, EP.485]"
source_date: 2026-08-04
show: "Invest Like the Best"
themes: []
generated_at: 2026-08-05T02:04:44+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: Gavin Baker - AI Market Jitters - [Invest Like the Best, EP.485]

## Summary

The July 2025 AI sell-off was driven by **narrative**, not fundamentals. Gavin Baker's central point is that every ground-level metric — GPU prices, token growth, DRAM spot pricing — was accelerating during the panic, not deteriorating.

The disconnect exists because public markets lack visibility into private players like Anthropic and OpenAI, which are driving the real story. Baker describes July as "2022 in a month" — sentiment collapse detached from underlying data.

Open source is widely misread as a threat. Baker argues it is the opposite: cheaper tokens shift margin away from frontier model providers but leave GPU hour consumption flat or rising. It is a demand multiplier for compute, not a demand killer.

The structural risk most investors are missing is **credit dependency**. If operating cash flows don't reprice fast enough to self-fund the build-out, debt fills the gap — and debt-fuelled infrastructure unwinds badly, as the dot-com era showed. Long-term supply agreements are the mechanism locking in winners right now: breaking one risks losing compute allocation permanently, so market share over the next several years will be decided by who pre-purchased, not who has the best model.

Regulation is Baker's single most underappreciated risk. Data centres lower local power costs and create blue-collar jobs, yet that story is being told badly by Silicon Valley. New York's data centre moratorium is an early warning sign, not an isolated event.

## Why July Was a Narrative Panic

### "I would describe July as 2022 in a month." [0:02:28]

The framing matters. Gavin isn't saying it's a crash — he's saying the *speed* of repricing is the anomaly, not the direction. Fundamentals were improving while prices collapsed. That gap is where the opportunity or the trap lives.

### "Every metric is actually accelerated." [0:03:07]

GPU availability, GPU rental pricing, DRAM spot price, token growth — all moving the same direction. This is the core tension of the episode: the market sold off hard on narratives Gavin considers factually weak.

### "Claude is kind of Walter Cronkite for the stock market." [0:21:35]

Everyone is feeding news into Claude, getting similar probabilistic outputs, and **trading on the same interpretation**. It's manufactured consensus — and Claude isn't always right, especially on forward-looking probabilistic calls. Ironic that the AI boom's biggest short-term risk is AI homogenising market reaction.

## Open Source as Demand Multiplier

### "Open source taking share does is take margin dollars out of the frontier model layer." [0:08:22]

Cheaper tokens don't destroy compute demand — they shift **margin** from Anthropic/OpenAI down to infrastructure. The cloud providers still get paid. GPU hours are the same. The market misread this badly, and Gavin's explanation here is the clearest rebuttal I've seen.

### "Have you heard anyone say they have too many GPUs?" [0:27:18]

Not one person. The anecdote about a startup paying ~$2/GPU hour renewing at just under $4 — **50-60% price increase** in six months — is the cleanest signal that this is a genuine shortage, not hype.

## Scale of the Prize

### "There's $25 trillion in knowledge work." [0:32:08]

At 20% tokens-as-percent-of-comp, that's a $5 trillion addressable pool. It either comes from **labour substitution or faster economic growth** — and Gavin's point is we really want it to be the latter. The bull case is that simple and that large.

## LTA Game Theory Locks In Winners

### "if you break the LTA, this is assuming we're not at a severe oversupply situation... if you break your LTA and then in the next two or three years for any reason, leverage shifts back to the memory guys, you're out of business, it's over." [0:34:36]

The asymmetry here is brutal.
Breaking an LTA to save cost in a downcycle
risks your supply position in the **next** upcycle.
Cyclical industries punish disloyalty — this is
a higher-stakes version of that.

### "market shares I think for the next several years are going to be determined by supply chain allocations and kind of what you have pre purchased." [0:34:36]

This reframes the whole competitive landscape.
**Winning isn't about the model** — it's about
who locked in compute early.
That's a non-obvious and uncomfortable truth
for anyone betting on pure capability.

## Inference Routers and Defensible Moats

### "if you can go from just using one, two or three frontier models to using those frontier models for whatever it is, 30 to 60% of your token consumption, and then use your own RL model, all of a sudden you're not a rapper, you're way more defensible." [0:48:34]

The "ChatGPT wrapper" criticism finally has a
structural answer: **fine-tune on your own data**,
use frontier only where it matters, and you have
real moat. Directly relevant to Loom's architecture
choices if it ever needs a proprietary model layer.

## Regulation as the Ignored Risk

### "Data centers are in a lot of ways the best thing to happen for blue collar wages in my lifetime. And yet you have the Democrats who ostensibly represent the blue collar workers taking those jobs away." [0:53:52]

The political narrative vs. economic reality gap
is stark here. The **PR failure** is real — and
Gavin's point is that the industry is letting a
correctable misconception calcify into policy risk.

### "I think regulatory has to be the biggest risk... you just can't ignore New York making a data center moratorium." [0:51:48]

He's bullish on fundamentals but this is the
honest caveat. **Regulation isn't a tail risk** —
it's already happening, and the industry's poor
messaging makes it worse. Worth watching as a
structural constraint on AI infra build-out.

## SpaceX as Mispriced Compute Play

### "SpaceX has kind of brought out the most, the fastest at the lowest cost... it doesn't feel like that's in estimates or really in people's thinking." [1:02:27]

The market is pricing SpaceX as a rocket company.
Gavin's saying it's actually the **most efficient
compute builder** among non-hyperscalers — and
that's not in consensus numbers at all.
That's a meaningful dislocation if he's right.

## Key Arguments

1. **Sell-off is narrative, not fundamental**
   - Every quantitative signal is accelerating
   - Public markets can't see private
     companies driving the real story

2. **Open source is infrastructure-positive**
   - Cheaper tokens shift margin to compute
   - GPU hours consumed stay flat or rise
   - Not a threat — a demand multiplier

3. **Credit dependency is the real risk**
   - If cash flows don't reprice fast enough,
     debt fills the gap
   - Debt-fuelled build-outs unwind hard
     — dot-com era is the template

4. **LTA game theory locks in winners now**
   - Breaking a supply agreement risks
     losing compute allocation permanently
   - Market share decided by who
     pre-purchased, not who has best model

5. **Inference routers create real moats**
   - Tools like Fireworks' Dexus let firms
     fine-tune on proprietary data
   - Reduces frontier-token dependency
   - Turns "wrappers" into defensible biz

6. **Regulation is the #1 ignored risk**
   - Data centres lower local power costs
     and create blue-collar jobs
   - That story isn't being told
   - NY moratorium is an early warning

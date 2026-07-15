---
source: notes
source_path: sources/podcasts/invest-like-the-best/2026-06-30-etched-building-ai-hardware-to-make-inference-faster-and-cheaper-invest-like.md
source_title: "Etched - Building AI Hardware to Make Inference Faster and Cheaper - [Invest Like the Best, EP.480]"
source_date: 2026-06-30
show: "Invest Like the Best"
themes: ["AI & Technology", "Misc"]
generated_at: 2026-07-01T02:10:06+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: Etched - Building AI Hardware to Make Inference Faster and Cheaper - [Invest Like the Best, EP.480]

## Summary

Etched is building a purpose-built chip for AI **inference** — and its founders believe inference will become the largest compute market ever built.

The core bet is simple. Today, a fraction of a percent of people pay for AI. Scaling to billions of concurrent users requires hardware designed for that workload from the ground up, not adapted from training chips. Etched's chip discards the assumptions the broader semiconductor industry inherited — voltage floors, temperature norms, generalised interconnects — because those assumptions were built for flexibility, not for the decode/prefill workload that inference actually runs.

Their software strategy matches the hardware focus. Rather than supporting every model, they hand-optimise for under 100 models that dominate real usage. This is a deliberate structural choice: pure-play focus means they must win or die, which drives harder decisions and attracts different talent than hyperscalers building chips as an internal hedge.

Operationally, their edge showed up early. A competitor took ten months to go from silicon to running inference in a rack. Etched did it in forty days — by prefetching software, racks, and production lines in parallel before the chips arrived. The **wall-clock compression** this unlocks matters beyond unit economics: agent tasks that take months shrink to days, which is a qualitative capability shift, not just a cost saving.

The end state they describe is civilisation-scale inference, where nations compete on data-centre energy efficiency as a proxy for workforce size, and GDP is measured in agents per gigawatt. Getting there requires inference costs to scale sub-linearly — buying ten times more servers for ten times more tokens is not a viable path to mass adoption.

## Why Inference Wins

### "it seems like inference is going to be really important. And it feels like we are on a decade march for inference to become the biggest market in the world" [0:20:53]

The realisation came from watching every startup spend all its capital on compute. The COGS of software is no longer near-zero — it's a function of inference spend, and so is the opex as coding agents proliferate. This is the **macro bet** underpinning everything. If correct, inference hardware is as foundational as cloud infrastructure was in the 2010s.

### "if I want to go serve 10 times more tokens, I buy 10 times more servers" [1:25:39]

That's the **broken model** Etched is building against. Linear cost scaling kills AI economics at adoption scale. The whole hardware bet only makes sense if you can break this relationship.

### "it must be some solution where if I want to go serve 10 times more tokens, then I get some economies of scale benefit" [1:25:39]

The **thesis in one sentence** — cluster-scale memory tech should produce falling per-token costs as volume grows, not flat or rising ones. This is the same logic that made cloud compute deflationary. Worth watching whether the silicon actually delivers it.

## Discarding Inherited Assumptions

### "the entire semiconductors and data center industry is built on buffer" [0:04:21]

Every layer of the stack — EDA tools, power modules, boards, standard cells — is built general-purpose. Not for AI data centres specifically. This is the core insight that lets a small team beat incumbents: **legacy constraints aren't physics**, they're habit.

### "I don't know about you, but I've never seen an AI data center with ice in it" [0:04:21]

Default EDA tool configurations assume chips run at freezing temperatures. Etched simply excluded that corner — chips will never run below 80°C anyway — and unlocked a cascade of optimisations throughout the system. A trivially obvious observation that nobody acted on. That gap is where startups live.

### "on GPUs you often get somewhere between 20 and 50% depending on the workload" [0:09:38]

The headline FLOP number is marketing. Model FLOP utilisation is the real metric — and GPU thermal throttling means 100% is provably unreachable: more transistors switching means more heat, which auto-reduces clock speed. Etched's low-voltage approach attacks the **thermal ceiling** directly, rather than bolting on more compute that can't be used.

### "we were able to create a new mechanism of running at much lower voltages, a new type of power delivery that we call low voltage inference" [0:09:38]

Bitcoin miners already run at under a quarter of GPU voltage — so the physics is proven. The question was whether GPU architectural constraints blocked it. Etched concluded they didn't, and built the mechanism. Classic move: find a domain where the constraint is already solved, port the insight across. Semiconductor veterans said it was impossible; miners proved it wasn't.

## Cluster-Level Architecture

### "people often ask how much memory bandwidth is on your chip. It should be asking how much memory bandwidth is on your full scale up cluster" [0:12:29]

Etched reframes the decode problem at cluster level — treating SRAM and HBM across all chips as a single unified pool. Their custom interconnect stack makes this viable by slashing chip-to-chip latency. The **wrong unit of analysis** is the whole problem. Everyone's optimising the chip; the bottleneck is the network between chips.

### "the best vendor is no vendor. As much as possible, we want to vertically integrate the entire product, both because we get more performance, but we can move way faster." [0:27:27]

Vertical integration as a **speed** argument, not just a quality one. Most hardware startups treat vendors as facts of life. Etched treats them as latency in disguise.

### "we envisioned a world where there was going to be under 100 models that actually mattered, and they were all going to look very similar from the underlying mathematical perspective" [0:51:31]

Etched's entire software bet rests on this constraint — skip the **general-purpose compiler**, build physics-level primitives for a small, stable model landscape. Contrarian when they made it. If model diversity explodes, this is their biggest architectural risk.

## Recruiting Rare Hardware Talent

### "we found three people that we thought could fit the bill and we talked to all of them and two of them have just retired." [0:30:13]

They mapped the entire Nvidia rack lineage, identified three humans on earth who qualified, and chased the one still working. That's not recruiting — that's targeting. The process matters more than the pitch.

### "you'd be surprised by the amount of people who say yes after the first conversation is pretty low. But the amount of people who say yes after the 20th conversation is surprisingly high." [0:29:09]

Persistence as a **recruiting primitive**. Most founders treat a first "no" as signal about fit. Etched treats it as the start of a relationship with a lag.

## Silicon to Inference in 40 Days

### "there is another very famous AI chip company that took 10 months to go from getting their silicon back to having them running inference in a rack. We were able to do it in 40 days." [0:38:34]

The **prefetching** strategy — building everything in parallel before the chip arrives — compressed a 10-month industry benchmark to 40 days. This is the clearest proof point in the excerpt that their philosophy is real, not just rhetoric.

### "a year long compute build would now take a month and that month long compute build will now take three days and that three day compute build will now take seven hours and so forth." [0:46:36]

Compounding **latency reduction** on long-horizon tasks is the real unlock — not chat speed. This is the frame that makes their 10x throughput claim matter. Speed on short tasks is nice; speed on month-long agent runs is a category shift.

### "If you have the most performant product and you can't produce it, then you're just a podcast." [1:16:15]

The line lands as a joke but it's a real strategic point: supply chain has to be designed in from the start, not bolted on after performance is proven. Worth filing for any hardware or physical product build — **availability beats specs** every time in a supply-constrained market.

## The Hard Engineering Problems

### "We had to go line up two clock signals on our chip to within 50 picoseconds, that is literally 50 trillionths of a second." [0:58:44]

The clock domain crossing failure was producing wrong results and there was exactly one fix: align two clocks to 50ps precision, 2 billion times a second. The specificity here matters — this isn't "we hit a hard engineering problem," it's a problem most teams would have scoped as impossible and shipped around. They shipped through it.

### "People literally were like this problem is unsolvable and best of luck guys." [0:58:44]

People quit over it. The response was: assume the problem is solvable — how would it be solved? That reframe is a repeatable mental tool worth keeping. Declaring impossibility is just a failure of imagination dressed up as rigor.

### "We think we're going to spend $100 million in the next 12 months... How the hell are we going to pull this off?" [1:03:33]

At the time the biggest semiconductor Series A was $40-50M. Etched was tallying a $100M spend requirement with $15M in the bank, and every major Valley investor had already passed. The gap between what the market believed was fundable and what the actual build cost was enormous — and they raised it anyway, in a snowball of small cheques.

## Supply Chain as Strategy

### "It fundamentally is not existential for my company for this product to win." [0:55:43]

The recruit's logic is devastating: Google won't fail if TPUs fail, Meta won't fail if MTIA fails, OpenAI won't fail if Jalapeño fails — but Etched fails if Etched fails. This is the cleanest articulation of why pure-play beats vertical integration in high-stakes hardware. Nvidia is the proof. The hyperscalers are playing defence; Etched is playing for survival.

### "If you get surgery, you're more likely to live, but you have to assume you'll never be able to walk again" [1:26:16]

The **trade-off framing** is stark — mobility vs. survival probability, handed to a 16-year-old to decide. Most founders have a "hard early life" story; this one is unusually concrete and verifiable.

## Civilisation-Scale Compute

### "I think this is the second to last year where a majority of the workforce is going to be human." [1:22:45]

The claim: 2027 is when agent knowledge workers outnumber humans in that category — and what happens after that is described as simply unfathomable. Contrarian and specific, which makes it useful. Whether it's right on timing or not, the **directionality** shapes every infrastructure bet being made now — including anything touching the horse racing tool or the MT5 pipeline.

## Founders' Personal Stakes

### "I was in a wheelchair and I needed to move to Boston for multiple months and both of my parents decided to move out and drop everything they were doing and live with me" [1:26:16]

The **kindest thing** question lands differently when the answer is this. Useful context — the person building a billion-dollar hardware company made a life-or-death decision at 16 without full use of his legs. That's a different risk tolerance baseline than most.

## Key Arguments

1. **Inference, not training**, is the
   coming market — today a fraction of
   a percent of people use paid AI;
   scaling to billions of concurrent
   users needs hardware built for that
   workload from scratch.

2. **Incumbents over-constrain** designs
   for generality — discarding voltage
   floors, temperature ranges, and
   standard interconnects gives a
   compounding performance edge for
   a focused chip.

3. **Prefetching everything in parallel**
   — software, racks, production lines
   before chips arrive — compressed
   silicon-to-inference from 10 months
   to 40 days; the daily revenue
   opportunity dwarfs the upfront cost.

4. **Wall-clock compression** on long-
   horizon tasks is the real value:
   agent runs that take months shrink
   to days, unlocking qualitatively
   new capability, not just UX gains.

5. **Pure-play focus is a structural moat**
   — hyperscaler chips only need to avoid
   the Nvidia tax; Etched must win or die,
   which drives harder decisions and
   attracts different talent.

6. **Supply chain is a design decision**
   — Gen 1 was placed on a different node
   and memory stack than Nvidia's Rubin,
   making Etched's compute **additive**
   to supply, not competitive with it.

7. **Inference cost must scale sub-linearly**
   — cluster-level economies need to be
   baked into the architecture; proportional
   hardware spend per token is not a
   viable path to mass adoption.

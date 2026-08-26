---
source: notes
source_path: sources/podcasts/invest-like-the-best/2026-08-25-neil-movva-making-ai-10x-cheaper-invest-like-the-best-ep-488.md
source_title: "Neil Movva - Making AI 10x Cheaper - [Invest Like the Best, EP.488]"
source_date: 2026-08-25
show: "Invest Like the Best"
themes: []
generated_at: 2026-08-26T02:09:28+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: Neil Movva - Making AI 10x Cheaper - [Invest Like the Best, EP.488]

## Summary

Neil Movva's core bet is that **background agents** will dominate AI inference, making cost-per-token the only metric that matters at scale.

Today, the industry optimises for chatbot latency. Movva argues this is a fundamental mismatch: GPUs are throughput machines, not low-latency devices. Sail's entire business is built on exploiting that gap.

The strategy is what Movva calls "scavenging." Rather than competing with Anthropic or OpenAI for premium GPU supply, Sail buys hardware nobody else will touch — intermittent power, non-standard chips, 95% uptime data centres. When an agent job runs for hours, a ten-minute GPU failure is irrelevant. That changes the economics entirely.

The latency contract with customers is explicit: average throughput will be highly competitive, but P99 tail latency is uncontrolled. In return, customers get unbeatable pricing. Movva frames this as a mini-mill strategy — distributed, flexible, cheap — versus building one giant monolithic plant.

On the structural side, Movva is bullish that inference spend is real and compounding, not speculative. People use tokens immediately; they don't hoard them. The biggest remaining inefficiency is **attention memory** (the KV cache), which he believes is one to two orders of magnitude away from where it should be — a larger unsolved problem than compute, where MoE has already made progress.

## The Background Agent Thesis

### "The best latency is no latency at all. When you wake up in the morning, the work's already been done overnight." [0:06:46]

The framing is sharp. Most inference companies optimise for speed-of-response; Neil is optimising for **not needing a response at all**. That's a different product category, not just a cheaper one.

### "The GPU is fundamentally a throughput machine... but that's actually not the way that we've taken AI." [0:19:39]

The central technical argument. Every major inference provider optimised for the chatbot shape of demand. Sail is betting that **shape is changing**, and the GPU's native throughput mode is the unlock. Worth watching if this prediction proves right.

### "You'll use 8 times more hardware, but you won't get 8 times the speed. You might get like 4 to 5x the speed." [0:22:06]

The NVLink explanation is the most technically precise moment in the excerpt. **Sublinear scaling** is why throwing more Nvidia GPUs at low-latency problems is expensive and wasteful — and why Sail doesn't bother competing there.

## Why Latency Is the Wrong Goal

### "I only care about absolute numbers. What are we able to do on the chip? How do we achieve that?" [0:18:27]

The "speed of light" culture from his Nvidia days is now Sail's internal standard. Ignoring relative benchmarks and chasing **hardware theoretical maximums** is a discipline most ML infra teams don't enforce. This one matters operationally.

### "I like to say there's no bad chips, there's only bad pricing. I will make any chip work at the right price." [0:44:08]

The core thesis of the whole business model, stated cleanly. Every "Nvidia or bust" buyer is leaving money on the table — and that's the opportunity.

### "We tell our customers, look, our average throughput is going to be very competitive, but our P99, our 99 percentile latency is not going to be controlled. It cannot be and in return I'll give you unbeatable economics." [0:54:57]

Honest, clean trade-off. The
**P99 disclaimer** is the product.
Most infra companies hide tail
latency; Movva makes it the pitch.

## Scavenging Cheap Hardware Supply

### "There's actually a diseconomy of scale to data centers in some way. It's way more expensive and difficult to build a 100,000 GPUs in one data center than it is to build 10,000 than it is to build 1,000." [0:50:04]

Counterintuitive and important. The whole market is still priced around **training-era assumptions** about scale. If inference works fine distributed, the real arbitrage is in small, overlooked power pockets nobody else wants.

### "we will buy any chip anywhere in the world for any duration of time. That is a level of flexibility and liquidity that no one else has." [0:52:45]

The simplest possible expression of the
competitive edge. Most cloud infra
companies optimise for quality of
supply; Movva optimises for **breadth**
of supply. Different game entirely.

### "You have basically zero buyers for a data center that has 95% uptime. I'm that first buyer." [0:53:53]

Classic **contrarian liquidity** play —
being the only willing buyer in a
market that everyone else avoids.
Works only because his control plane
can absorb the failures.

### "We are building a factory. We're trying to build the best steel factory in the world, but it will come through mini mills, not through large monolithic steel plants." [0:56:35]

Good analogy — mini-mill steel
disrupted integrated mills on **cost**,
not on quality. Movva is betting the
same dynamic plays out in compute
infrastructure.

## The Economics of Async Inference

### "I want to have the lowest cost per token in the industry and do that by a mile." [0:04:27]

"By a mile" is doing a lot of work here. He's not positioning as slightly cheaper — he's betting that a **10x cost gap** creates an entirely new product category, not just a price war.

### "People buy tokens because they're immediately valuable to them. You don't hoard tokens, you use them immediately." [0:48:33]

The strongest counter to the dot-com bubble comparison. Inference demand is consumption, not speculation — structurally different from buying Cisco switches for a future internet that didn't arrive on time.

### "I want abundant tokens and diverse harnesses. I want everyone to build their own harness." [1:08:04]

The **vision statement** in two
sentences. Cheap tokens are the
input; personalised agents are the
output. Relevant to Loom — this
world makes per-user intelligence
infrastructure viable.

## Transformer Architecture's Core Flaw

### "I would say the original sin of transformers is that you've taken this extremely fundamentally memory bound layer and juxtaposed it right next to a compute bound layer." [0:32:55]

Sharp framing. The GPU exists as a compromise machine because the architecture demands two incompatible things from silicon simultaneously. This tension is what makes the Cerebras/GPU hybrid argument coherent.

### "I like the argument now that the median model that we serve is so much more advanced than like a random human giving feedback that the signal you get from random human preference, unconditioned human preference, is not actually worth anything." [0:36:24]

This is a big shift if true. RLHF from general users was the engine of the ChatGPT era. The claim that models have **outgrown crowdsourced feedback** has real implications for how alignment work gets done.

## Data, Scale, and Training Limits

### "The internet was a one time subsidy on data. We got it for free. It's extremely high quality, about 30 trillion tokens of high quality text... and we've basically looked at it all already." [0:36:24]

Clean summary of where the pre-training frontier actually is. The internet data well is dry — the next gains come from verifiable RL environments, not scraping more text.

### "Security has become proof of work. When you want secure software, it's really a question of how many dollars did you spend on Anthropic's APIs trying to break into your software." [0:10:44]

The best concrete use-case in the excerpt. Security-as-compute-budget is a genuinely new mental model — and it makes cheap, long-running inference **structurally necessary**, not just nice-to-have.

## Long-Term Vision and Craft

### "from the gate level silicon all the way to building a great Internet scale service, you should aspire to be someone who over the course of your lifetime achieves that level of understanding." [1:16:34]

His professor's advice, but it
doubles as Movva's actual **operating
philosophy**. The whole episode is
evidence he took it seriously.
Rare to find that full-stack
ambition outside of a handful of
people.

## Key Arguments

1. **Background agents beat chatbots** on volume —
   no human attention bottleneck means consumption
   is unbounded; Neil predicts 90/10 split
   (background vs real-time) within a few years.

2. **GPUs are throughput machines** forced into
   low-latency mode — fixing that mismatch
   is the core cost lever Sail pulls.

3. **NVLink is irrelevant for Sail** —
   tensor parallelism only matters for latency;
   skip it and cheaper chips win on flops-per-dollar.

4. **Scavenging beats competing** — don't bid
   against Anthropic/OpenAI for premium supply;
   take the supply they won't touch instead.

5. **Async agents change the latency contract** —
   if a job runs for hours, a 10-min GPU
   failure is irrelevant; unlocks a cheaper
   tier of infrastructure economics entirely.

6. **KV cache / attention memory** is the
   biggest remaining waste — MoE already handles
   compute fairly well; **attention** is where
   the real inefficiency lives, 1-2 OOM off.

7. **Inference spend is non-speculative** —
   structurally different from dot-com;
   demand is compounding and already proven.

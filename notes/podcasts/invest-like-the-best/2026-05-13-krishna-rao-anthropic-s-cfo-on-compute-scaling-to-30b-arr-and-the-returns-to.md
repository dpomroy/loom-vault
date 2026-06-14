---
source: notes
source_path: sources/podcasts/invest-like-the-best/2026-05-13-krishna-rao-anthropic-s-cfo-on-compute-scaling-to-30b-arr-and-the-returns-to.md
source_title: "Krishna Rao - Anthropic's CFO on Compute, Scaling to $30B ARR, and the Returns to Frontier Intelligence - [Invest Like the Best, EP.472]"
source_date: 2026-05-13
show: "Invest Like the Best"
themes: ["AI Market & Investing"]
generated_at: 2026-05-27T21:10:32+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: Krishna Rao - Anthropic's CFO on Compute, Scaling to $30B ARR, and the Returns to Frontier Intelligence - [Invest Like the Best, EP.472]

## Summary

Anthropic's CFO Krishna Rao gives a rare inside view
of how compute actually runs the business.
**Compute is the constraint** — too much kills you,
too little kills you, and the gap between those
outcomes widens exponentially as growth accelerates.

Key points:

- Anthropic went **$9B → $30B run rate** in one quarter
- 90%+ of internal code is written by Claude Code
- They use three chip platforms (Trainium, TPUs, GPUs)
  fungibly — a multi-year engineering investment
- Returns to **frontier intelligence are not slowing**,
  especially in enterprise
- Safety investment turned out to be a business asset,
  not a drag — nine of Fortune 10 now customers
- "Virtual collaborator" is the next product frontier,
  targeting $40T of global knowledge work

Matters because: this is the clearest public account
of what running a frontier AI lab actually looks like
operationally — not the hype, the plumbing.

---

## Quotes

### "The compute that we procure, it's the lifeblood of our business. It is the most important thing in the company. It's like the canvas on which everything else gets built. And so the decisions we make and how much compute to buy are some of the most consequential and hardest decisions to make in the entire company."

Unusual framing from a CFO — normally the CFO talks
about capital allocation in financial terms.
Here the **physical resource is the strategy**.
Everything downstream (models, products, revenue)
is derivative of this one decision.

---

### "If you buy too much computer, you go out of business. If you buy too little compute, you can't serve your customers and you're not at the frontier. Same thing."

The symmetry here is the insight.
Most people only worry about one direction of risk.
**Both failure modes are terminal** — and the
uncertainty window compounds exponentially.

---

### "When you're building and growing a business exponentially, really small movements in monthly or weekly growth rates result in compounding very, very different outcomes. And so as we're thinking ahead even with our revenue growth, it's really hard to predict this business. And it's really hard. I think humans mostly think linearly and you think incrementally."

This is the honest CFO admission buried in the episode.
The **forecasting problem is structural**, not a
skills gap — human cognition isn't wired for this.
Relevant for how you build Loom's ranking models:
linear decay assumptions will consistently underfit
exponential capability jumps.

---

### "What we found very consistently is by releasing new models that TAM is unlocked in a unique way. More TAM gets unlocked, more use cases are possible. And a good illustration of that is this last four months that we've had at the company, right? We started the year with about $9 billion of run rate revenue and we ended the quarter with north of $30 billion of run rate revenue. That kind of a change is really enabled by these model intelligence leaps and then the products that we build around them."

$9B to $30B ARR in four months.
That number deserves to sit on its own line.
The mechanism — **TAM unlocked by capability jumps**
rather than by sales motion — is the core thesis.
It also means traditional enterprise growth playbooks
are the wrong frame entirely.

---

### "Right now within the company, 90 plus percent of our code is actually written by Claude code. A lot of Claude code's code is written by cloud code. And so you think of this as why do we allocate compute internally? Why would we forego revenue for it? It's because the models themselves are helping us to build that next generation of models."

The recursive loop is real and already operating,
not theoretical.
**Forgoing revenue to feed internal compute** is the
counter-intuitive capital allocation decision that
most finance people would never approve — and it's
apparently the right call.

---

### "We talk a lot about how talent density beats talent mass, and I think that's true here. We want the densest collection of AI research talent and inference engineering talent, and that enabled with the Best models is a really winning combination."

This phrase — **density over mass** — is the
hiring philosophy in four words.
Worth holding onto for Loom: a small, high-signal
feed beats a large noisy one on the same principle.

---

### "Changing the pricing for Opus, you see this Jevons paradox, we lowered the price of it, but the consumption went up way, way more than what you would have expected. And so because we hit that sweet spot for customers, they were able to use it a lot more. We had the efficiency to be able to serve it to customers at scale. And then they were able to build that into their workload such that when we released Opus 4.6, it's a model improvement. They can slot it in. We didn't change the price."

**Jevons Paradox applied to AI tokens** — lower
price → more usage → stickier integration →
price stability on next release.
The strategy is to colonise the workload, not
maximise per-token margin. Sensible long game.

---

### "Today all of our legal entities, we can produce the statutory financial statements using claude. And yes, a human checks it, but all of those financial statements are produced with claude. We also have a more real time platform called Ant Stats and it used to take a lot of time to sift through all the data, get to conclusions, write a memo about it, or publish a regular report on what's happening over the course of the day, what's driving it. We now have a library of skills for CLAUDE that are specific to finance. Last I checked there were over 70 of them that everyone can kind of access through this common repository. And on top of that we built an mfr, a monthly financial review skill, and it can produce our monthly financial review. It's 90 to 95% ready."

The most concrete internal deployment example in
the episode. **70 domain-specific skills** in a
shared library is a genuine org design decision,
not just "we use Claude a lot."
Statutory financials produced by the model is the
kind of claim that would have been laughed out of
a boardroom 18 months ago.

---

### "The last linkage, if you're selling to enterprises, we now sell to nine of the Fortune 10. All of those enterprises are entrusting us with customer information, their data, they're interacting with their employees, sometimes even interacting with their customers as well. Those are the most sensitive workloads. More and more of these businesses are running on Claude and our cloud platform. When you have this investment that we made, and we'll continue to make in safety, interpretability, alignment, that actually inerts the benefit of the enterprise customers as well, and all of our customers, because they want that."

The **safety-as-moat argument** is the most
underappreciated claim in the episode.
Interpretability research that started as a mission
commitment turned into a genuine enterprise sales
differentiator. That's a real flywheel, not spin.

---

### "I think it is towards this vision or this goal of a virtual collaborator. And so think of this as something that has context within your organization, that can use all of the tools that are specific to you, whether they be homegrown tools or tools that you purchase, that has memory and the ability to effectively learn from mistakes you've made, but also mistakes that it's made over time. The ability to work over a very long time horizon on not just a task, but an actual idea."

**"Virtual collaborator"** is where the product
roadmap is pointing. The key attributes are:
org-specific context, tool access, persistent
memory, long-horizon tasking.
This is the job spec for what agents need to become
— relevant framing for any agentic work you're
building.

---

### "The capability and the use cases are playing catch up to where the model is. We are talking about humans in large organizations with a set of tools and practices and things that they've been doing for a really long time. Change is hard to extent that that diffusion hits a wall or slows down or something like that. That could affect the rate of change in terms of revenue growth, the scaling laws slowing down or not holding."

Rare moment of candour — the CFO naming the
**actual bear case** rather than deflecting.
The diffusion risk (human/org inertia) is distinct
from the capability risk (scaling laws). Both are
real. Most analysts conflate them.

---

## Key Arguments

1. **Compute is not a cost line — it's a fungible
   strategic asset.** The same chips run inference
   in the morning and model training in the evening.
   Treating it as a variable cost (as investors tend
   to) fundamentally misrepresents the business.

2. **Returns to frontier intelligence are
   compounding, not diminishing.** Each model
   generation unlocks new TAM rather than serving
   the same customers more cheaply. The $9B → $30B
   ARR move in one quarter is the evidence.

3. **Recursive self-improvement is already
   operational.** 90%+ of code is written by Claude;
   Claude Code writes its own code. Internal compute
   allocation is a deliberate choice to sacrifice
   near-term revenue for faster capability development.

4. **Safety investment became a competitive moat.**
   Interpretability and alignment research — done
   for mission reasons — turned out to make better
   models and made Anthropic trustworthy enough to
   win the most sensitive enterprise workloads.

5. **The "virtual collaborator" is the next product
   unlock.** $40T of global knowledge work is the
   target. The pattern from coding (rapid adoption
   once capability threshold crossed) is expected
   to repeat across every knowledge domain.

---
source: notes
source_path: sources/podcasts/all-in/2026-06-06-the-ipo-comeback-why-tech-giants-are-finally-going-public-all-in-liquidity-ipo.md
source_title: "The IPO Comeback: Why Tech Giants Are Finally Going Public | All-In Liquidity IPO Panel"
source_date: 2026-06-06
show: "All-In"
themes: ["AI & Software Now", "Misc"]
generated_at: 2026-06-07T02:05:25+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: The IPO Comeback: Why Tech Giants Are Finally Going Public | All-In Liquidity IPO Panel

## Summary

**Going public is overrated as an event,
underrated as a long-term strategic move.**

Two recently-IPO'd CEOs — Cerebras
(AI silicon) and Planet Labs (Earth
imaging) — give an unvarnished read on
what going public actually changes
(credibility, liquidity, employee morale)
vs. what it doesn't (your vendor
relationships, your engineering backlog).

Key sub-plots worth tracking:

- **Space-based data centers** may be
  economically inevitable within ~5 years
  if Starship hits cost targets
- **Cerebras' wafer-scale chip** is
  15–18× faster than GPU for inference
  — a genuine architectural divergence,
  not marketing
- The "stay private forever" era is
  ending; the pendulum is swinging back
  toward earlier IPOs

Relevant to Loom: both the
compute-infrastructure angle (Cerebras)
and the real-world data angle (Planet)
touch on where AI goes next.

## Quotes

### "I think it's really difficult to overestimate the amount of garbage that's involved in going public." [0:03:04]

Feldman's framing: 130 people on a Zoom, commas moving in documents, zero value added. Refreshing honesty from someone who just did it. Worth remembering next time the IPO narrative gets romanticised.

### "Your engineering projects have made no progress since the day you weren't public." [0:03:04]

You go back to work, you have new constituents to address, but the core business is unchanged — more money in the bank, and that's about it. The anti-hype take. The IPO is a financing event, not a transformation.

### "Going public gives you access to liquidity for early shareholders, whether that's the early employees or early investors." [0:08:22]

It gives cash to the company and — importantly — credibility: customers like governments and large agricultural players need to know you're going to be around. The legitimacy angle is under-discussed. It's not just capital — it's a signal of permanence to risk-averse buyers.

### "AI is only as good as the data it's trained upon." [0:11:28]

AI is reducing the barrier to entry so more people can access Earth observation data — but the models still need the underlying data to be any good. Obvious once stated, but a strong counterpoint to pure-model hype. Data scarcity is still a real moat.

### "A thing that people don't know that is actually perhaps more important is that we've had a miniaturization of satellites so that the same satellite that used to cost a billion dollars and weighed 20 tons now costs a few kilograms." [0:12:10]

It's the mainframe-to-desktop revolution for space — and just like that transition, it's unlocking loads of new applications. The launch cost narrative gets all the attention (SpaceX/Starship). The miniaturisation story is the quieter, arguably bigger enabler.

### "When launch costs come down to about $200 to $300 a kilogram, it would be cheaper, just simply cheaper to put the data centers in space." [0:14:26]

Currently sitting just over $1,000/kg; that's down ~10× in 10 years. On current Starship trajectory, Marshall expects the threshold in two to three years. If this is even half right, it's one of the bigger infrastructure shifts of the decade. The solar panel angle — sun-synchronous orbit means 24/7 sun exposure, five times more energy per panel than ground-based, no batteries needed — is the part most people miss.

### "If you build a GPU, the odds that you're better than Nvidia and AMD are approximately zero." [0:21:57]

If you want to be 20× better, your architecture can't look like theirs — they've already eaten all the low-hanging fruit. That's what led Cerebras to a fundamentally different approach. Clean first-principles reasoning. The same logic applies to any competitive market: copying the leader's architecture is a guaranteed loss.

### "How big is the market for slow search today? Zero." [0:24:47]

Zero. How big is the market for dial-up? Zero. You won't wait for AI — it has to be delivered in real time. That's what they built for. The cleanest articulation of why inference speed is a product requirement, not a benchmark. Directly relevant if Loom ever surfaces AI-generated content in real time.

### "I think historically more money is made after IPO than before." [0:27:39]

Every study shows it — both in percentage terms and in absolute dollars. The amount of money you can put to work in most venture companies pre-IPO is modest; post-IPO, when things are going well, the opportunity is vastly larger. Counter-intuitive for most LP mental models. The Planet Labs 10× in the public markets is the proof of concept cited here.

### "All the cool stuff that we're doing with LLMs now is really based on just the text of the Internet being absorbed into these models. But they don't know shit about the real world." [0:31:11]

They don't know about the farm field, the flood, the security situation around the corner. Give them real-world data and they can answer real-world problems — opening up a massive new class of applications. "Large Earth Models" vs Large Language Models is Marshall's framing. Whether or not Planet Labs captures that value, the underlying point — that current AI is text-native and world-blind — is a legitimate gap.

## Key Arguments

1. **Going public changes optics, not
   operations.** The business fundamentals
   — vendor relationships, engineering
   progress, customer pipeline — are
   identical the day after IPO. What you
   gain is capital, credibility with
   risk-averse buyers, and employee
   closure. That's it.

2. **Space infrastructure is approaching
   an economic tipping point.** Satellite
   miniaturisation + falling launch costs
   are compounding. When Starship drives
   costs to ~$200–300/kg, terrestrial
   data centres may lose their cost
   advantage — a structural shift, not
   a science-fiction scenario.

3. **Cerebras' wafer-scale bet was an
   architectural necessity, not a gimmick.**
   The core insight: if the bottleneck is
   moving data from memory to compute,
   and you want 20× improvement, you can't
   build a better GPU — you have to
   rethink the physical layout entirely.

4. **The "stay private forever" era is
   ending.** The decade of Andreessen-style
   "stay private" advice produced a handful
   of trillion-dollar exceptions (OpenAI,
   SpaceX) and a lot of locked-up LP
   capital. Planet Labs' 10× post-IPO
   move is the counter-narrative now
   circulating in VC circles.

5. **LLMs are world-blind; real-world
   sensor data is the next training
   frontier.** Current models are trained
   on text. Satellite imagery, sensor
   networks, and time-series Earth data
   represent an entirely different input
   class — and whoever owns that data
   layer has a structural advantage as
   AI moves from language tasks to
   physical-world reasoning.

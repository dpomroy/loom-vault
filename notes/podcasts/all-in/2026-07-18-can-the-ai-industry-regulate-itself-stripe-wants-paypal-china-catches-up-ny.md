---
source: notes
source_path: sources/podcasts/all-in/2026-07-18-can-the-ai-industry-regulate-itself-stripe-wants-paypal-china-catches-up-ny.md
source_title: "Can the AI Industry Regulate Itself? Stripe Wants PayPal, China Catches Up, NY Bans Datacenters"
source_date: 2026-07-18
show: "All-In"
themes: ["AI & Technology Landscape", "Misc"]
generated_at: 2026-07-19T02:04:53+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: Can the AI Industry Regulate Itself? Stripe Wants PayPal, China Catches Up, NY Bans Datacenters

## Summary

The hosts conclude that **industry self-regulation** is the right answer on AI oversight — but only if it genuinely replaces government bureaucracy rather than stacking on top of it.

The case against government control is straightforward. Regulators lack the technical expertise, and models are evolving too fast for any approval queue to keep pace. A FINRA-style SRO could work, but only if it covers frontier models and catastrophic risks exclusively, and includes startups alongside the big labs.

The more pointed argument is about **Anthropic's motives**. The hosts read its state-by-state regulatory push not as safety altruism but as a deliberate incumbency strategy — compliance costs that large labs can absorb and smaller competitors cannot. The formula, as one host puts it bluntly: brand as safe, ban the unsafe, profit.

On payments, the Stripe/Block/Advent bid for PayPal is framed as less about rescuing a declining product and more about what the combination unlocks. PayPal's 700 million accounts plus Stripe's merchant rails plus stablecoin infrastructure equals a credible challenger to Visa and Mastercard — something none of the three could build alone.

Two quieter risks get serious treatment. Enterprise AI spending is growing 21x year-on-year, and "zero data retention" settings cannot actually be trusted — making token costs and data leakage underpriced CFO problems. New York's data-center moratorium compounds this: a pause of any length translates to a five-year-plus compute gap, and the hosts flag possible foreign influence operations amplifying the opposition. The episode closes on a genuine positive — an AI-designed enzyme that reversed elderly skin tissue to the biological age of a 31-year-old.

## Why Governments Can't Regulate AI

### "The government does not have the expertise to evaluate AI models. The criteria are changing too rapidly. You're going to very rapidly end up with a queue where all the models would be waiting to get tested." [0:07:16]

The core argument against an FAA-style agency. Sacks is right — the moment you centralise model approval in government hands, you've handed a veto to whoever controls the queue. Speed asymmetry alone kills American competitiveness.

### "This should be a substitute for a new regulatory agency. If it's just additive, then it defeats the purpose and there's no real reason to support it." [0:07:16]

Sacks's fifth condition for the SRO. This is the load-bearing clause the whole thing hinges on. Every other condition is negotiable; this one isn't. If the SRO layers on top of existing oversight, you've just built the DMV with extra steps.

## Anthropic's Incumbency Play

### "AI giant Anthropic is pursuing a strategy of one upmanship that encourages states to impose increasingly tougher AI guardrails rather than align around a single set of regulations." [0:16:00]

Sacks quoting the Politico piece directly. This is the sharpest data point in the segment. Anthropic isn't pushing for clarity — they're deliberately ratcheting state-by-state to create a patchwork that only a well-resourced incumbent can navigate.

### "At some point I think these companies are going to have to grow a spine and fight and decide where they're willing to draw a line." [0:16:00]

Sacks on what the industry needs to do. Blunt and probably correct. Every concession so far has been read by regulators as an invitation for more. The SRO only works if it comes with a credible "this is the line" commitment, not just goodwill gestures.

### "Brand yourself as a safe AI company. Ban unsafe AI. Three, profit." [1:21:14]

This is the sharpest line in the excerpt.
Sacks is saying Dario's safety panic may be
**strategic positioning** as much as genuine
belief. Hard to fully dismiss.

## The PayPal Acquisition Logic

### "What is the only kind of baby that Advent and Stripe and Block could have together? You are creating a competitor to Visa and Mastercard." [0:22:32]

Chamath's framing of the PayPal deal's real upside. Most coverage is treating this as a turnaround play. Chamath's read is more interesting — **700M accounts + stablecoin rails + Stripe's risk infra** is a serious shot at displacing card networks. That's a different category of ambition entirely.

### "I think eBay and PayPal are probably the beginning of a wave of megadeals of call it flaccid digital businesses that can be revived with the blue chew of capital and the right operator." [0:27:32]

Chamath's prediction on what comes next. The thesis is clean: founder-less, AI-naive, network-rich legacy platforms are undervalued relative to what a good AI-native operator could extract. **Bending Spoons** at smaller scale is the proof of concept. Worth watching which stalled Web 2.0 assets fit this pattern — relevant to how I think about market structure more broadly.

### "it's a misnomer to call it the PayPal mafia. It's really the PayPal diaspora, totally. Our homeland was taken over and they burned our temple and then kicked everybody out." [0:32:01]

Sacks reframes the "PayPal mafia" myth entirely. The founders didn't conquer — they were expelled. That distinction matters: the diaspora framing explains *why* they scattered so productively, not because they're sharks but because they had nowhere else to go.

### "the existential issue for PayPal is that you're dealing with a product that's 25 years old. I mean, it's the same thing that we created back, you know, like, 27 years ago. I mean, it's changed a little bit, but not that much." [0:33:38]

Sacks puts the acquisition thesis in perspective — you can use AI to cut costs and make the numbers work, but the product itself is a legacy interaction model. Buying users is fine; buying a dead product vision is a trap. The honest answer is nobody has a plan to fix that yet.

## Enterprise AI Data Risk

### "if you think that you're going to flip a ZDR switch, zero data retention, which is the magic term that the industry uses to tell you that everything's going to be okay, I think the answer and the message should be it's not going to be okay because you can't guarantee any of it." [0:45:10]

Chamath's sharpest point in the excerpt. Zero data retention is a **promise**, not a proof — and the Grok Build incident demonstrates exactly how quietly it fails. Anyone building on third-party AI infra for sensitive workloads should treat ZDR claims as aspirational at best.

### "there are all kinds of non obvious data leak vectors lurking in AI." [0:45:10]

Short, but load-bearing. The Grok incident wasn't malice — it was a privacy setting that silently didn't work. That's the **scarier** failure mode than intentional data harvesting, because you can't audit for what you don't know is leaking.

## Token Costs as a CFO Problem

### "token spend among ramp customers has grown by 21 times." [0:49:54]

Not 21%. **21x.** In one year. The Ramp CEO drops this number casually but it's the most consequential data point in the excerpt — it explains why CFO tooling for AI spend is suddenly a real product category, and why unmanaged token costs are a coming earnings surprise for public companies.

## New York's Data-Center Moratorium

### "a typical data center uses the same amount of water as two and a half in and out burgers." [1:01:57]

Sacks is debunking Hochul's moratorium point by point. The water argument — often the strongest-sounding environmental objection — collapses on contact with an actual benchmark. The NY ban looks more like **regulatory theatre** than evidence-based policy when you run the numbers.

### "These data centers have become the scapegoat for all of the angst that people have about AI and it's kind of become this very clumsy way of trying to throw a wrench in the gears of innovation" [1:02:37]

The framing here is right. The regulatory
pressure isn't principled — it's displacement
activity from people who can't regulate the
model directly.

### "The number one thing slowing down the growth of Anthropic's revenue, it's not demand, I think it's the availability of compute and data centers" [1:05:36]

Anthropic funding groups that obstruct data
center construction is genuinely self-defeating
— unless the regulatory capture theory is correct.
That's the more troubling read.

### "When you start talking about a moratorium on data centers, it's not like a few month pause. It's probably a good five years at least before you can get another data center switched on in the state of New York." [1:07:09]

The lag is the killer detail.
A political moratorium held for 2-3 years translates
to **5+ years** of lost capacity. That's not a
pause — that's a structural setback.

## Foreign Influence in the AI Debate

### "PRC linked influence operations are targeting AI debates in the US" [1:15:04]

OpenAI published this claim a month before
this episode. Whether or not you accept the
GMO-Russia Today parallel, the incentive structure
is obvious: **slow US infra, win the AI race**.

## An AI Biotech Breakthrough

### "They took actual human skin from elderly patients that had donated their skin, and they put this enzyme onto that skin and they were able to eliminate 55% of the CML on the skin, which basically reversed the skin's age down to the age of a 31 year old." [1:24:01]

AlphaFold-driven directed evolution produced a
novel enzyme that doesn't exist in nature.
This is the **concrete AI benefit** the rest of
the episode was arguing we'd forfeit if we
strangle compute infrastructure.

## Key Arguments

1. **Industry SRO beats government regulation** —
   but only if it covers frontier models and
   catastrophic risks only, includes startups
   and open source, starts voluntary, and
   *replaces* rather than layers on top of
   existing oversight.

2. **Anthropic's regulatory strategy** is a
   deliberate incumbency ratchet — state-by-state
   compliance costs that entrench large labs
   and price out smaller competitors and
   open source. Framed as safety; functions
   as a moat.

3. **PayPal is cheap, not fixed** — the deal
   is driven by an 85%+ market cap collapse,
   not a product vision. The real prize:
   combining PayPal's 700M accounts with
   Stripe's merchant rails to bypass card
   networks entirely.

4. **AI data privacy guarantees can't be
   trusted at face value** — the Grok Build
   leak shows "zero retention" settings can
   silently fail. Independent orchestration
   layers are the only defensible enterprise
   architecture.

5. **Token cost disparity is an underpriced
   CFO risk** — frontier models cost 50–100x
   more than open/Chinese alternatives, and
   enterprise token spend is growing 21x
   year-on-year. Rate-limiting tooling is
   now a real product category.

6. **NY's data-center moratorium creates a
   5+ year compute deficit** — 40% of US
   projects already mothballed; hosts flag
   possible foreign influence ops amplifying
   the opposition, mirroring past campaigns
   against GMOs and nuclear.

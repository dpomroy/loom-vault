---
source: notes
source_path: sources/podcasts/david-senra/2026-09-09-mati-staniszewski-on-elevenlabs-voice-ai-building-the-communication-layer-for-ai.md
source_title: "Mati Staniszewski on ElevenLabs, Voice AI & Building the Communication Layer for AI"
source_date: 2026-09-09
show: "David Senra"
themes: []
generated_at: 2026-09-13T02:02:48+00:00
agent: note-taker
model: claude-sonnet-4-6
---

# Notes: Mati Staniszewski on ElevenLabs, Voice AI & Building the Communication Layer for AI

## Summary

ElevenLabs was built to fix bad Polish dubbing — but Mati Staniszewski and his co-founder shipped nothing until the underlying **speech generation** was actually good enough to be worth shipping.

The company defines itself as a research lab first. It builds frontier audio models, then deploys them through product. Crucially, it stays narrow by design: if the bottleneck in a problem is not audio, ElevenLabs does not touch it. They explicitly avoid intelligence, knowledge work, and coding — domains where bigger labs have more compute and more data.

Their go-to-market mirrors Palantir's: field deployment engineers embedded inside customer teams, stretching the product to solve real problems, then carrying that knowledge back into R&D. Without the return loop, Mati argues, it is just expensive consulting.

The deeper claim is about **voice as interface**. For decades, humans learned machine language — keyboards, code, command lines. Voice flips that. It lets technology finally learn ours. The next bottleneck to mass AI adoption is not intelligence; it is communication. A small detail makes the case: adding ums and pauses to a voice agent measurably increased engagement. Authenticity outperforms polish.

The ceiling is not commercial automation. It is restoration — giving back a voice lost to ALS or cancer, returning a person's presence to the world. Senra closes the episode on conviction: if you love what you do, no one can pay you to stop. The right founder, at the right moment, has no sell price.

## Origin: Dubbing Frustration

### "we started in 2022 with his longtime friend Piotr Dąbkowski. He explains how a frustration with poorly dubbed content in Poland led them to build frontier speech technology" [0:02:59]

The origin story is unusually concrete — not "we spotted a market gap" but a lived annoyance: one voice narrating an entire film, all emotion stripped out. Good founders find problems they can't stop thinking about. This qualifies.

### "we realized there are three steps in dubbing process. There is transcription step, then it's translation step to another language and then you need to regenerate that in another language. But the research that existed at the time for each of those steps wasn't very good." [0:05:11]

They didn't pivot away from dubbing because the market was wrong — they pivoted because the underlying research wasn't ready. That's a different kind of discipline: knowing when to solve prerequisites instead of forcing the end goal.

### "before we can solve dubbing, let's solve the research component to generate speech and make it sound great." [0:07:07]

Classic constraint-first thinking — strip the problem to its hardest unsolved piece and own that. Most founders chase the full vision prematurely. Mati and Piotr went one level deeper.

## Research Lab, Narrow by Design

### "the general philosophy is like a lot of small teams, usually less than 10 people having flexibility, autonomy to just run ahead and apply their best judgment in what we can solve for the customer." [0:12:45]

Relevant for Loom — small autonomous units beat coordinated bureaucracy when the problem space is fast-moving. The Honda R&D parallel Senra draws here is apt: separate the invention layer from the deployment layer.

### "when we think about new product, the big question is do we think we have a unique advantage by applying our audio models in that product experience?" [0:16:15]

This is a clean decision filter — not "is this a big market" but "does our core capability create the advantage here." Most companies don't have a filter this crisp. Worth stealing as a framework.

### "we explicitly are not planning to touch any of the intelligence or knowledge work or coding. Not our strength, not our domain" [0:22:35]

Saying out loud what you won't do is harder than it sounds — especially when the adjacent markets are enormous. The restraint here is the strategy.

## Field Deployment Engineers

### "you want all the FDEs to actually solve the customer problem and stretch your product in that direction... bring any of that knowledge back to the product so the product becomes better for the next generation of companies building on top of it" [0:32:17]

This is the Palantir playbook made explicit. FDEs as a
product feedback mechanism, not just a sales aid — most
companies only do the first half and call it services.

The second step is the compounding one. Most SaaS companies
miss it entirely and wonder why churn is high.

## Why Voice Carries More Than Text

### "the voice carries such an additional element of emotional impact, of recognition. The moment you hear someone's voice, you recognize it." [0:49:46]

This is the core thesis behind the whole company dressed up
as an anecdote. Voice isn't just audio — it's identity.

Relevant to Loom: if the feed ever gains an audio layer,
**recognition and emotional resonance** are the differentiators
worth designing around, not fidelity.

### "the ums, the ums, the pauses. And suddenly the performance of working with that voice agent skyrocketed." [0:54:25]

Counter-intuitive but empirically backed: **imperfection
signals humanity**, and humanity drives engagement.

Perfection is a liability in conversational AI. The uncanny
valley runs both ways — too clean and people disengage.

### "text, of course, you imagine you interpret. But it doesn't have the emotion, it doesn't have the intonation, doesn't have the imperfections. It doesn't have the pauses." [0:53:45]

Clean summary of what voice adds dimensionally over text.
**Four properties** — emotion, intonation, imperfection,
pauses — none of which text can replicate.

Worth keeping as a reference quote when anyone questions
why voice AI is a distinct research problem from LLMs.

## Going All In

### "AI is changing the world. We can build the frontier of that change. We are going all in." [0:56:59]

Asked if he'll sell. Three sentences. No hedging.

Senra immediately follows with the sharper version of this
argument — **don't sell your best idea at 31** — but Mati's
answer is the one that matters here.

### "highly likely, like 11 labs is probably the best idea you will ever have in your life... you're gonna sell your best idea at 31. You got four decades ahead of you, maybe five." [1:00:13]

Senra's real point isn't about ElevenLabs specifically —
it's that **founders systematically underestimate the
opportunity cost** of selling the one idea that actually
worked.

Founders who sell early optimise for certainty. The ones
worth studying stayed in the game.

### "If you love what you do, they couldn't pay you to stop." [1:00:27]

The framing here is sharper than the usual
"do what you love" cliché.
David's distinguishing between intrinsic
motivation and something stronger —
**resistance to exit**.
It's a useful filter for co-founders and hires.

## Voice as the Next Interface

### "The next bottleneck of how you actually get access to that intelligence will be how you communicate with that intelligence." [1:04:08]

This is ElevenLabs' core thesis stated cleanly.
If true, voice infra is **infrastructure-layer**
valuable — not a feature.
Worth tracking whether the market prices
this in over the next 12–18 months.

### "For the decades, we learned how technology around works and learned the language of that technology." [1:04:29]

The keyboard, coding languages, GUIs —
all required humans to **adapt to machines**.
Mati's bet is the inversion is finally here.
Strong framing; the question is whether
LLMs are actually good enough yet to
deliver on it without constant friction.

### "The circus part that you mentioned that you feel you're doing something important. It's completely unimportant." [1:08:24]

Mati validates David's "stay away from the
circus" rule — then immediately explains
**why he still goes** (pre-arranged sales meetings).
The nuance matters: it's not conferences
that are useless, it's unstructured attendance.
Practically relevant for Loom's outreach
thinking too.

## Logistics & Future Vision

### "You need to pre arrange a lot of the one on ones you want to do during the conference." [1:08:55]

The operative word is **pre-arrange** —
treat the event as the forcing function,
not the content.
Clean tactical rule. Applies anywhere
you're trading time for access.

### "We will enable everyone out there to have Babelfish in their existing devices, existing presence, existing work." [1:06:27]

The Hitchhiker's Guide reference reveals
the **original north star**: not to build
a single product, but to be the layer
underneath everyone else's products.
Platform ambition dressed as a feature —
that's the right kind of dangerous.

## Key Arguments

1. **Research lab first, product second**
   ElevenLabs builds frontier audio models,
   then deploys them via product — narrow
   by design, so they never compete where
   bigger labs have more compute and data.

2. **Focus is the moat**
   Staying exclusively in audio is a filter:
   if the bottleneck in a problem isn't audio,
   they don't build it.

3. **Ship timing matters**
   Dubbing required solving speech generation
   first. Shipping early on unready research
   would have wasted the opportunity entirely.

4. **FDEs belong inside product, not sales**
   Embed → learn → abstract → improve.
   Without the return step it's just expensive
   consulting, not a product company.

5. **Voice is identity**
   Restoring a voice lost to ALS or cancer
   restores a person's presence in the world.
   That's the product's actual ceiling —
   not commercial automation.

6. **Imperfection is a feature**
   Adding ums and pauses to voice agents
   measurably increased engagement.
   Authenticity beats polish in human
   and synthetic communication alike.

7. **Voice is the next primary interface**
   The bottleneck to mass AI adoption is
   communication. Voice resets decades of
   humans learning keyboards and code —
   technology finally learns our language.

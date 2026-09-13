---
source: podcast
show: "David Senra"
show_slug: david-senra
spotify_episode_id: "1PXS9dsGQuCcAgpNZcF1MB"
date: 2026-09-09
duration_min: 71
url: "https://open.spotify.com/episode/1PXS9dsGQuCcAgpNZcF1MB"
title: "Mati Staniszewski on ElevenLabs, Voice AI & Building the Communication Layer for AI"
transcript_source: "paid"
transcript_status: paid
transcript_url: "https://traffic.megaphone.fm/SCIM9642421723.mp3"
guests: []
---

# Mati Staniszewski on ElevenLabs, Voice AI & Building the Communication Layer for AI

## Description

Mati Staniszewski is the co-founder of ElevenLabs, an AI audio company he started in 2022 with his longtime friend Piotr Dąbkowski. He explains how a frustration with poorly dubbed content in Poland led them to build frontier speech technology, why ElevenLabs combines audio research with product deployment and how its focus on voice shapes where the company chooses to compete. Mati also describes the Palantir-inspired operating model behind ElevenLabs: small autonomous teams, a flat organization and forward deployed engineers who work directly with customers and feed what they learn back into the product. He discusses using AI to amplify human potential, helping people who have lost their voices speak again, why imperfections can make AI voices feel more human and his belief that voice will become one of the primary ways people interact with AI. After turning down multiple acquisition offers, Mati says he and Piotr are committed to building ElevenLabs independently and pursuing what they see as a rare opportunity to reshape how humans communicate with technology. Show notes: https://www.davidenra.com/mati-staniszewski Made possible by Ramp: https://ramp.com Deel: https://deel.com/senra AppLovin: https://applovin.com/senra Chapters (00:00:00) Building an AI-Native Company Before ChatGPT (00:02:59) Why ElevenLabs Started With Audio & Dubbing (00:12:37) Research + Product Deployment: How ElevenLabs Is Built (00:16:15) Focus as a Competitive Advantage (00:18:47) Building an Ecosystem Around Voice (00:22:25) The Communication Platform & Deutsche Telekom (00:28:29) Forward Deployed Engineers & Lessons From Palantir (00:33:41) Flat Organizations, Transparency & AI-Native Management (00:37:19) Small Teams & Putting Engineers Everywhere (00:43:00) Where ElevenLabs Is Growing Fastest (00:44:38) Taste, Art & Science in AI (00:48:23) Using AI to Amplify Human Potential (00:55:19) Becoming an Entrepreneur & Building With Piotr (00:56:49) Why Mati Won't Sell ElevenLabs (01:04:01) Voice as the Interface for AI (01:06:49) Turning Conferences Into a Business Tool Learn more about your ad choices. Visit megaphone.fm/adchoices

## Transcript

**Speaker A** [0:00:02]: We ran into each other at Michael Dell's event a few months ago and you're like, oh, I'm very curious how building a company today is different from building one in the past. And Michael has 40 plus years of experience, he's been dominating for decades. And when I saw him, we had like a 30 minute conversation about this. You read all these biographies of history, skills, entrepreneurs and you just see this over and over again. It's like, oh, this time is different. Turns out, no, this time is not different. And Michael's like, no, no, I actually think this time is different. So I want to start with like how you think about building your company. AI native from today.

**Speaker B** [0:00:35]: Yeah, Michael is a legend. He must have so many interesting perspectives, especially like he's still running the company. So it will be interesting whether he applies some of that difference to the current running of the show. But for us in some ways, given we are first time founders, me and Piotr, my co founder, my best friend of 15 years, ElevenLabs is the first venture we started.

**Speaker A** [0:00:59]: That's insane. You started in 2022, you launched before the first version of ChatGPT, right?

**Speaker B** [0:01:05]: We did. It was still a year when the topics of the day were crypto and metaverse. So 2022 was still a year where everybody was obsessed about those two. So it was a perfect time because we could actually focus and build a lot on the AI side, what were

**Speaker A** [0:01:21]: you doing before you founded this company?

**Speaker B** [0:01:23]: I was a pioneer so I was helping build optimization models and bring optimization models to the customers. So NHS during the COVID response on how distribute vaccines across UK or working with oil and gas industry and figuring out how to optimize the energy work. So a lot of optimization models and then working with customers on actually figuring out how you bring that into their production. And my co founder was at Google and he did a lot of the text models for Knowledge graph. Before that did research at university around image visual models. So incredible. Brained the smartest person I know for developing a lot of the research work and I was happily on that intersection of building the product and bringing that to the customers. So that was before Palantir's BlackRock building risk models, bringing that to customers and by background studying mathematics. So good intersection of the things I liked and now at the level labs that's also what I do and that's also from the company lens. When we started that was the whole goal of like can we combine research and product deployment under one hood. On the research side built all the audio models Starting with model to produce speech, text to speech model. And that was that 2022, the first model that could finally cross that human like quality. And then over time now it's entirety of audio models, transcription models, localization models, orchestration for voice, conversations with agents. And then on the product side, can we unify that as one platform that helps people businesses transform how they would communicate with their audience.

**Speaker A** [0:02:55]: Wait, so the first idea you started with audio.

**Speaker B** [0:02:58]: We started.

**Speaker C** [0:02:58]: Why?

**Speaker B** [0:02:59]: The actual trigger point comes from where you're from, From Poland. Very peculiar thing. If you watch a movie in Polish, all the voices, whether it's a male voice or whether it's a female voice, get narrated with one single character. So you have one voice narrating the whole movie, all the emotional intonation disappears and it's still. So we grew up with this. Everybody in Poland groups with it. One person dubbing. And then in 2021 we retested or re experienced this still happening in that content. And then second thing happened which was

**Speaker A** [0:03:34]: it was still happening in movies in 2021 that you'd watch in Poland.

**Speaker B** [0:03:37]: Yes.

**Speaker A** [0:03:38]: Same thing that was happening when you were a kid.

**Speaker B** [0:03:40]: Exactly.

**Speaker C** [0:03:40]: Okay.

**Speaker B** [0:03:40]: And it's crazy because of course it's cheaper, easier to do, quicker timeline, but the quality is poor. As you can imagine. It's a pretty terrible experience. And that was like a trigger point. In the future, that experience will be completely different. You will have original voice, original emotions, original intonation and actually be able to experience that in that incredible way. Which is very timely because just a week ago we released finally a model that is able to do that extremely well and finally bring the content from one language to another. But maybe more broadly, that was also our eye opening of how we interact with technology. How you can interact with technology will change and that will apply the language barrier that will break, but also just the general conversations with devices with digital world will happen differently across different modalities, across different channels. And we wanted to.

**Speaker A** [0:04:32]: This is what you thought back in 2022 or what you think today?

**Speaker B** [0:04:34]: In 2022, we knew that you will need to unlock the stories, the content across the modalities and channels. We didn't yet know how quickly the kind of the shift from static to interactive will happen. We hope this will happen, but we didn't know how quickly.

**Speaker A** [0:04:48]: So the first idea was. First idea was dub static content that I was watching. I'm watching a movie in Poland. I want this to actually feel like I'm watching in my native language.

**Speaker B** [0:04:58]: Exactly.

**Speaker A** [0:04:59]: That had to be appear like a tiny Business though, right at the time, like if that's your initial idea, you weren't going into it thinking this is going to be a giant business. Like you're one of the fastest growing startups today.

**Speaker B** [0:05:11]: You know, we actually thought it was a huge business at the time too. So we thought it's like if we think about all the content, all the stories out there, how incredible if they were available in audio and whether it's some of the biggest streaming companies, whether that's tv, whether that's the conversations, all of those could be actually delivered in the local language. So we thought it's actually huge and I still think it's huge. And then if you shift this to the conversation we are having now, could this be in the future? This version where I speak Polish and you understand me in English, or I speak English and you understand me in any language that you want? In Hitchhiker's Guide of Galaxy, there's this idea of a Babelfish that you put next to the ear and you can understand everything around you regardless of the language they speak. So we knew that we will get there. But initially it was like dubbing. So I'll give you a full way of how it progressed. Initially it was dubbing and then as we started diving into what we need to do to solve dubbing, we realized there are three steps in dubbing process. There is transcription step, then it's translation step to another language and then you need to regenerate that in another language. But the research that existed at the time for each of those steps wasn't very good.

**Speaker A** [0:06:18]: Which companies were doing the research?

**Speaker B** [0:06:20]: There was a good Nvidia models, open source models.

**Speaker A** [0:06:24]: But wait, it's just an independent research or it's not any of the big companies.

**Speaker B** [0:06:26]: No, I mean everything was poor. Everything was robotic, everything was pretty robotic. It was still, you know, it was still like, you could immediately tell it was like a robotic voice and nothing really crossed that uncanny valley yet. There was one good open source paper, an open source repo that I'm trying to recall that was pretty good but very unstable and still took so much time to generate. That was the best. And Nvidia had some good research on some of those components, especially on the speech to text side. Translation was okay. Ish. I mean DeepL at the time was incredibly doing incredibly well. And then you had the kind of Google Translate version of that, but all of the components to do dub were not good enough yet. So that's part one, the research wasn't there. And part two, when we started testing the dubbing idea with a lot of initially creators. The message we are getting back from the creators is like great, I would love to get dubbing one day. But today I have different problems. My problems are I want to post, produce and change the line that was recorded in the wrong way. Or before I record my video, I want to be able to narrate the script and see how it sounds. Or instead of me speaking over a video, could I just have AI speak over that? So before I even think about dubbing, can you give me that? And that was for us, it was like, okay, before we can solve dubbing, let's solve the research component to generate speech and make it sound great. And on the product side, let's actually deliver for people to be able to just narrate content. So let's pun down and ignore for a second the language shift. Let's just help bringing content alive with audio with a high quality.

**Speaker C** [0:08:07]: I want to tell you about the presenting sponsor of this podcast, Ramp. I have been reading a lot about SpaceX lately.

**Speaker A** [0:08:13]: SpaceX is one of the most valuable businesses in the world and one of

**Speaker C** [0:08:15]: the main themes in the history of SpaceX is constantly attacking and questioning your cost. Ramp helps many of the most innovative businesses in the world do exactly that. The median company running on Ramp cuts their expenses by 5% and one thing SpaceX has demonstrated is that a religious dedication to controlling costs and can help actually increase revenue because you can pursue opportunities you couldn't otherwise. And we see that in the Ramp data too. The median company running on Ramp also grows their revenue by 16%. So when you're running your business on Ramp and your competitors are not, you have a massive competitive advantage that compounds over time. Ramp is the only platform designed to make your finance team faster and happier. Many of the top founders and CEOs I know run their business on Ramp. I run my business on Ramp and you should too. Go to ramp.com to learn how they can help your business save time, save money and grow revenue. That is ramp.com deal is how the best founders turn the world into their talent pool. I've been studying how history's greatest founders operate for a decade and one thing they all have in common is they understand that recruiting and hiring the very best talent is your most important priority. A players recognize other A players, which is why top companies like Ramp, Shopify, 11 Labs, Uber and DoorDash all use Deal. Many of the top founders I know have personally invested in Deal after using their product and what they discovered is that DEAL is the best company in the world at building infrastructure for global hiring. Deel will help your business hire, pay and manage any worker anywhere in the world so you can retain the best talent anywhere and spend the rest of your time focusing on what you do best, delivering value to your customers. The founder of eleven Labs has a great description of of the value DEAL can give your company. He said, we built eleven Labs to break down language and communication barriers with DEAL enabling us to hire and support exceptional talent anywhere. We can accelerate our innovation and bring more voices, stories and ideas to every corner of the world. Deal is trusted by over 40,000 businesses. Learn how they can help your business today by going to deal.comsenra that is deal.comforward/senra.

**Speaker A** [0:10:23]: Let me make sure I'm understanding this correctly. You're like, we're going to dub. We're going to reach out to creators first. So I'm, you know, reaching a couple million people in English. Let me see if I can get this guy to say, hey, can I translate it? Can we dub this for Polish and Spanish and all these other things? And then the feedback you're getting is, yeah, that's kind of nice. But I have a lot. I have many more immediate concerns. And can you help me with xyz?

**Speaker B** [0:10:43]: Exactly. And it kind of was. Two things at the same time were great because that was also true on the research side, where you have this, like, three steps you need to solve in dubbing and nothing in the space is good. We need to solve one of those steps ourselves. That's where Piotr comes in and is able to create and assemble the best research team to solve it. And he himself is an incredible researcher to actually bring that to life.

**Speaker A** [0:11:02]: Yeah. Because I'm friends with Mr. Beast and I remember talking to him about this a few years ago where, you know, he was the largest creator in the world and he used to run separate YouTube channels. And he told me, he's just like, yeah, well, for my Japanese, like the Japanese versions of my videos, he doesn't just dub them, he'll hire a voice actor. That's like, the voice is famous in that country.

**Speaker B** [0:11:23]: Yeah. One day you should, whether with us or any other company, think should dub your podcast. It's so much knowledge that could be brought into so many different entrepreneurs worldwide. Like in Japan, if those conversations were.

**Speaker A** [0:11:36]: It's funny you said Japan, because I was thinking, I knew we were going to talk today and I've been thinking about you the last few days and I'm working on this episode for the founder of Honda, for my other podcast founders. And what's surprising about that is, you know, it's not Honda. The cars at this point, when this guy's live, it's the most. He, he created the most successful mass produced motor vehicle in history, which is the Honda Super Cub. And the way they describe their company, he's like, we're just a research lab for engines. Literally, that's what he's like. All I do is think about engines all day. He actually separated out and made the Honda R and D a separate company because he thought it was so important. And then they were just funded by a percentage of sales, but then they turned over all the research to the manufacturing division. And he's just like, if you just have a research division and you only tell them to experiment and you've staffed with engineers and researchers, he's like, they're going to constantly invent new things. And then if you're a manufacturer, you can figure out how to apply those to products. I was like, I would never think. You'd think, oh, they're car manufacturers. No, this is a research team, to be honest.

**Speaker B** [0:12:37]: And you started with this question. This is not too dissimilar from how I think about how we run 11 laps today.

**Speaker A** [0:12:43]: I know, that's why I'm telling you this.

**Speaker B** [0:12:45]: So it's very much like there's a focused research lab, there's research engineering on bringing that to the product work. And then we have a lot of small teams running after specific product problems that we can solve. And then of course, the wider go to market and deployment of how you bring that to the customers worldwide. But the general philosophy is like a lot of small teams, usually less than 10 people having flexibility, autonomy to just run ahead and apply their best judgment in what we can solve for the customer.

**Speaker A** [0:13:14]: Okay, you need to say more about this though, because this is where I still, I'm a little confused by this. Somebody doesn't know who you are. They just met you for the first time. They don't know what 11 labs is like. Describe to that person how you view your own company. It's like a research lab. Is that the word you're going to use? Like, how would you describe this?

**Speaker B** [0:13:31]: I would introduce consistently the company as a combination of research and product deployment. Research is frontier audio models. Text to speech. Speech to text orchestration. Product is one platform that helps companies transform how they communicate with the world around them. And that can be marketing with, helping them tell a story like Ramp creating their super bowl ad it can be support working with Deutsche Telekom on creating voice agents for the call center or it can be sales helping on inbound sales qualification to make sure that that streams through or even wider operations and working with the government of Poland to help create an agent that can take a healthcare appointment, follow up with a patient to remind them about appointment, ask how they're feeling. And that kind of one combination between those is building the research, building the frontier of all voice, of all audio. And on the product, doing the part of applying that audio, combining that with knowledge, combining that with the creative work to then allow companies people to change how they communicate.

**Speaker A** [0:14:34]: And you are solely focused on audio.

**Speaker B** [0:14:37]: On the research side, solely focused on audio product, we combine the best of audio with integrations knowledge, LLMs to help

**Speaker A** [0:14:45]: deliver for explain why you think it's so important to be solely focused on audio. On the research side, we think we

**Speaker B** [0:14:51]: have incredible talent to be able to go after that. The focus is so important and effectively building the best architecture for those audio models. And we think audio is a good combination of not only science but also the arts that you need to solve. It's a little bit subjective. The voices that you produce will be subjective, so you really need to get it right. But ultimately, as you think about AI models, there's data, compute architecture that you need on audio. We think a lot of the problems that still exist are on the architecture side. We want to be solely focused on solving those architecture problems so you can actually get the best quality out there. A lot of the team, a lot of the people that work on our side are the best audio researchers in the world. And they're also excited by the premise of being able to continue deploying the best frontier audio models.

**Speaker A** [0:15:42]: And you feel you have technology on the other side that no one else in the world has.

**Speaker B** [0:15:46]: We think so, yes.

**Speaker A** [0:15:47]: This is a weird analogy. I'm so glad I'm reading this book at the same time we're talking because for Honda, they kept trying to get him to diversify. He's got other products, obviously he builds a bunch of things with engines, but he's like, does that product have an engine? And they're like, no. He's like, then I'm not building that product. He's like, I just do. I focus on engines and sometimes it's on two wheels and four wheels and everything else, but it's like just engines. It's very similar to what you're saying about audio. And he also said that he felt he had the best engine technology in the world and no one else could replicate what they did.

**Speaker B** [0:16:15]: There is a common question as we think internally of it's 100% true of how you described it now too. And like when we think about new product, the big question is do we think we have a unique advantage by applying our audio models in that product experience? If the product experience doesn't have a big bottleneck in that audio in the voice communication side, then it's not our forte.

**Speaker A** [0:16:39]: Explain a situation where you realized that you shouldn't go after that opportunity. Could you give me an example of what you're describing?

**Speaker B** [0:16:45]: The example would dial you to slightly different spaces. One is for a long time and I think it's still true. The ideal version in the audio space is if you've created a marketing campaign is how that combines with a lot of the image and video work to deliver better content. Two years ago we would have first tried to see whether we can help people create effectively lib dubbing or avatars for their content. So let's say you switch from one image to another, you need to move the lips or let's say you want to narrate something, you create an avatar. That was roughly two years ago. A lot of the models that existed on that site just weren't good enough. And deploying a product in the space would be such a defocus and such a shift for the company that it didn't have the audio as a superpower. It still had a bottleneck of the quality of avatars, quality of a lot of.

**Speaker A** [0:17:42]: Because the problem to solve there is video, not audio.

**Speaker B** [0:17:44]: Exactly. So this was still poor. So even if you had the best audio applied into that work, it's still the experience wouldn't be very good. So we decided to not effectively pause any of that effort. Fast forward today is of course shifting now. I think there's a good set of open source models now that exist in that space where the combination of audio, image and video can actually deliver that result. So we are revisiting that today and the recent London ads engine of bringing an ad and bringing that internationally and shifting things in the video. Perfect use case of that. But still a conscious decision we are taking is not creating the model from scratch. So like true text to video or like VO3 type models that exist, we want to be at that intersection where we know the audio can give you the unique advantage which is usually you already have an existing asset, you need to modify that asset, add that audio component and bring it and bring it home.

**Speaker A** [0:18:36]: Do you feel this intense focus or Relentless focus on audio is kind of like defense against the larger labs, for sure. Do you talk about this in the company?

**Speaker B** [0:18:47]: We do. The big part is our focus is audio on the research side and that's where we want to win. I think that we also talk about this in the long, long term. That advantage that we have today will hopefully still be there, but it might not be as big on just the pure research. That's why the other components, that's why the product is so important and that's why the ecosystem is so important that we build around that product. And maybe just to explain what I mean by the ecosystem, of course there's the brand and trust that you built, but there are also other parts that you can build. And in our case this was investing into effectively a marketplace model where people can create an asset re authenticated and then you can share it and earn compensation as a result. So like trying to create a completely different model for how that works.

**Speaker A** [0:19:32]: Give me details about that because I don't know. I don't. Yeah.

**Speaker B** [0:19:35]: An example is voices. So we did it with voices where people can create their voice. We authenticate it, then you can share your voice, your AI voice, and passively as your voice is being used, you earn compensation. We have 20,000 voices today on the marketplace and new people that come in now have a selection of different accents, different styles, different languages, of course, different age, gender that you can pick every time you use it, that other person gets.

**Speaker A** [0:20:04]: Do you as a company make these voices? Any of these voices or is it just third parties?

**Speaker B** [0:20:08]: We of course created a system for people to do that. And some of them, when we see pockets that are missing, we'll ourselves try to go after and find people to fill those pockets that are missing and create those voices for the wider ecosystem to benefit.

**Speaker A** [0:20:22]: No one knows about 11 reader. You have to do a better job. I was listening to your episode with Jon Kallson, who I love, and I don't think he even knew. He kept saying, he's like, why doesn't this exist? And you're like, there's an app. And then the follow up to talk to him. I was like, no, dude, I use that app. What you're asking for, John, is he already has it. You need to show it to them on your phone while you're recording the podcast with them. So I use George. That's the voice I. In fact, we do all these like research reports for the people that come on.

**Speaker B** [0:20:48]: Thanks for being a user. That's amazing.

**Speaker A** [0:20:49]: No, of course it's A fantastic product, and it turns every document into essentially a podcast that I can listen to when my eyes are busy. But the funny thing is we do these research, like dossiers about everybody comes on. And so I put the one about you into 11 reader. So I'm listening about you win your own product. But like in George's case, is that coming from you guys?

**Speaker C** [0:21:12]: Did somebody.

**Speaker A** [0:21:13]: Is somebody else getting paid?

**Speaker B** [0:21:14]: When I'm listening to George, somebody else is getting paid. It's a great voice actor that worked with us now for a long time. And every time you listen, he gets paid.

**Speaker A** [0:21:23]: Do you understand? When you sat down, I was like, one. I keep running into you everywhere. And so that's what I was like, dude, we gotta just do a podcast together. But you're so confusing to me. And in a great way. This is not like a negative thing, because I was like, I don't even know how to describe your company. You're doing all this research, but then you have all these other different products. This is very unusual, especially for somebody that's so super focused.

**Speaker B** [0:21:44]: But, you know, it is very fair. And I think we are seeing that everywhere across AI companies of like, you know, the model becomes the platform becomes application. But for us, the unifying theme across all of them is that angle of communication. Like, we think how you communicate as a company as you think about content, communicate, all of that is changing. And we want to be at the intersection of that. We build the best models to help you do that, and then build a platform that effectively delivers that content, delivers the knowledge, delivers the conversation a completely new way. And that's, of course, there's just so many different applications. There's 11 reader that lets you enjoy content in a completely new way.

**Speaker A** [0:22:19]: So research platform applications on that platform.

**Speaker B** [0:22:22]: Exactly. Okay. And you know, like, we explicitly are not planning to touch any of the intelligence or knowledge work or coding. Not our strength, not our domain, but we are.

**Speaker A** [0:22:35]: That's a vicious battle, too.

**Speaker B** [0:22:36]: Very vicious battle. Lots of. Lots of great companies in there. But what we would love to be is if you think about the next three years or however many years, there will be probably three platforms that you set all the interactions on those platforms. We want to be the leading platform for those interactions for that communication. Wait, explain that the whole way. And that kind of builds on that theme. How you engage with content, how you engage with the company will change. We want to help people. Companies have one place, one platform where you can set it up, you can set up your integrations, you can bring your knowledge, you can bring your brand, you can bring your assets from the company and then deploy that for entirety of customer journey. Whether that's in the marketing example where you tell that story through content, capture that knowledge back about the user, whether that's in sales, when you're trying to engage and bring your product to the customers, whether you are supporting that across the customer journey or maybe in a simpler way as you are trying to understand the customer journey. Every on brand interaction that that journey has, we would love to be able to capture and help you make that better for.

**Speaker A** [0:23:44]: Okay, so let's make this concrete because I still like I want to be able to wrap my head around this. Let's take your like most deeply integrated customer.

**Speaker B** [0:23:53]: Yes, right.

**Speaker A** [0:23:54]: And say, you know it's Goldman Sachs, I'm making this up. And this is how they, they use this product. All the different products they use like who is the company or one of the companies that is most deeply integrated with your company and explain how all the different suite of products that they're using that are powered by your technology.

**Speaker B** [0:24:09]: Deutsche Telekom is a great example. They will use a lot of the audio work to create a podcast and their app and the magenta, they will do that for the ads. So they can create ads and distribute that to their audience. They use a lot of our 11 creative work to be able to do that. Then they will use our 11 agents work for in call center where you call in you want to help you get that help through the voice agent integrated with the knowledge from Deutsche Telecom. So you can make sure that if somebody is calling in to learn about the product, they get information very quickly. If they are calling to get support on how to get a refund or the recent billing request, they can get that help. And then more recently they even deployed an agent inside of the network. So if you are a T Mobile subscriber, if you call, you can ask agent to join the call and help you out, schedule a booking or real time translate your conversation to the other person. And they'll use our effectively combination of agents work and bringing that real time dubbing to be able to communicate in our language. And that across all of that, all of that information is captured back so you understand how customers engage with in this case with the full spectrum of the journey, marketing, the support and then the wider operations, even sales and we help them do all that.

**Speaker A** [0:25:32]: Okay, so in a situation like that, because I think you mentioned obviously a huge increase in your revenue, it's growing really fast. It's like you're Targeting bigger companies. Right. What was the first product Deutsche bank used from you?

**Speaker B** [0:25:46]: Deutsche.com. sorry. Yeah, the first was marketing. So it was two years ago. Two years ago. Still, most of the agents were really very good. They weren't very reliable, they weren't very quick. So marketing was the most obvious one. So they started with that, they deployed that the quality of the content was, was great. So people could engage with the podcast effectively. The use case that you mentioned of bringing your notes and then being able to read them out loud, they were just creating that daily for all the customers so they could read about what's happening in the world through the podcast with ElevenLabs voices. So that was the first use case. Then of course, support is a combination of voice, but also the integrations.

**Speaker A** [0:26:34]: Well, talk about how you expanded them from one product to the next. Like how do you actually do that

**Speaker B** [0:26:39]: in that case, the main and I guess mostly like, how do we partner with them to help them bring that product alive?

**Speaker A** [0:26:46]: Yeah, they start with one, but you have 10 different products, you could sell them. So how do you go from 1 to 2 and then 2 to 5 and so on and so forth?

**Speaker B** [0:26:54]: Yeah, I think the main thing is one, you of course deploy the first one. You make sure that there is value behind that. So across any customer engagement, we try to make sure that we don't only prove concepts, we prove the impact, prove the value. And only after that, we try to get the companies working with us at the broader scale so we prove the impact on the marketing side to get the support going. What you actually need to do is not only the audio, you need to build the integrations. So you need to connect it with all the CRM systems that Deutsche Telekom works with. You need to work on integrations with the output. So how do you connect it to the phone system, whether it's SIP trunking or Twilio, how you make sure that that connection exists. So you would spend a lot of time on integrations, making sure that their logic is respected on how when you do pick up the phone call, the agent behaves the way you want it to behave. So here for deployed engineers would partner with the team, spend the time and Bonn in this case in Germany, working through side by side together on the integration on just being able, making sure that the agent follows the flow that you want, has the knowledge that it should have. And then in that step, the hardest thing in any voice agent work is actual deployment of how you actually test that it works. So then you need to trial that we've initially simulated that you verify the calls, then you do it at smaller scale.

**Speaker A** [0:28:18]: And you're doing this with FTEs?

**Speaker B** [0:28:19]: Yes, we do all that with FDEs, then we deploy and then of course we scale over time.

**Speaker A** [0:28:24]: When did you realize that a huge path to greatly increasing your revenue was doing FTEs?

**Speaker B** [0:28:29]: And before I answer this, and of course the last part is, as you deploy, the job isn't done. You still want to continue evaluate, monitor and refine that behavior over time. And that applies across all of the use cases. NFDs for that are great too. So I used to be at Palantir, so it always felt like a big thing of how we want to work with customers. It's like almost. I don't like the word customers because in many ways I feel like all of them are partners where you are working together on the same problem and try to solve that. So those. A lot of the philosophy of the FDEs was there from the start to make it specific, working with the partners side by side on their problem.

**Speaker A** [0:29:09]: Hold on, this is actually really interesting. So tell me what you observed that was working at Palantir, you were like, ooh, if I start my company, I want to do that too. And why?

**Speaker B** [0:29:19]: I think the most incredible thing was that you were meant to be on the same side of customer obsessed of their problem and try to understand them deeply from the beginning. So I used to work at blackrock before Palantir blackrock when I joined, given the compliance security, the first month or two, when you send an email, it gets verified by your team, it gets trained before you send it externally. So it's like a pretty detailed flow of making sure that it's good. In Palantir, when I joined after the onboarding in the first month, I'm like, okay, you now need to work and understand a customer. You're flying to Aberdeen to North Sea to work side by side with them, understand what's happening and then bring it back. And that was complete shock for me and kind of the approach and culture of I have never almost interacted with a customer on the blackrock side and now here I am in the first weeks I meant to go there and be next to them, which was crazy. I thought it was great. I thought it was that mentality and every time you are going to be there on the, I'll call it frontline, loosely on the frontline to work with them and bring that knowledge back, understand what is actually the problem, what's fixable problem and then actually fix it. And that mentality Is so true now at elevenlabs too, where all of our fdes, our go to market team too is going to obsess of like how can I actually be there with the customer, understand the problem and work with that. There was other components that I think were great. The small teams, they had usually small deployment teams that worked on a lot of that. The best idea wins concept was very true where in that small team you very quickly assembled the best knowledge of what you think should be done for that customer and you had power to then actually enact on it.

**Speaker A** [0:31:09]: Define small.

**Speaker B** [0:31:10]: About five people considered in pound tier big. And in elevenlapse is going to be also relatively big. I'll tell you something more though on the FDE side because of course now you probably see every company doing fdes and in our case fdes are part of the product team. They are not part of the go to market team, they are part of the product team. They are deeply embedded on understanding what's the roadmap of the product. But there's a second reason which is one, you want all the FDEs to actually solve the customer problem and stretch your product in that direction. But second thing you want to them to do is bring any of that knowledge back to the product so the product becomes better for the next generation of companies building on top of it. And I feel like the second part is always frequently missed where it's like first, okay, if these are doing effectively a lot of the hard integration work to solve the problem. But if you don't do the second step of how you actually learn the the expertise and bring it back to the product, then it's effectively just services or just wait, same way with that second part.

**Speaker A** [0:32:17]: So you're gleaning information through trial and error, working closely with them. Then you can take that back and spread that knowledge across the other tens of thousands of customers that you have.

**Speaker B** [0:32:26]: Is that what you're talking about? Exactly. Okay. Exactly. And it's a product knowledge of like how you operate with. You know, there are simple things. Let's say you build an integration. How do I now have that integration available to everyone? That's a simpler version of that. But let's say you are working in healthcare space. In healthcare space. If you deploy the work, then you want to optimize the product experience for the right. If you are not starting as a second customer, you want to make sure that you have.

**Speaker A** [0:32:57]: So wait a minute, you're using your customer base as almost like R and D, another form of R and D.

**Speaker B** [0:33:03]: You are definitely Accelerating your R and D through understanding the domain that you're working with. And it's, you know, it's because their problems are not.

**Speaker A** [0:33:10]: Very rarely, a company's problems is unique to that company.

**Speaker B** [0:33:13]: That's right. And the beauty of that is like kind of everybody benefits because you work with one customer, you learn, you bring that into the product experience, you learn with another one, you learn, you bring it back to the product experience. Both of those customers benefited from having the product optimized for the better work. The domain expertise they have is still there. They can win based on the domain expertise, but the product experience of how you build based on that domain expertise can be abstracted, can be reusable.

**Speaker A** [0:33:39]: What else did you learn working at Palantir?

**Speaker B** [0:33:41]: They also were very much of no title organization, which we carry over at ElevenLabs, which does help in that best idea wins approach where people do feel. I feel like I'm mimicking you on that, Church.

**Speaker A** [0:33:56]: I thought the same thing. I was like, you don't have to

**Speaker B** [0:33:58]: if you don't want to. I know it's a complete coincidence. We're leaving that part in no titles, relatively flat organization, very few layers. So it's like between me and the C suite, I worked there before the dpo, it was four, five steps or less. So you always felt like a proximity between. I think it was like four or three, actually. So it was a good proximity of being able to work together. At 11 labs, we have a couple, five today. Like maximum depth of how many layers there should be. And hopefully over time, actually there will be fewer more layers. If AI helps you run the organization the way we would like to run.

**Speaker A** [0:34:42]: Well, say more about that. What can you not do today in the way you run your organization that you hope AI can change in the future?

**Speaker B** [0:34:50]: I think there's always. You want the information from the person working as closely to the problem. So let's say you're developing a product, you want to speak with the engineer that actually develops that product rather than their manager. If it's a client conversation similar, you want to understand what is that client saying from the person on the ground. Rather, a manager is summarizing that information and giving that to you. And I think that information flow will change with AI where you will have access to everything that's happening in a better granularity than you could ever have before because it summarizes that back and forth. Second, I think that in General, roughly at 11 labs, most people will have close to 10 direct reports. So a pretty wide, wide Set, which helps us build that small team approach that we have. And that too only works if you can amplify a lot of what's happening across all the teams, all the people that you work with, to summarize information of what's happening in their teams, how they're performing, what are some of the gaps. That definitely helps and helps shift it from reactive to proactive. I think too what I mean by this is frequently in the past, I think you would rely on specific individuals surfacing the information to you. Now as we think about 11 labs and how we run, it's like you can summarize all what's happening, all the data of what's working, what's not, and get that signal. I get that signal and I can proactively engage on where I think it's not working, which helps. It helps, of course, everybody across the company because you have that same ability wherever you are. I think that maybe last part, which is very related to those two, why it's even possible today we took a choice to be extremely transparent with a lot of the data that we have, a lot of the docs that we write. So everybody has almost access to all the docs that are there in the company, which ultimately helps you create that system where you can actually tap into that knowledge.

**Speaker A** [0:36:50]: Okay, so I want you to say more about this because I think this is one of the things I want to talk to you about. Because you're relatively young, this is your first company, your first company you built, you got into AI right away and then you were perfectly positioned for this huge explosion. Obviously people have been talking about AI for 80 years or whatever, but you're at the right place, right time with I think the right set of skills based on what the company built so far. So how different do you think in the future the way you run your organization can be than what it is today?

**Speaker B** [0:37:19]: I think the small teams approach will definitely be there across many of the companies that I believe will be created in the future. It also helps with a very different piece, which is if you just think about adopting AI technology in our case, it doesn't have to be a top down mandate of you need to use this technology to get better and then the teams enable others. Given it's relatively small and independent people, bottoms up, adopt what they think is best and are unable to run with it straight away. So that helped a lot in that sense. I'll give it two others which we believe strongly on. One in a lot of the small teams that we have, and a Lot of teams that we have, we bring even non technical teams, we bring engineering talent in those teams. So our talent team, our ops team, our legal team, all of that will have engineers that help both automate some of the work, but also elevate everybody else in how they are using AI. I think that will be a bigger pattern in the future across the companies too, where I think increasingly some of the biggest and smallest companies will try to infuse all teams with engineering resources so they can get smarter.

**Speaker A** [0:38:27]: Is there any function that is centralized at elevenlabs that then all these small individual teams can then access? I spent some time with Luca Ferrari of bending spoons and he had this wild idea, wild idea to me where he's just like, well HR is actually really important. He thinks like the fact that tech people are like dismiss of it is like ridiculous. And he's like, but my HR is like 50 people and they're all engineers. And then it's like one centralized HR that every single other because he owns, I don't know how many companies they all utilize it, but it's just like 50, I think 50 engineers in HR and then all the different structures, teams and companies he has tap into that for that resource.

**Speaker B** [0:39:08]: Of course there are centralized functions. Legal is a good example of course of how we are running. That needs to be very central enablement of how we help people across go to market and other teams, how they are learning the craft of how to sell 11 labs. And as you said, there's so many different products. You need to be very particular about how you deliver that to the specific customer. So it's not confusing the customer and what we are offering or what we do. So yes, so there's a good amount of those functions, but they all too similar to luca's approach. All of them will have a good amount of engineering in them and figuring out how you scale that operation so it's not becoming hundreds of people in all locations, but how you can use the few people that you have and really bring that knowledge everywhere. One of the biggest ones for us is probably around revops of how you or the revenue engineering effectively function. We have so many tools that help you get the knowledge, whether it's code, during the conversations, transcribe, bring it back, make it easier for you to fill on a field so you capture that knowledge and then don't have to spend manual time. And then of course increasingly we dogfood a lot of our own work. So trying to figure out how we can create AI agents to help replace part of that work but still operate within the team. So a good example is AISDR people going on the website today on 11Apps. You can fill in the dropdown form and leave information about your company, but you can also speak with a voice agent and leave that in a quicker and different way. You've seen a lot of people go for that flow. And then interestingly two things happen. One, people are both making the experience easier, they enjoy it more. But two, they leave a lot more information than they ever would for the dropdown form. They tell us so many about the problems about the wider set of use cases so we can connect them better.

**Speaker A** [0:41:00]: That's really interesting. So because they're speaking and not typing, you get more information 100%.

**Speaker B** [0:41:06]: I mean it's of course a quicker way of doing it, but also people just feel more at ease instead of going through this manual dropdown form. It's just I feel like a better way on leaving the information. But now because we think it's going to be such a big part where every company will have their revenue engineering function. But in our case we want that kind of AISDR function to be part of the company. We want it to help everybody across wherever you are. We are a global company so it's central and then deployed to each local team so each local team can refine it for the local new ones. But developed of course centrally.

**Speaker C** [0:41:48]: I found one of my all time favorite quotes when I was reading the

**Speaker A** [0:41:51]: book 0 to 1.

**Speaker C** [0:41:51]: The quote says the single most powerful pattern I have noticed is that successful people find value in unexpected places. And they do this by thinking about business from first principles instead of formulas. That is exactly what Applovin has done with their advertising platform. Applovin connects you with over a billion potential new customers inside mobile games. Applovin allows you to capture undivided attention. Applovin ads are full screen video ads that are watched for an average of 35 seconds. That is retention that blows other ad platforms out of the water. And you can launch on Applovin in minutes. You set the goal and Applovin achieves it. There's no complex setup, no expertise needed and Applovin scales quickly. They can put your ads in front of over a billion potential customers. Other businesses have seen immediate results, have scaled to hundreds of thousands of dollars of spend per day and increased their revenue by millions.

**Speaker A** [0:42:49]: So you want to get started quickly

**Speaker C** [0:42:50]: before all of your competitors are on Applovin. And you can do that by going to applovin.com that's applovin.com you still think

**Speaker A** [0:43:00]: of 11 labs as a single company. Just with how many different products do you guys have?

**Speaker B** [0:43:04]: Right now we have three kind of core product lines and then we have additional three that are developing. Developing.

**Speaker A** [0:43:14]: But how many different applications?

**Speaker B** [0:43:17]: Well, within each of those we'll have. No, but let's say six are kind of the core. And then within that you can do, of course, maybe like 20, 30 different things.

**Speaker A** [0:43:26]: Yeah, it seems like you have a ton.

**Speaker B** [0:43:27]: Yes.

**Speaker A** [0:43:28]: Like 11 reader, for example.

**Speaker B** [0:43:30]: Yes, but it's, you know, it's like Elearn Reader or Elearn Productions, which help you with the human loop aspect to correct the content and localize that to another level.

**Speaker A** [0:43:38]: Where's all the revenue coming from?

**Speaker B** [0:43:39]: The biggest nights are on the agent side and the creative side. So the number of use cases that deploy conversational agents is just skyrocketing today for us.

**Speaker A** [0:43:50]: And are you seeing a specific industry that's adopting them faster or No?

**Speaker B** [0:43:55]: I think the quickest today for us is fintech. Super quick.

**Speaker A** [0:43:59]: Like Revolut.

**Speaker B** [0:44:00]: Revolut, exactly. Klarna Pug Bank. Like all of those companies are just moving at another speed or customers bank in the US here. Then the healthcare, retail, e commerce and telcos are the four of the biggest ones. Fintech is moving the quickest. Of course, it's slightly different regulatory aspects, but then I think the healthcare telcos is kind of a second and retail e commerce is. Just this year I started going through the wave.

**Speaker A** [0:44:30]: I want to ask you one more time. I just want to go back to this in case we missed anything. Is there anything else that you learned working at Palantir that we didn't talk about that you think is valuable?

**Speaker B** [0:44:38]: Well, this is a stretch and I'm biased, but in Palantir frequently there was this concept of how you need a little bit of the understanding of the art to do your job well, or people need to need to effectively try to be artists, even if we aren't. One of the phrases that was used was artist colony. And if that was ever publicly said, I never fully appreciated the strength of that. But I do feel a lot more about this now as we kind of intersect that AI and creative space in many ways, whether it's building the audio, research models, there's a lot of nuance in how that's delivered. Every voice that is delivered. Do you like George and Levenrider? Everybody will have their own preference. And how you make sure you capture those voices, how you deliver those preferences is a tricky challenge. And then two, as you Work with some of the brands that are trying to define how they communicate with the world. That too requires some of the art in that. And we are trying to bring, of course, a lot of the people to combine that. But blending that art and science, Panther definitely tried to do. I think I'll let others judge to do it successfully. But we also will try to do and hopefully are doing good steps in that direction. Whether it's the Voice marketplace that we spoke about, whether it's having a lot of creatives in the company building projects with us or around us, or the for deployed engineers or for deployed creatives almost to work with the customers, I think that blend will be increasingly important. And everybody talks about taste now, how taste will be the finding front of AI and behind a buzzword. I think there is a lot of truth to that where, yes, increasingly everybody will be able to create everything and what defines above. Good product experience, good deployment experience will depend on how the design language sounds, how tasteful it is, how you bring that across. So I think Palantir tried to do it. We are trying to do it too.

**Speaker A** [0:46:41]: Yeah. I think what you're getting at is there's this guy named Edwin Land. He's the founder of Polaroid. I discovered him because he was Steve Jobs hero. And Steve Jobs was talking about, I remember it, I talked to him about on founders episodes over and over again. I should get a framed picture of Edwin Land and put him in the studio or something. But he was the one that invented the idea that Steve Jobs used where he's like, I want to build a company at the intersection of technology and liberal arts. And the reason he just came to mind is when you brought up taste, he has this great quote where he says, taste is as rare as a unicorn. And so it's like people talk about all the time, but it is definitely like a limiting factor. And it will all, I think, will always be like a limiting factor. But I love this idea. I think this is my issue with a lot of why I don't live in San Francisco. Like, I drop in there, we do a bunch of recordings, obviously have a bunch of friends that are tech founders. But it's just like I feel this. Like the new crop of tech founders is like they. They lack the humanity. Where, like, one thing I liked about Steve Jobs or Edwin Land or the founder of Honda, they would say over and over again, it's like, I'm just inventing technology to enhance humanity. Yeah. Where I think a lot some of these people are like, I'm inventing technology to replace it. So this leads me to another thing that I wanted to ask you about. Since you worked at Palantir, you've seen Alex Karp be one of the only people and he's done it for a year and a half and now it's like, really, really. I think his perspective has caught on where he's just like, if you're running these labs and you keep going on TV or giving interviews talking about, I'm building nuclear weapons grade technology and it's going to take everybody's job. I see too many conferences, which I want to ask you about.

**Speaker B** [0:48:09]: No, I haven't been there.

**Speaker A** [0:48:10]: Okay, so I was just there. I was only there for a few hours and Karp was the one that spoke first. And he's just like, what do you think's going to happen? He's like, your technology is going to get nationalized. Do you have any opinion on his perspective on this?

**Speaker B** [0:48:23]: Not directly. So of course we've seen what happened at Anthropic Case recently given and most of our team is in Europe, spend a lot of time with the European teams and governments of how we think about building sovereignty and how important this will be. So no direct answer to your question. I do agree. So much of the other part of what you said, which is AI really needs to work for the people. It needs to amplify human potential rather than replace it. I hope we will do a lot of the work and are doing a lot of work in that space. But I hope in some of the interviews that you mentioned and some of the conversations from other companies that this will be an increasing theme of how they can bring that to reality too.

**Speaker A** [0:49:09]: The reason I ask you that question is because I think me and you were at a dinner with Scott Wu, founder of Cognition. I just recorded an episode with them. I've spent a bunch of time with Scott over the last few years, even before they launched Devin. I met him and what I think he does well and what you do well is you guys are always talking about the positive benefits that your products are creating for people. Like, I think you told the story of a woman had lost her voice before she got married and then she worked with you guys to recreate. And so therefore she could essentially redo her vows in her own voice. It's like a perfect example of that

**Speaker B** [0:49:46]: voice is such an incredible identity that probably the case that you mentioned is some of our proudest work where we can work with people that lost their voices to ALS due to fraud, cancer, and work with them on bringing it back. That is one example. Recently we worked with a musician that lost his voice and he wanted to still perform. So he worked on recreating that voice. We set out a concert and he did a concert with his old band together with an AI voice. And now he's touring and in the uk he's going across places and touring across. Or a congresswoman last year lost her voice and still wanted to inspire others to do the work and was in the congress with for the first time with AI voice, trying to bring that to life. And the common theme is the voice carries such an additional element of emotional impact, of recognition. The moment you hear someone's voice, you recognize it. If you know someone, of course that has a second part, which is how we safeguard and how you think about safety across that future where voice can be created. But yeah, that's the. The work across there Today it's over 10,000 people where we worked on bringing their voices back and hope to continue that. And outside of the accessibility space, of course, what happens in education, wider culture here we partner today with 800 organizations to help bring the technology to the people out there. Another crazy one, actually. That's a crazy story recently. Sorry to interrupt you. There's like first of all a legend, a guy called Tim Green. He used to be a best selling author, one of the top NFL players. And then unfortunately he got ALS and couldn't do all of that work. And from all the things you could imagine him doing, he decided to go the complete extreme and he did a podcast. So he started a podcast.

**Speaker A** [0:51:50]: I'm gonna have to find this guy and chase him down.

**Speaker B** [0:51:51]: No, well, you should have an interview with him and he.

**Speaker A** [0:51:55]: That's not what I meant. That's not what I meant, Matty.

**Speaker B** [0:51:57]: Okay, okay, fair, fair meant.

**Speaker A** [0:51:59]: I will destroy him. No, o but

**Speaker B** [0:52:04]: he does extremely well. He has great guests at Hari Blutnik recently on his podcast, some of the NFL players. And this year he won an Emmy for his work. So it's like, wow. So he's incredible.

**Speaker A** [0:52:18]: Wait, so you made that voice though?

**Speaker B** [0:52:20]: Yes, we do. His AI voice.

**Speaker A** [0:52:22]: That's incredible.

**Speaker B** [0:52:23]: So that was one of our proud small brick contribution to, to his work, but it's just so crazy. It's the most extreme thing you can do. And he does it. He inspires. I don't know how many people got inspired, but we had from hundreds to thousands of people reach out thanks to him on how can we get our voice back too, in the same way.

**Speaker A** [0:52:46]: Well, I think you hit on something which Is one of the reasons, and I discovered this accidentally is what makes podcasting so powerful is the voice where it's like, you know, obviously I like, love to read. I mean, there's books all around, like scattered around the house, everywhere. Obviously. I have like, I don't know, I have like a thousand books in my other library, like price 600 unread. And there's some authors where I literally just fall in love with what they do and read every single thing they've ever written. But if you would ask, like my emotional attachment to my favorite authors or my favorite writers, like Cormac McCarthy for example, in fiction, compared to like my favorite podcast, which is like, not at all comparable. It's like I feel like I know because of the voice and like the, the human, like, element of that. I just feel like I know them in a way that I could never know, like my favorite, you know, writer for sure.

**Speaker B** [0:53:31]: I mean, you also, it's. You're in the conversation now and it's like the voice carries so many other dimensions than text. Like, text, of course, you imagine you interpret. But it doesn't have the emotion, it doesn't have the intonation, doesn't have the imperfections. It doesn't have the pauses.

**Speaker A** [0:53:45]: The imperfection is really important because, you know, some. We have some guests that come on here and they're like, okay, I said like, too much. It's like, that's how you speak. It's like we, yeah, we can edit it out if you want. But like, I slur my words, I say, oh, I make all these kinds of weird things. It's like, but that is just how I am. I don't ever want to be appear on a, like a podcast and you meet me in person. It's like, this guy doesn't even sound the same. Like, the imperfections. People admire imperfection, or, excuse me, authenticity way more than they do perfection.

**Speaker B** [0:54:12]: That's true. You know, it's actually funnily, it even applies in a non human way, in a voice agents way too. Initially, we are trying to create a perfect voice agent that doesn't do anything.

**Speaker A** [0:54:24]: It didn't sound human.

**Speaker B** [0:54:25]: It didn't sound human. And then of course, the obvious thing that was the clearest is like the ums, the ums, the pauses. And suddenly the performance of working with that voice agent skyrocketed. Everybody was like, oh, this is so human. This is good. I'm happy to speak with that. So, yeah, it's making it imperfect. It's almost now the element of that but voice does carry that information. It kind of connects you in a completely different way. And why, I think also it's such a hard research challenge because here in text, you don't have that many of those dimensions. You need a lot of data, of course, to create a good language model, but you don't have the dimensions of every voice being different, every voice sounding different to every person. So even doing benchmarks for text to speech is extremely hard because usually different models will have different voices. That already makes them uncomparable.

**Speaker A** [0:55:19]: Did you know when you were younger that you wanted to be an entrepreneur?

**Speaker B** [0:55:23]: I would say I didn't know this was a path for a while.

**Speaker A** [0:55:25]: You did or did not?

**Speaker B** [0:55:26]: Didn't. I was, you know, I.

**Speaker A** [0:55:28]: Because you're European.

**Speaker B** [0:55:30]: In Poland, it was. Yeah, for sure. A little bit of that though, you know. You're joking, but I think it's true.

**Speaker A** [0:55:34]: No, I'm being serious.

**Speaker B** [0:55:36]: Taking like the risk of like not starting something. It wasn't like a common conversation ever happening. I mean, I had a lack of having incredible family. That kind of gave me opportunity to study abroad. And then that kind of opened your eyes of like, okay, now you can work with some of the great companies and then when you work with those great companies, then you realize you can actually do things. Palantir was great for that for sure, where it's like, you can actually go and work with the customer, try to figure out the problem you can take. That seemed very risky to me, but you can do that. So kind of step by step, that opened the eyes of like, okay, maybe this is a path, maybe it is possible to start your own thing.

**Speaker A** [0:56:14]: And from the time you had that realization to the time you started 11 labs, what was the.

**Speaker B** [0:56:18]: So then, as you kind of decided,

**Speaker A** [0:56:20]: was it a year, two years, like, what was it?

**Speaker B** [0:56:22]: So over my time at Palantir, my co founder is Piotr Time at Google, we would start doing hack weekend projects together. So through the years we tried to explore new technology and build together. I think a few years prior we knew that we would love to work on something together. But you want to work something that you think is a true problem and you are obsessed about. And that came to us in 2021. So a few years? Two years? Two, three years.

**Speaker A** [0:56:48]: How many acquisition offers have you had?

**Speaker B** [0:56:51]: Concrete ones? Three or four.

**Speaker A** [0:56:53]: When's the last one?

**Speaker B** [0:56:55]: Last one was last year. Like June last year.

**Speaker A** [0:56:58]: You're going to sell?

**Speaker B** [0:56:59]: No. The reason I ask you, AI is changing the world. We can build the frontier of that change. We are going all in.

**Speaker A** [0:57:09]: Don't pay attention to your VCs, dude. Their incentives are different than yours. The reason I ask you is there's two reasons this came to mind, and some of this is all intuition. You can't even describe this, but Evan Spiegel sat in that exact same chair that you're in. People gave me shit. They're like, why you want to interview Evan? Look at his market cap. I was like, I don't give a shit about his market cap. Like, I don't look at companies that way. I'm obsessed with products. And, like, that dude has soul in the game. Like, and I hope he wins. I have no idea. Like, I don't know anything about, you know, I don't use, like, Snapchat, specs, anything. Whatever it is just, like, he is differentiated. I did. There's just something about him that I like, that I, like, just want him to work out well. Right? And so that. And I'm getting the same exact vibe. I was like, man, I want Matty to, like, win. I want him to succeed. There's just something very likable about you. And then the second reason is because obviously Scott Wu, he's coming on the show, like, every few months. Because I really like Scott a lot.

**Speaker B** [0:58:02]: I mean, it's because he's a genius. He's so good as well.

**Speaker A** [0:58:04]: Not only that, but he's articulate and brilliant and optimistic. But everybody is running at that dude right now. Everybody. Like, the amount of people that want to buy his company. And just something we talked about. And I hope he holds out, because I would like to see a lot more people just be like, no, I'm like, in this forever. It's not just to get a big bag of money, you know, like, go listen to. To. To Travis from Uber. You know, he made billions and billions of dollars from Uber, and he's just like, that did not make me happy. I need something to work on. And see, that's why. That's your question. Because I asked Scott that too. And he's just like, well, there are obviously a ton of people trying to. To either get him or his entire company and all his talent. And he just so far said, no,

**Speaker B** [0:58:48]: I'm not selling love, Scott. I think they should build independent company, too. I think they have an opportunity to be one of the hyper AIs of the future, or however you call the hyperclouds of the future. So I think he can do it. They have an incredible team, and I think we can do it, too. I think it's I really mean it. I think the opportunity that currently exists for entrepreneurs of, with the wider shift, the things haven't been written and it's like it's such a, such a good time to build something special. And I think shows like this are

**Speaker A** [0:59:24]: really important because most of the podcasts are made by VCs, right? It's just like the content that entrepreneurs.

**Speaker B** [0:59:30]: The content that entrepreneurs are so self serving in many ways, I feel the

**Speaker A** [0:59:32]: content entrepreneurs are consuming are created by VCs. It's a weird thing to me and what I would say is it's like the amount of fucking founders that I've talked to that have sold their company or like, like, like I had something, it was going really well, they gave me a bunch of money. Now they tell me what to do. I was like, what did you think the money was for? Like, no one's just going to give you a bunch of money and then you still retain the independence to do whatever you want. And then it's in all these freaking biographies. From Ted Turner to like, there's just a million people that talk about it after the fact. And they got huge bags, billions and billions of bags. Like, I'd give the billions back if I could just have my company back. And listen, man, I think you're smart and driven, but highly likely, like 11 lives is probably the best idea you will ever have in your life. And you're how old?

**Speaker B** [1:00:13]: 31.

**Speaker A** [1:00:14]: Okay, so you're gonna sell your best idea at 31. You got four decades ahead of you, maybe five.

**Speaker C** [1:00:20]: Hold on.

**Speaker A** [1:00:20]: And you're gonna work on your second, third, fourth, fifth best idea. Dude, the money's not worth it. It's not worth. You're gonna get the money anyways.

**Speaker B** [1:00:27]: Well, you're convincing me something. I'm already convinced.

**Speaker C** [1:00:29]: I know, but they all say this shit.

**Speaker A** [1:00:31]: The founders all say this. And it's like really hard when there's like, dude, I'm dropped 50 billion on you. Like, it just, the numbers are getting crazy. So I understand why people do it. I'm not knocking them, I'm just saying I would like, I'm very interested in entrepreneurs that there's no price. Like again, I've repeated this over and over again. It's super important to understand. It's like everybody's like, oh, if you love what you do, you do it for free. No, there's another level. If you love what you do, they couldn't pay you to stop. How much money would you have to give Steve Jobs and say, I'll give you 2 trillion, Steve. But you can't work on Apple. He'd say, go fuck yourself. There's not a dollar amount in the world that could stop him from doing that. And the world is better because he didn't stop doing it.

**Speaker B** [1:01:07]: I'm with you there. I agree. Many people I think will say it. In our case, we had a lack of having acquisition offers, which we turned down. And that was not an option. And any of those acquisitions would. It's not 2 trillion, but they would have made life easy, of course. But I think that in itself should never be an interesting proposition. And like you said, it's like we do appreciate this is likely the best idea, the best timing to have that kind of lack of when it all happened is such an incredible coincidence. And I don't know how the world will look like in five to 10 years. How will the universal high income piece and conversation come in? How the wider society will adopt the technology? How will you actually provide advantage? All of those questions are out there and I think they will be a big part. So of course the best thing they think we can do for the world and for us is just to continue building.

**Speaker A** [1:02:06]: Did you read Scott wu's piece in Colossus, the Colossus magazine? No, that's done by my friend Patrick. Yes, I'll text it to you right when we're done. You can put in 11.

**Speaker B** [1:02:16]: I'll listen to it on a whip.

**Speaker A** [1:02:18]: Put in an 11 reader and listen to it. But I loved what his perspective was at the end. He's like, listen, you know, he thinks he same thing, right person, right set of skills, right time. Thinks this teaching AI how to code, teaching computers how to code is one of the most interesting problem he could think of. And he's like, listen, I could accept that if I try and fail. But what he felt was intolerable. I forgot the word he used, but it's something like intolerable is like I didn't even try. So I was just like. He's like, I just want to give this one opportunity, the best opportunity in my lifetime. Which he understands. Think he's like around your age too. He's like, I'm just going to give it everything I have and see what happens.

**Speaker B** [1:02:56]: It's like some version of biggest risk is not taking any risks in some version of you should just go after it.

**Speaker A** [1:03:06]: Does your co founder think about this the same way?

**Speaker B** [1:03:08]: Yeah, he's also all in. He doesn't like public presence as in interviews, podcasts, but he truly is a genius. I hope one day he comes on the podcast too, anytime he wants. He is of course a great researcher, but beyond the researcher, he also can bring a lot of those ideas in business and other parts of the space and kind of understands what's happening and how it happens. But on the research side, AGI pill and how that world will change is very deeply in his mind and he knows that he can be. And now the wider research team are all part of that change. So it's. It's unique opportunity. I think all of us realize that how unique the timing is and what we can do with that timing and what we can do for the world. I think that's like that we are four and a half years in as a company and at scale.

**Speaker A** [1:04:00]: It's crazy because your opinion is that the next form factor isn't a device. It's actually just the way you're going to interact with AI is just your voice.

**Speaker B** [1:04:08]: 100% will be one of the biggest ways in general, intelligence keeps developing. The next bottleneck of how you actually get access to that intelligence will be how you communicate with that intelligence, how you collaborate with that intelligence. And we can solve that. We can solve that for everyone out

**Speaker A** [1:04:24]: there 12 months from now. How do you think the way you communicate with AI is different than it is today?

**Speaker B** [1:04:29]: Then voice is definitely part of it, but it kind of understands you. It's able to connect the IQ plus the EQ part of it, emotionally understand you, knows how you're feeling, can adjust based on that, can pause, can think, can reinsert itself into the conversation in some crazy way. For the decades, we learned how technology around works and learned the language of that technology. The keyboard, the screen, the coding, languages even, they're kind of, you need to learn how the technology works so you can control it. And now what I think we can solve is flip it back to how we want to communicate, how the most primal way is voice conversation. And you can bring technology on our terms. So I think 12 months from now, what will happen is similar as we are speaking. I think the technology will be able to understand us an incredibly better way. Both our knowledge, both the emotional part of that conversation and delivery deliver similar conversation we are having now.

**Speaker A** [1:05:33]: And if that's the case, then the market for this and even the use case, the amount of people using AI will drastically explode. I think there's actually a historical equivalent that just popped to mind when you were speaking where it's like Alexander Graham Bell was talking about the difference between the telegraph and the telephone. And the telegraph could send messages over long distances, but you had to learn how to program it and use it and you had to learn this language to send it. And he's like the phone, you just pick up and do exactly what you do already.

**Speaker B** [1:06:00]: Yeah, 100% it will. I think you know that even I'm looking at around the room, I feel like there'll be so many devices as well that will just be able to work on your terms. Hopefully the screen, the phone will kind of be able to be back in the back pocket because you won't need it in the same way as you do now.

**Speaker A** [1:06:15]: So when you first started the company, you mentioned this from the Hitchhiker's Guide to Galaxy. So was you and your co founder's ideal version of your product, the Babelfish?

**Speaker B** [1:06:27]: It was on one of the slides that we thought that, yes, Babelfish will exist and will hopefully make it happen, but less so that we will create Babelfish itself, but we will enable everyone out there to have Babelfish in their existing devices, existing presence, existing work. That was definitely one of the north stars that we are thinking about.

**Speaker A** [1:06:49]: Okay, another question I have for you. Why do you always pop up at all these conferences?

**Speaker B** [1:06:55]: I don't do that many.

**Speaker A** [1:06:56]: I think I get these emails. So. So Daniel, obviously a close friend of mine, he hounds me on this and he's right. He's like, dude, you have one of the most elegant businesses in the world. He's like, all you have to do is sit inside a room and make podcasts and every single thing that you want in life will come to you. And he's like, his line for this is like, stay away from the circus.

**Speaker B** [1:07:13]: Yeah.

**Speaker A** [1:07:14]: And so the only ones I do obviously do events for my partners, like Ramp, where I saw you at the Ramp dinner. And I obviously love Michael Dell, so I do his too. And I do nothing else because of Daniel's advice. Just like, stay away from the circus. The people that show up at these things, they aren't doing any work. They're just there to distract. You don't have to do it. And so then I get all these emails and invitations, like, come to this thing and I open it up and I see your face everywhere. What are you doing?

**Speaker B** [1:07:39]: No, I usually try to do two to three per quarter, usually conference events. But in our case it's a little bit different because for a lot of the people that are usually on the conferences, they are our partners or prospecting partners or clients. So it is usually a great way of forcing function of having them in one place and trying to figure out how we build together. That's the benefit of the breadth of the work we do. That a lot of. Especially on the conversational agents work that applies to most of the businesses of how they think about communicating with their customers, how they are thinking about changing customer journey. So. So a lot of the events are a great way for us to catch time with a lot of the people

**Speaker A** [1:08:21]: that we work with and then turn them into customers.

**Speaker B** [1:08:23]: And turn them into customers.

**Speaker A** [1:08:24]: All right, so you are one or

**Speaker B** [1:08:25]: expand the one to two or five, whatever. This is the common trope. And I remember thinking back in the day when we started, I got the first invite for one of those conferences and it's like, oh, this is super cool, super fun. And then you go, I'm European. So I drank alcohol at the time as well. And. And then I felt tired. I didn't think I did anything. And it seemed fun, but it wasn't very productive. And then I had the period. It was not.

**Speaker A** [1:08:55]: Did you have nothing to sell at the time?

**Speaker B** [1:08:56]: At the time I didn't know how to. What's the purpose of the conference? I think it was the lack of preparedness on my side where I was going into the conference and just flowing through it. And I think it was a terrible thing. It's like you. You go there, you have the sessions and some of them are of course good, but most of them are not relevant to you or your business or they are. The circus part that you mentioned that you feel you're doing something important. It's completely unimportant. And that's kind of. Then I didn't do any events and then I realized that it's like actually you can do them. Well, you do need to prepare. You need to pre arrange a lot of the one on ones you want to do during the conference. Everybody is there at the time. You don't want to do too many of them because there's some repeating crowd across those events. So you want to do that once, which is kind of different. And of course you want to be pretty explicit to the other side too, that they know what they are, that you are pitching them and they are relaxing. That's a bad recipe for disaster. But many people want that too. They are there to do exactly the same thing, do business and figure it out. So now it works really well for me. I do good prep. We pre arrange a lot of time. I never go and try to be there for just the sessions or just the content or when of course, I speak frequently on those conferences, but the main thing is trying to grab time with the people that are there. And that has been working really well.

**Speaker A** [1:10:15]: Are you still drinking?

**Speaker B** [1:10:16]: No. On the weddings. But apart from that, every time I

**Speaker A** [1:10:20]: go to Europe, I have the same thought. When I get back, I should drink more.

**Speaker B** [1:10:24]: So much fun.

**Speaker A** [1:10:26]: They just know how to have fun.

**Speaker B** [1:10:29]: There are social circumstances where I would drink. They're just so infrequent now that. That there's that. I wouldn't do it.

**Speaker A** [1:10:35]: Okay. Next time we are at one of these rare conferences together, let's make sure we have a drink. All right.

**Speaker C** [1:10:40]: Deal.

**Speaker B** [1:10:40]: Deal.

**Speaker A** [1:10:41]: All right. Thanks for doing this.

**Speaker C** [1:10:44]: I hope you enjoyed this episode. Please remember to subscribe wherever you're listening and leave a review. And make sure you listen to my other podcast, founders. For almost a decade, I've obsessively read over 400 biographies of history's greatest entrepreneurs, searching for ideas that you can use in your work. Most of the guests you hear on this show first found me through founders.

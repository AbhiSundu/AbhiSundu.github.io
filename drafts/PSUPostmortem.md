---
title: "Results from my first Steam Game: PUTRID SHOT ULTRA Postmortem"
date: 2022-11-19T11:07:54-05:00
draft: false
---
I released my first commercial steam game, [PUTRID SHOT ULTRA](https://store.steampowered.com/app/2053360/PUTRID_SHOT_ULTRA/), on November 7 2022. I spent 6 months working on this game in my free time for a total of about ~200 hours of work. In this post, I'll discuss the results of my game, my process, and some analysis on why my game performed the way it did.

## Summary of Results
My game sold 285 copies in 3 weeks following its release.
![results](https://i.imgur.com/XretR2j.png)

First 3 weeks of sales:

![sales_graph](https://i.imgur.com/KGntyWN.png)

The initial sales spike comes from wishlist conversion. From there, the game hit 10 reviews by day 3 of the release (I had 4 friends write reviews and received 6 "organic" reviews very early on). I saw a massive spike in Discovery Queue traffic after hitting 10 reviews (from ~2000 visits to 15000 visits per day). I did not notice a spike in sales due to the discovery queue traffic.

A handful of large youtubers made videos on the game:

* [Wanderbots](https://www.youtube.com/watch?v=hUwIxWYF3X4)
* [Retromation](https://www.youtube.com/watch?v=64MQ3ALXQio)
* [UltraC](https://www.youtube.com/watch?v=6vu_DlMV3OE)

This caused the second "spike" in sales in the graph above. The larger channels that played it seemed to enjoy the game enough to finish a run, but didn't seem to *love* the game due to some critical balance issues.
A number of smaller youtubers made videos on the game as well, including [RogueAbyss](https://www.youtube.com/@rogueabyss), [ParaDyme](https://www.youtube.com/watch?v=IWHi9VRWr4Q), and [HauntedHusband](https://www.youtube.com/watch?v=eTkhYLoughA).

The game launched with around 620 wishlists (I'll discuss this in the next section). The game currently has 15 positive reviews and a median playtime of around 47 minutes (this time seems to fluctuate, the highest it went was around 55 minutes and it started at around 30 minutes).

## Pre-release marketing
I released my steam page on 06/20/2022, meaning I had around 4-5 months to build wishlists.
Here's my wishlist graph annotated with each of my marketing activities:
![wishlistgraph](https://i.imgur.com/1fZA4GV.png)

The subreddits I posted to were /r/WebGames, /r/IndieGames, /r/games (on indie sunday), /r/love2d, and /r/playmygame.

My main takeaways:

1. Steam next fest had the best "bang for my buck", roughly 300 wishlists, zero effort on my part outside of 'signing' up for the festival.
2. Reddit posts were hit or miss, medium-effort, and usually got me anywhere from 10-30 wishlists
3. Crazygames was easy to submit to and got me ~50 wishlists

My twitter had a very small following before this game's release (~150 followers). I had a couple decent tweets (150-200 likes) but those didn't seem to affect wishlists/sales in any noticeable way. Releasing the game did get me about 100 additional twitter followers, so that was neat.

My steam capsule was done by the amazing [Guilherme Holz](https://www.artstation.com/gholz). He has some good steam capsule experience and was really easy to work with.
## Post-release marketing
I emailed around 20 youtubers with free steam keys to the game. [Here's the email template I used.](https://i.imgur.com/3jgEIhW.png)
I created the list of youtubers to email using the strategies outlined in [this video](https://www.youtube.com/watch?v=ukw_vTFjSDo). As an aside, I highly recommend Aurodev's channel, I followed a lot of his tips for setting up my steam page, creating builds in steamworks, etc.

I didn't have the time nor patience to set up an official presskit, so I just created an ["unofficial" presskit](https://imgur.com/a/prv0qRh) on imgur with relevant artwork. This seemed sufficient for all the influencers that eventually made videos of the game.

As I mentioned earlier, 3 large youtubers and a number of small youtubers made videos on the game.
## Analysis
In this section, I'll outline my thoughts on my results and my process.
## What went poorly
### Game Balance
The game is very easy to "break". There are quite a few spells that sound cool in theory, but utterly steamroll the entire game in practice. Without fail, every influencer that played the game was able to identify these strategies and basically 'autopilot' the entire final 60% of the game. The game is meant to be a challenging dodge-based shoot-em-up, but in many influencer videos, it became an idle game due to these strategies.

In a later patch, I nerfed some of these more egregious strategies, but the damage was "done" so to speak, as many of my initial players had lost interest in the game due to how easy it was.

Some players even called out these broken strategies in demo feedback, but I wrote that off as those players just being particularly skilled, rather than recognizing how easy some of these strategies were to execute. In the future, I think I'll try to get more of my friends to playtest the game, and I'll keep an eye out for this type of feedback

### Lack of replay value
Even for 3 dollars, the game launched with less content than people had probably expected. If the game were properly balanced, I'd expect most people to beat it within 10 runs. Each run ranges from 30 minutes to 1 hour, so this is a solid 5-10 hours of content.

However, due to the aforementioned balance issues, many players beat the game on their first run. The game has quite a few starting loadouts, but this didn't seem like enough of a reason to replay the game for many players. In response to this, I added a number of "challenge modes" (similar to the "Heat" gauge in hades) that drastically increase the challenge of the game. I also added "endless mode". With these updates, I think the game is well-worth the 3 dollar pricetag, but on release I can see how some players would find it light on replay value.

### Shallow progression
I think the game's core mechanic of "Every N shots, do something cool" is great. However, many of the subsequent upgrades / progressions are very boring. Once you pick up your core set of spells, the upgrades are largely just "+2 ice damage", "+5 fire damage", "-15% reload speed" etc. The youtubers that played the game seemed reasonably engaged by the magic spells, but seemed to just gloss over the upgrade system becuase it was so boring.

### No amount of influencer traffic can out-market your game's quality
If you look at my results, you might think "that's not too bad for a game without good marketing!". Then you see that I had multiple youtubers with 100k-500k subscribers cover the game and suddenly you're like: What happened? I think it's clear that my game just doesn't stand out among the crowd. I also think the balance issues mentioned earlier contibuted to youtubers liking the game less.

It does feel humbling to have this much influencer traffic and see such tepid results. I won't vent about this too much more, I just want to say: Imagine if I had made a better game! With the amount of influencer traffic I received, it may have rocketed my game to the moon if my game were better.

### The game's visuals are polarizing
The game's art is very simple, maybe to a fault. I personally like the art style, but I feel that this was one of the reasons my "post-10-review" steam impression boost didn't convert very well into increased sales. I also saw a few comments on youtube videos talking about how ugly the game looked.

## What went well
### Pre-release process
Despite my lackluster sales results, I think my process for pre-release marketing is solid, and I would definitely follow it again. To summarize, my pre-release marketing was:
* Publish steam storepage with demo
* Publish browser-based demo on itch to collect early feedback
* Post to related subreddits
* Participate in festivals (Steam Next fest, Dreamhack beyond)
* Email influencers right before release

This is the same high-value low-effort process that other, more successful solo devs have followed (I believe "20 Minutes till Dawn" and "Pawnbarian" followed very similar pre-release marketing strategies). As I mentioned earlier, I think that a good process only works if your game is also very good.
### I improved my engine a ton
Making a commercial game on steam really forces you to implement all those "must-have" QoL features that players come to expect in a commercial game (remappable controls, rich options menu, save/load, achievements, steam cloud, etc). I now have a bunch of re-usable modules for all of the above and more in my "engine" wrapped around Love2D.

This is the 4th game I've shipped with the Love2D framework and I really love it so far. I think I'll continue to use it for all future 2D projects (though I've been eyeing Godot for 3D recently).
#### Other tools I used that I recommend
* [Tiled Map editor](https://www.mapeditor.org/)
* [LMMS for music](https://lmms.io/)
* [luasteam for steam API](https://luasteam.readthedocs.io/en/stable/)
* [aseprite for all sprites / animations](https://www.aseprite.org/)

### I developed more "Emotional poise"
I used to get really anxious before game releases, but over the past year and a half I've released many games. With every game I release, I get better at handling the "Post-release jitters" that come with releasing something into the wild.

With this steam release, I was still quite anxious on release day but the anxiety faded pretty quickly when I saw that the game didn't launch with any huge bugs / crashes. I think I'll be even less anxious for my next steam game, whenever that is.

In general, I think I've done a really good job of slowly growing out my audience and scope over the past two years, and this commercial game is a nice capstone to my progress.

### Some players really love the game
The median playtime fluctuates between 45-55 minutes, which is apparently below the average on steam. However, if we look at the following chart:
![playtime](https://i.imgur.com/wM37NMw.png)

we can see that while most players seem to bounce off the game after 1-2 runs, there are a small group of players that seem to *really love* the game. I'm really happy that I could make a game that resonated this much with some players.
### Miscellaneous things I'm proud of:
* I'm really proud of how the [soundtrack](https://soundcloud.com/abhisundu/sets/putrid-shot-ultra-ost) came out. I'm not a professional composer or anything, but I've been composing on and off for the last 6 years and I think this game's OST is my best work so far.
* After the 3 updates I made post-launch, I think the game is a great deal for 3 dollars. There's a solid amount of content for the money in version 1.4 with the different loadouts, challenge modes, and endless mode.
* The boss battles came out great. I know many players breezed through the bosses due to some of the more broken builds in the game, but the 3 main bosses and each of the minibosses all have really fun and fair attack patterns.

## Closing thoughts
I don't want to be overly critical and say "my game is bad because it sold badly": I wouldn't have released my game if I thought it was bad. I think PUTRID SHOT ULTRA is a good game. And after the updates I made, I think the remaining players really like it.

However, I underestimated how difficult it would be to balance the player's power curve in a "long-run" roguelike like this. This led to the game being boring for some players due to some builds completely trivializing what should have been a very challenging, engaging end-game. I have a newfound respect for all the expertly-tuned roguelikes that always feel satisfying, even when you 'break' them.

I also think that, even at its best, my game is pretty niche (given the playtime chart in the previous section). That said, it's nice to see some players fall in love with the game, even if they're not in the majority. I think I saw a few players in the steam reviews clock upwards of 15 hours, which is really cool to see.

I'm very thankful to the influencers who covered my game. It feels like my game sold a bit better than it deserved thanks to the influencer traffic! I'm excited to keep improving; it feels like if I follow the same process but develop an even better game, I may see significantly better results.

My game is far from perfect, but I'm proud of what I've made.
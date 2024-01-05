---
title: "Results one year after my first commercial game"
date: 2024-01-05
draft: false
---

I released [Putrid Shot Ultra](https://store.Steampowered.com/app/2053360/PUTRID_SHOT_ULTRA) on Steam roughly one year ago, on November 7, 2022.

{{<image src="/images/putridshot.gif">}}
## Sales
The game sold around 840 units on Steam in the ~1 year since its release. The game also has around 1800 outstanding wishlists.
![sales_graph](/images/PSUSales_1Year.png)

In the first month, the game sold around 300 units, so it's definitely surpassed my expectations one year later.
The sales graph for the game shows spikes during every Steam sale/discount after the release:

![sales_graph](/images/PSUSalesTraffic_1Year.png)

With the exception of the first Steam winter sale, each subsequent discount resulted in around 20-40 additional units sold. I discounted the game in an increasing fashion, increasing by about 5% every 3 or so discounts. Steam allows you to set discounts in advance, so every few months I spend ~5 minutes scheduling future discounts.

## Reviews and Reception
The game currently has 32 reviews, all positive:
![sales_graph](/images/positive32reviews.png)

While the reviews are all positive, I think this is more of a 'rotten tomatoes' 100%, if that makes sense:

![sales_graph](/images/mehreview.png)

As we can see, while the reviews are positive, that doesn't mean it's a 10/10. The general tone is "not bad for the price", so it's probably a solid 5 or 6/10 for most.

The playtimes of the reviews tell the real story: While a few players sunk 10+ hours into the game, most players seemed to be done after an hour or so.
![sales_graph](/images/medianplaytime.png)
One complete "run" of the game takes between 45 minutes to an hour, so this means most players either played a handful of unsuccessful runs, or stopped playing shortly after they won their first run.
## Retrospective
### What actually went wrong?
Honestly, it's sort of a shallow game. There's nothing wrong with that; For 3 bucks or less, it's got a solid amount of reasonably-polished content, but I think I invested my time in the wrong areas during development.
#### Replay value vs consumable content
Roguelikes tend to live or die based on how replayable they are. This means the variety of builds and playstyles needs to be really high. I thought I accomplished this with the 8 unique 'active spells' the player could equip at the start of the run, but these don't change your playstyle enough.
{{<image src="/images/psu_oars.gif">}}
{{<imageDescription text="Active spell: Swarthy Oars">}}

The active spells are basically your 'secondary' fire: An ability that charges up over time and does something cool. However, because they're secondary modes of interaction, they only change your playstyle when you choose to activate them, which is every 10-20 seconds or so. You're still shooting the same weapon the whole game.

In fact, most upgrades trigger automatically when you shoot, so even at the end of a run when you're meant to be a literal god, your playstyle is still the same: Shoot for a bit, roll around, repeat. I think this led to most players getting bored after a couple runs (which ends up being ~1 hour of gameplay).

I had been working on adding new starting weapons to the game that would drastically change your playstyle, but I lost interest in updating the game after a couple months. 

{{<image src="/images/PSU_secretweapons.gif">}}
{{<imageDescription text="A prototype for an alternate starting weapon">}}

Instead, before release, I spent most of my time on enemy and boss variety.

I think the game has a ton of variety in this way: There are 24 unique enemy types in the game, and 10 unique bosses and minibosses in the game, all with unique attacks and attack patterns. In general, I think I'm really good at boss attack-pattern design, i.e coming up with attacks that are complicated enough to be engaging but still fun to dodge and play with.

However, I don't think roguelike players really care about this. For example, I don't really care which boss I'm facing in a game like Risk of Rain 2: It's just a big health bar that I get to watch tick down. If I had spent less time on enemy and boss design and more time on adding new ways to play the game, I think it would have been more successful.

Bosses and enemies are 'consumable', so adding them to my game was only 'additive' in terms of content. Adding "new ways to play" makes all existing content more interesting, so adding a new character or weapon is 'multiplicative' in terms of content.

All that said, I don't have many regrets here: I enjoy making bosses, and Putrid Shot Ultra's bosses are really fun. In the future I'll probably prioritize making systems that give you a better playstyle variety, and *then* make some cool bosses.

I also think the stage variety is too low. There aren't many stage variants, so the only real 'procedural' aspect to the game is the upgrades you find. Some players even called this out in the reviews, mentioning that there wasn't enough level variety. In the future, I'll probably spend more time on level generation.

#### The art is bad
Previously I'd said that I stood by the game's art style, saying it was meant to be 'retro', but I think I'm lying to myself: The game looks bad. I think the idea behind the aesthetic is good, but my execution was not. I'm sure a good artist could take the same aesthetic and make it look 10x better, but I'm not a good artist (yet). 

{{<image src="/images/psu_finalzone.gif">}}

I also intentionally cut a ton of corners art-wise to shorten dev time, so the art is bad even with respect to my own actual skill level.

My newest roguelike [Spectral Slash](https://abhimonk.itch.io/spectral-slash) is probably much closer to my art skill ceiling right now:
{{<image src="/images/spectralSlash.gif">}}

I don't think "good art" is a hard-requirement for a game to be successful, but I think it helps a ton. I've seen games with honestly clunky mechanics sell decently-well thanks to solid art. I don't think it's something a solo dev needs to invest a *ton* into, but it's one of those things where you need to *at least* clear some minimum bar of art quality, and I don't think I'm there just yet.

I'd been practicing art a decent amount in 2023, and I plan to practice a lot more this year since I'll have more free time. Hopefully I'll keep improving and eventually be able to make better game art.

#### I spent way too much energy marketing
The more I think about it, the more I feel like most marketing is a waste of time for a solo dev. I think the bare minimum marketing is:

1. Post a demo to Steam + itch
2. Make at-most 1 post to reddit
3. Send free keys to streamers / youtubers
4. Enter Steam festivals

Anything outside of that feels like a waste of energy. The above 4 steps account for basically all of my game's sales. Maybe I'd feel differently if I had a hit game that went viral on TikTok, but those games probably get even more traction from the above 4 steps anyway.

I also spent a long time obsessing over reddit posts, tweets, and my Steam tags. I shuffled the game's tags around multiple times before release to see if anything would fix my game's abysmal wishlist rate, but of course none of it worked because my game lacked *the stuff*.

Even more than the time investment, I spent way too many *brain cycles* thinking about marketing. I constantly lamented my game's poor performance pre-release, venting my frustrations into a hidden devlog instead of actually working on my game.

In the future, I'll stick to the above 4 steps, maybe with a [little extra](http://localhost:1313/posts/marketing-free-games/), and spend the rest of my time making something cool.

### What actually went well?
#### It only took 200 hours to make
Much of that time was doing 'Steam stuff' and QoL that I'll never have to do again, so my next commercial game will take even less time. Also: I've spent more than 200 hours on plenty of projects that never saw the light of day, and yet I spent only 200 hours on this game? and it earned me 2 grand?? Yes! Haha Yes!!

For me, this is the optimal dev time for a short Steam game. I think my next commercial game will be similarly-scoped.
#### The music kicks ass
I'm so damn proud of the [OST](https://soundcloud.com/abhisundu/sets/putrid-shot-ultra-ost). I still listen to it regularly just for fun. Hell, I'm probably the only person that still listens to it, but it's seriously my best work. Maybe that's sad, but I don't care.

The main motif is super catchy and each track has a cool way of using it while also progressively introducing new ideas. The tracks are all pretty balanced too, which is uncommon for me since I never really learned how to 'master' a track.

I've improved my music workflow since then, so I think my next full OST will be even better.

#### A few people loved the game
It always blows my mind that people are still playing this game. I know a couple players that clocked 20+ hours in my dinky little 3 dollar game.

Having a handful of people, people who have no personal connection to me, *truly love* something I've made, makes this feel like a success regardless of the sales.
## Closing Thoughts
[In the past](https://abhisundu.com/posts/gamedevlottery/), I think I'd been a bit too precious about all of this. Making money off of games is cool and good, and I'm going to keep doing it.

I don't need to beat myself up for charging money; I don't need to beat myself up for not making *the next big thing*; I don't need to feel guilty or unskilled for any of this.

I want to gain even more 'emotional poise' this new year. I thought I was ready for a commercial release last year, but goddamn, hitting that 'release' button and watching reviews, videos, and bug reports roll in was terrifying. I was constantly anxious. If I had known how anxious I'd be, I probably wouldn't have even released the game.

The only way to get tankier is to just keep increasing volume, so I want to keep releasing games this year. I want to experiment with stuff outside my comfort zone, and then crush something in my wheelhouse. I want to keep improving every aspect of my gamedev skills.

Until then, I'm happy with my first Steam game. I'm glad I made it.

**-------------------------------------**

If you want to be notified when I make posts like this or release games, consider signing up for my [mailing list](https://mailchi.mp/fe0667f0520b/abhi-sundus-mailing-list).
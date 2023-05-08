---
title: "Sekiro vs Vampire Survivors: Adversary-focused vs Player-focused design"
date: 2023-05-08T11:20:54-04:00
draft: true
---

Recently, I've been thinking about games as being on a spectrum from "Adversary-focused" to "Player-focused":

<insert image of spectrum>

At a high level, an adversary-focused game drives the player by giving them a very simple toolset and providing them with a variety of adversaries to test their mastery of said toolset. A player-focused game gives the player a variety of tools to use/combine and drives them to test these tools out against adversaries which don't need to be varied.

## Adversary-focused: Sekiro, Shadows Die Twice
Sekiro is the quintessential adversary-focused game. You have a very limited toolset in this game:

- A single weapon
- The ability to deflect and counter
- A handful of prosthetics (tools) and special attacks equipped one-at-a-time

You can't really have a "build" in Sekiro. You either learn to deflect and master every enemy's attack patterns, or you simply stop playing. There are a few exceptions to this (i.e using clever combinations of prosthetics and special attacks to trivialize a fight), but these are usually only used by speedrunners so I'll consider them outside the scope of this discussion.

So why do people play Sekiro? Because of the *variety of adversaries*. Every boss needs to have its own unique moveset and attack patterns for a game like Sekiro to be interesting. If you were just mowing down hordes of enemies, Sekiro would be really boring.

By giving the player a restricted toolset, the designers have leeway to create really complicated enemy attack patterns to keep the game fresh. The designers also don't need to worry about balancing a boss for all "builds", because there's only 1 build in sekiro: Attack and deflect (or die (twice)). Finally, because the player's toolset is so simple, players can experience a noticeable growth in their own skill level over the course of the game. Using the same tools for 20+ hours against different adversaries is basically 'learning an instrument the right way': It's the perfect way to practice something.

The side-effect of this is that each "unit of content" is quite expensive: If you wanted to create a Sekiro expansion, creating new prosthetics and special attacks would *not* be the way to go. You'd need an entirely new string of bosses, each with their own unique animations and attack patterns. Looking at Sekiro Mods, the most popular mods are those that either
- introduce QoL like a skill wheel
or
- add entirely new attack patterns to existing bosses
This is much different from just tweaking some numbers and calling it a day.

## Player-focused: Vampire Survivors
Vampire Survivors (and the bullet-heaven genre in general) is the quintessential "Player-focused" game. The entire game is about building an interesting combination of 'tools' to use against enemies. The enemies themselves might as well be blobs of meat; They don't matter.

While Vampire Survivors has enemy variety, it absolutely didn't need it to be successful. The player is driven by obtaining new passives and crafting their own build. The replay value comes from recombining the pool of tools in new and interesting ways through randomness ("yee haw, I've got a holy water build this run!").

This might be a little tougher to balance, as players might have very different experiences based on their 'build', but this isn't too huge of a problem in the roguelike genre due to randomness and permadeath. The fact that you might get a broken build one run won't ruin the game for you, because you might get a completely different setup on the next run.

The side-effect of this is that each "unit-of-content" is a bit cheaper to make, because it multiplies against existing 'units of content'. If you add a few new items to Vampire Survivors, you not only get the benefit of the new items added: You also get the benefit of the *combination* of the new items with the old items. The synergies build upon each other.

An expansion to Vampire Survivors really just needs to be a collection of new passive items that create new synergies with existing passive items.

## Other examples of Adversary vs Player focused games
As with everything, this is a spectrum:

(notation: 30/70 player/adversary means 30% player-focused, 70% adversary-focused).

- SNKRX - 100% Player-focused. I genuinely don't think there's more than like 2 enemy types in this game (small bean, and big bean), you cannot convince me otherwise. The real fun comes from building your snake.
- Slay the Spire - like 70/30 player/adversary. Might be controversial, but enemies are just a collection of "attack, defend, apply status" behaviors. IMO the real fun in the game comes from the deck that you build.
- The Binding of Isaac - like 60/40 player/adversary. A lot of the fun in the game comes from the weird cool builds you can make, but enemy variety and room variety is still very important.
- Wildfrost - Honestly like 50/50 player/adversary. Your build is important, but moment-to-moment decision making against the pool of encounters is really important. Once you get good at the game, it feels like you can find a decent build most runs and it comes down to how you plan your turns against each fight.
- Elden Ring - ranges from 70/30 to 30/70 player/adversary. The game has a lot of build variety when you first start (so it's player-focused early on when you're still deciding your build), but once you get into the groove for your build, the game shifts to being more adversary-focused.
- Celeste - 100% adversary-focused (where the adversaries are the levels themselves)

If I had to be specific, I'd say Sekiro is really 10/90 player/adversary, since there's a *tiny* bit of build-making when you pick shinobi tools and your special attacks / skill tree.

<insert spectrum with each game on it>

## Why does this matter?
One of my favorite blog posts about game design is [Assessing Risk](https://derekyu.com/makegames/risk.html) by Derek Yu. At one point, he talks about the "amount of unique content" your game requires:

*"The more one-off, non-reusable content you'll have to make, the more time it will take to make it"*

With this context, it becomes a lot more clear why adversary-focused games can be really tough for a solo-dev to make. I once made a boss rush for the LowRezJam2021: It took me roughly 45 hours of work to make 3 polished bosses with their own attack patterns and behaviors.

If I wanted to add another boss, it'd probably take me at least 5-10 hours of work.

In comparison, adding a new card or enemy in a deckbuilder I made a while back takes probably a few minutes each.

TODO finish this
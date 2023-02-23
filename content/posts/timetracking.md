---
title: "I tracked every minute I spent on gamedev for 3 years"
date: 2023-02-21T18:10:11-05:00
draft: true
---
Over the past 3 years, I've spent hours making different games. The games ranged from short projects taking only 20-30 hours to much longer projects taking upwards of 200 hours. Many of the projects did not see the light of day, but most of the projects ended up shipping in one way or another. In tracking this time, I learned how long it takes me to "make a thing", what types of project cause me to burn out, and how time tracking affects the way I work in general.

**Insert pie chart of all gamedev done over the years**

**Insert a gif of a pico 8 game**
**this game took me 25 hours to make**

## Time Tracking as a Productivity Hack
When I was a kid, I was obsessed with self-improvement and "life hacking". I'd mainline every ted talk, article, and lifehack reddit post I could get my little skeleton hands on, drinking in the fantasy of turning into the perfect version of myself.

Nowadays, while I'm a bit more disillusioned to self-improvement as a genre, the world of "Time management self-help" is still one of my guilty pleasures.

**Insert picture of deep work**
**ok this book is actually decent though**

It's a pretty common productivity "hack" to use a timer as a way of keeping you focused. The act of starting a timer forces me to acknowledge beginning a task, which makes me more likely to be focused at the beginning. The ticking of the timer increase the guilt I feel when I go 'off task', working on something else or distracting myself. In this way, starting a timer is a good way to execute focused work (or "deep work" if you're a fucking nerd), and I'd recommend it for those reasons.

Being able to press stop on a timer also gives me an opportunity to really let go of whatever I was just working on. This isn't to say I don't think about my games when I'm not working on them, but being able to literally press stop makes it easier for me to mentally do the same.

I started tracking time as a way to find more time in my day for my many hobbies. I started off recording everything, like time spent watching TV, playing games, mindless browsing, and hobbies to see where I was 'wasting time'. Tracking everything I did ended up being a huge pain, so nowadays I only record how much time I spend on hobbies and work.

Since then, my goal became to better-understand how long it takes me to actually *make things*, so I could better-scope my projects around a tight schedule. I ended up learning a lot about how long it takes me to create a certain amount of gameplay, and how that time scales with respect to a game's scope. I also learned that tracking your time can cause you to optimize the time you spend in interesting ways, both good and bad.

## Logistics
I use an app called aTracker (disclaimer: I am not sponsored by this app). It has a free version that I used for the first year with good success but I've since upgraded to the paid version to avoid the ads. For every new gamedev project I start, I create a new "task" on the app.

**Show atracker UI**

Whenever I'm about to work on the project, I tap the project to start the timer and stop the timer when I stop working. When I'm finshed with a project, I archive the task on the app. The app keeps track of the total time spent on each task, so with the above workflow I can measure how long it takes me to "make a thing".

## How long does it take me to make a thing?
To start, let's look at some overall data:


**show graph of increasing time spent on gamedev for each game**
I spent **INSERT AMOUNT** hours on gamedev in the past three years, ranging from tiny 1-2 week projects (~20-30 hours) to multi-month commercial ordeals. Since my goal was to better understand how long each "unit of content" takes for me to create, let's graph the amount of time spent on each game VS the amount of "content" in each game in terms of hours.

**show graph of hours spent (x axis) vs content in game (y axis)**

Not a huge surprise here, the longer I spend on a game, the more content I can create. **TODO make some statement on the slope or curve**

You'll notice that the games I make tend to fall into one of three buckets:
- Short project (20-40 hours)
- Medium project (50-90 hours)
- Long project (150-200 hours)

## Short Projects (20-40 hours)
These were usually PICO-8 games. The PICO-8 restriction model forces me to ship games roughly at the 30 hour mark unless I'm working overtime on music and story. PICO-8 prevents you from having more than 8192 symbols in your code (which translates to around 2000 lines of lua code), which usually takes me around 30 hours to write.

**List the 20-40 hour projects with links and time spent on each**
**SH4DE, Cards of the bog, PUTRID S4NDs, Olden Peak, TRYH4RD jam version, Six Cards Under**

To be honest, these games probably had the best "fulfillment-to-effort" ratio. I'd spend between 1-3 weeks on a simple idea, expand on it as much as I could in that time, and then ship a game. Each of these games got thousands of plays on itch.io, despite only taking a few weeks to make. I never once got sick of working on any of these games due to their short development cycle.

And if I ever got sick of one of these projects, I felt comfortable shelving the project indefinitely due to the lack of a sunk cost.

The only problem with this category of games is that their "effort-to-content" ratio is lower than other categories. This is because it often takes at least 5-10 hours to even set up the core systems of a game.

Given that this initial startup cost gets paid no matter what game you're working on, only spending an additional 10-20 hours on the systems you just created cam feel wasteful.

## Medium Projects (50-90 hours)
These projects were more meaty games with multiple levels amd mechanics. I only made two of these games over the last few years.

**List TRYH4RD conqueror edition and Planet D4RK**

I think this is the sweet spot for the "effort-to-content" ratio. O still pay the initial "game systems dev" startup cost, but I'm able to spend more time squeezing each drop of content out of the idea.

For example, TRYH4RD is included in both this category and the previous, because the jam version only took 45 hours and featured only 3 bosses. However, feeling that there was more to explore with the mechanics, I spent another 30 hours adding new bosses and attack patterns on the existing systems.

Since I'd already written the core combat, I could spend these 30 hours really fleshing out crazy attack patterns that fans really loved.

## Long Projects (150+ hours)
These are the "soulsuckers" of hobbyist gamedev. The ones you wish you'd never started; The ones you want to quit if not for their sunk costs; The ones where you don't care about how well they're received, because you're just happy that you shipped.

**List the 150 hour projects**
**Dreams of D4RK, Jingnon's ascent, One Shot Dog, PUTRID SHOT ULTRA**

One thing you may notice from this is half of these projects are unfinished. I only finished the demo for Dreams of D4Rk, and One Shot Dog never saw the light of day. Jignon's ascent only shipped because I realized I would never finish unless I gave myself a hard deadline.

I think these projects are the most 'dangerous' to me as a hobbyist dev. I can really only spend around 1 hour per day on gamedev, so a 200 hour project can easily take me 6 months to a year to complete. This is a *long time* to spend on a single game, especially as one person. The allure of picking up a new technology or running with a new game idea is ever-present and tantalizingly strong.

## The 30 hour mark vs the 150 hour mark (consider removing this section)
I find that I tend to want to "quit" at the 30 hour and 150 hour mark for most projects.

At 30 hours, I usually either hit one of these three "endpoints":

1. The core systems are all great and proven to be fun. Now I get to go wild and just make a ton of content, drawing the line wherever I feel like stopping.
2. The core systems feel bad, and I've been lying to myself for the past 25 hours. It's time to quit and move onto a different project.
3. The game is almost done, just need to make a final push for 5-15 hours.

At 150 hours, I hit slightly different 'endpoints':

1. The game is almost done, and the existing content is very polished. All I need to do is add the finishing touches like menus, cutscenes, ending/story, etc. I will descope where I can to ensure this game gets done by the 200 hour mark.
2. The game is nowhere close to being done. I still have a ton of content to create, and I've dug myself into a hole so I can't meaningfully descope without ripping out entire systems that I like. I will be working on this game until the day I die unless I give up here.

## Optimizing for a number
When I start tracking something, I naturally start to optimize for it. I think this is common for most people (i.e calories are numbers, so people naturally try to optimize that number one way or another).

When I started tracking gamedev time, I subconsiously started trying to optimize that number. This is both good and bad.

### The good: Focus and efficiency
Tracking my gamedev time has forced me to focus 100% of my energy on gamedev when the timer starts. I enter a "flow state" much faster now, and can get huge amounts done in the 1-2 hours that I spend on it at a time.

I no longer play a youtube video or a podcast in the background of gamedev. I focus all my energy on the current task and I feel really productive when I'm working on games.

### The bad: Cutting corners
Since I'm trying to optimize the "time spent" number, I found myself cutting corners quite often, especially during my most recent commercial project. I reached a point where I realized making "good art" for the game would take too much time. Learning how to improve my art would also take too much time, so I simply made bad art for the game.

I caught myself doing the same on my current project. I want to improve my art, but I caught myself "half-assing" the art with the intention of maximizing my "content-per-hour" ratio so I could make the game faster.

# Conclusion
Nowadays, I still track the time I spend on gamedev because I like knowing how long it takes me to make a game. If I know that I'll have a free schedule for 2 weeks, I can "budget" time for a quick pico 8 game because I know that it'll only take me 20-30 hours of work. This makes it really easy to confidently explore ideas knowing that I won't get caught in some multi-month long sunk cost.

I'm also able to catch myself before diving into an insane multi month project because I can look at my time spent, compare it to the time spent for other projects, and make a well-educated guess on how much longer it will take to finish.

However, I've been trying to catch myself "optimizing", to make sure I'm not intentionally creating subpar content just for the sake of maximizing my "content-per-hour" ratio. It's a lot harder to commit to learning a new skill while making a game if you're watching a timer tick up with every minute you spend fumbling around with this new skill. For that reason, I've been trying to be more detached with my time tracking.

All that said, I highly recommend tracking the time you spend on projects. Not for efficiency or productivity, but just to help you understand how long it takes for you to make something you like.
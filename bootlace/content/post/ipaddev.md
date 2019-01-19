---
showonlyimage: false
draft: false
image: ""
title: "iPad Pro: Dev blog"
date: 2019-01-19T12:10:00+01:00
weight: 1
categories:
- dev
tags:
-"iPad Pro"
---
One of the primary hurdles in the decision to buy an iPad Pro as a laptop replacement, was 'can I use it to write and publish games?'. This is from the perspective of a lifelong coder. I was an 8bit machine code programmer in the 80s, the iPad Pro is the future finally arriving for childhood me (well, sans holographic projections :)).

The journey begins...
<!--more-->

**The beginning**

I bought an iPad Pro (10.5) in 2017 with the intent of seeing if I could use it as MacBook Pro replacement (for my needs, at least). The incentives primarily being lower weight, smaller baggage footprint, and typically better battery life (probably mostly down to use patterns). I was making a lot of trips to the city for 'culture' (3hr journey) and ultimately found that as part of packing for more than a night, the weight difference wasn't all that noticeable. Anyway, the experiment was cut short when about a month into ownership I dropped the tablet onto a granite floor, smashing the screen into more pieces than... Well, not massively economical to fix, so decided to just go back to my MBP.

With last years updated iPad Pros, I decided to give it another go. Shame the keyboard and pencil weren't transferable from the 10.5", but really like the larger screen with less bezel. I went for the 11" as I ultimately want it to still feel comfortable as a tablet. I suspect I may come to regret this.

Primary concern with buying an iPad Pro as a tablet replacement, is that I'm a coder at heart, and I was finding it hard to see how I could use the iPad as a proper coding device for the sort of apps I make (games!). I shall blog my experience of trying to create games on iPad Pro exclusively. 

**Blogging on iPad**

First thing I wanted to do was ensure I was able to update the blog from the iPad Pro itself. I've historically written my own CMS using MySQL and PHP, but wanted something lighter weight, but not the constant update, security hell of something like WordPress. Decided to make a static site (no cookies, no fishing for privacy, no concerns over GDPR), and was initially just going to create HTML pages by hand and maybe script some sort of automated indexing scheme. Instead bumped into the world of static site generation, and in particular found myself quickly taken with [Hugo](https://gohugo.io). I was quickly able to setup a simple Hugo based site on MBP and then looked at how I could transer this process to iPad. A quick google and the simplest solution became use cloud based repo ([github](https://github.com)) and use site that specialises in the processing and hosting of static sites ([netlify](https://www.netlify.com)). At this point, all updating the site on iPad required from me was a decent github client ([Working Copy](https://workingcopyapp.com)). I've barely touched the surface with Working Copy, but it's brilliant. To create a post on iPad, all I need to do is pull the site (if needed), duplicate a previous post, rename it, update meta data and content, commit, push, and wait a minute or two for Netlify to pick up the change, build and publish it automatically for me.

I suspect I will actually move away from Netlify at some point, and sort out the automation and hosting myself. Although I also suspect I'll need to think of a reason why to :). I need to work out a less public preview method, and need to consider the hosting of more varied content via the same domain.

**Dev on iPad**

The biggest hurdle for me when considering the iPad Pro, was that of wanting to be able to do general coding, and ultimately be able to at least build and publish iOS applications. I'm still considering lots of options, terminals are great for a bunch of stuff, and ssh onto any machine means I can do a bunch of C/C++ and try things out without straining the tablet itself. Obviously testing more graphical stuff becomes a challenge, and remote desktop, photon, etc, are only partially practical.

I discovered Pyhtonista and Codea on the app store. I love Python (although I barely know it :)) and hate Lua (I know it too well :)), and whilst Pythonista is a nice environment to work in, the low level coder inside of me can't quite live with the performance differential between Python and Lua. Codea being the Lua based one and additionally having a path to export, compile and publish projects to the app store is where I'll be focusing my efforts. At least initially.

**Random thoughts**

Writing this is taking a long time, and time is precious. I have far too much fun stuff to do, and too much not so fun stuff. Fingers crossed, I'll stick with this, and hopefully abridge less often.


---
title: "My Thoughts on the Recent Karoo-Shimano News"
date: 2022-06-02T15:29:27-07:00
summary: "Turns out there was more to this one than I initially thought."
description: "General thoughts and review on the current Hammerhead Karoo 2 and Shimano recent news from an engineer's perspective."
image: "karoo"
type: "tech"
categories: ["Technology"]
tags: ["Technology", "News", "Shimano", "Karoo"]
keywords: [
    "Hammerhead Karoo Shimano Engineer Reaction",
    "Tech blog Hammerhead Karoo Shimano",
    "Cycling Data Warehousing",
    "Cycling Machine Learning",
    "Shimano private ANT",
    "Proprietary wireless protocols in Cycling",
    "Cycling technology",
    "Shimano Di2 Integration with Hammerhead Karoo"
]
draft: false
resources:
- src: '*/karoo.jpeg'
  name: "karoo"
  title: "Such a beautiful screen"
  params:
    alt: "Close up view of the Hammerhead Karoo 2 cycling computer device fitted to a set of BlackInc handlebars"
- src: '*/karoo_shimano_bars.jpeg'
  name: "karoo_shimano_bars"
  title: "I always enjoy this view"
  params:
    alt: "View over Factor O2 VAM bicycle handlebars by Black Inc showing Shimano Dura Ace shifters and a Hammerhead Karoo 2 cycling head unit"
- src: '*/nerd.jpg'
  name: "nerd"
  title: "Yeah, it feels like that sometimes"
  params:
    alt: "Stock photo of a man dressed as a nerd"
    width: 50
    exclude_gps: true
- src: '*/blackbox.jpg'
  name: "blackbox"
  title: "A common term used in a lot of places"
  params:
    alt: "Stock image of a black box representing a system where inputs come in and outputs are returned out"
    width: 30
- src: '*/bwc_tunitas.jpeg'
  name: "bwc_tunitas"
  title: "Thanks for the shout out, Max!"
  params:
    alt: "Picture of BicycleWaterCooler website logo sticker artistically shot at the top of Tunitas Creek Road in Woodside, California"
    width: 80
- src: '*/hotdog.jpeg'
  name: "hotdog"
  title: "If you haven't seen HBO's Silicon Valley, you need to!"
  params:
    alt: "Screenshot from popular hot dog not a hot dog app from HBO's Silicon Valley"
    width: 50
- src: '*/asleep.jpeg'
  name: "asleep"
  title: "aka Shimano's PR department"
  params:
    alt: "Toddler falling asleep at the wheel of his toy car"
    width: 50
- src: '*/tinfoilhat.jpg'
  name: "tinfoilhat"
  title: "And down the rabbit hole we go!"
  params:
    alt: "Stock image of a man at a computer wearing a tin foil hat"
    width: 35
---
# Adding to the Noise
For those of you maybe less familiar with the context around this one, let's see if we can maybe go over some brief history first.

## First of all
The Hammerhead Karoo 2 is wonderful. I absolutely recommend it. And I still do. I haven't written a formal review on the device itself, but it's a small player in a very congested field dominated by both Wahoo and Garmin when it comes to cycling computers.

The company has been around for a few years, and the Karoo 2 has been by far their most successful product, and it's worthy of praise. It integrates well with everything, has support for both GLONASS and GPS satellites, bluetooth and ANT+ wireless protocols, has a beautiful screen, and has, by far, the best navigation that I've seen on a bike computer. 

My favorite feature? Regular updates with detailed release notes! The former release engineer in me is so happy by this single point, you likely don't even know.

{{< img nerd >}}

If there's one negative thing to say about the device, it's that the battery life is a bit on the lower side when compared to its competitors. It's really only an issue when you end up riding for more than about 7 hours, though, so it's easy enough to bring a small battery pack (with a usb-c cable, of course) to help it along for those last 20 miles or so.

## Timeline
This one is important because it sets the backdrop for our story.

* August 2020 Preorders for the Karoo 2 go live
* January 2021 I got my own Karoo 2
* January 2022 SRAM announces [they have acquired Hammerhead](https://www.sram.com/en/life/stories/hammerhead-acquisition)
* May 26th, 2022 Hammerhead [announces a change](https://support.hammerhead.io/hc/en-us/articles/360051706614-Hammerhead-Shimano-Di2) in its partnership with Shimano wireless Di2

## What's (ex)cluded in that Shimano Update
Basically anything that shows your current shifting on a Shimano Di2 system, a very good system in my opinion, is to be removed in the next update (as of June 3rd, 2022). This means what your current battery level is, the current gear you're in, how many times you've shifted, and even the support for using the hood buttons on your Dura Ace shifters!

# The Why
This is all outlined in much more detail over in the [DCRainmaker Article](https://www.dcrainmaker.com/2022/05/shimano-forces-hammerhead-to-remove-all-di2-related-functionality-from-karoo.html/comment-page-1).

The "official" statement and position of Shimano claims that [SRAM](https://www.sram.com/en/sram) is a competitor, which makes Hammerhead a competitor of sorts by extension. I put "official" in quotes because, to my knowledge, there really hasn't been an official statement yet from Shimano directly, and we only know this information from Hammerhead.

## Stupid? Perhaps. Unfortunate? Absolutely.
It really looks like Shimano is picking on the little guy here, and the people really out of luck are users of their really great product, i.e., you and me. 

Actively removing features and functionality that you've grown to really enjoy due to a spat between companies is not really the best situation when you're trying to grow your user and fan base. I mean, [Team Israel Start-Up Nation](https://www.eu.hammerhead.io/blogs/teamjournal/team-israel-start-up-nation-signs-2-year-renewal-deal-with-hammerhead) is running the Hammerhead Karoo 2 alongside all Shimano gear!

## Wireless Protocols
The DCRainmaker article above discusses this in more detail, but Shimano has not been very forthcoming in sharing their wireless standard. Nor have they been onboard with using more open standards that both SRAM and Garmin have been pioneering for years.

They choose to remain locked in to a private ANT network, something very similar to how my [Pioneer Power Meter]({{< ref "/reviews/Pioneer_Power/index.md" >}}) works. It continues to be a bit of a black box to us end users, while we all just simply assume it's "bluetooth". 

{{< img blackbox >}}

Basically it's going to require a key to properly authorize and encrypt / decrypt communication over a predetermined wireless frequency band (in the 2.4Ghz spectrum), a key that has to be negotiated. Or at least the process to determine that key has to be negotiated via a proprietary algorithm. For anyone who has worked with [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language) or [OAuth](https://en.wikipedia.org/wiki/OAuth) when it comes to web services, I'm going to assume the process is quite similar.

There's actually a really good [Wikipedia article](https://en.wikipedia.org/wiki/ANT_%28network%29) about the history and details around Garmin's work in creating the open ANT+ protocol based loosely around the concept of a PAN (Personal Area Network), one of which later became Bluetooth as we know it today.

# Why I get it, the Engineer Edition
I ran into someone last weekend at the top of a local climb in my area who knows a bunch of people in the industry. He's a local crit racer, recently participated in the [Cat's Hill Criterium](https://catshill.org/catscourse.html), and had some insight into the situation that he shared with me.

{{< img bwc_tunitas >}}

How we got into this weirdly specific conversation, I'm not sure. But hey, I'm always down to talk shop!

## It's all about the data collected
These days, everyone is obsessed with data. On its own, our personal data (especially cycling data) may only be helpful or interesting to you or to me. In large amounts, it's basically useless to most normal people.

But not to companies who have budgets for engineers who can spend 8+ hours a day doing something interesting with it!

Similar to when you sign up for a rewards card at your local grocery store, "the company" will collect data about your purchases. Then some engineering software collates it all together into a big digital "warehouse" where it's (hopefully) anonymized and data about all that data (i.e., "meta" data) is then stored as (also hopefully) insightful information.

I say "hopefully" a lot here because privacy in general [is a big topic in tech](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation) right now. Keeping personally identifiable information (abbreviated "PII") on your users has to be closely monitored. Severe fines can be enacted against companies who don't adhere to very strict standards when they come into contact with it.

### Still with me?
Wait, so why does any of this matter in this dispute between Hammerhead and Shimano?

Well, imagine you're collecting data points about cycling. This includes details about your shifting patterns, how often you shift, which gears and gear ratios you're using, how long you go before recharging your battery, etc. 

Now imagine correlating this information with the GPS coordinates of each and every one of your rides, along with any other sensor information you may have running on your bike including speed, cadence, power numbers, you name it.

Put all of this into a big data warehouse and run some [MapReduce](https://en.wikipedia.org/wiki/MapReduce) jobs against all of it in hopes to find generalized patterns for all kinds of human behavior. For those of us who work around [Machine Learning](https://www.ibm.com/cloud/learn/machine-learning) and [AI Model training](https://www.telusinternational.com/articles/how-to-train-ai), this is pretty normal stuff, actually, we just usually collect it from some kind of website or service that all of us end users, you know, _use_.

{{< img hotdog >}}

Over time, enough data is built up, patterns are inferred, and business decisions about future products and updates are made. All based on the data that is being shared here on your behalf.

### Oof, I know
It's potentially a _lot_ of revealing information. Information that Shimano likely _shouldn't_ simply hand over without some careful analysis first. Although, in full disclosure, I'm a general [open-source](https://opensource.com/resources/what-open-source) advocate, so I'd definitely prefer Shimano to simply get on board with the community-defined standards that nearly everyone else uses these days.

Before anyone goes sounding off on some kind of conspiracy alarm, note that this is only for wireless data coming from Di2 units, something that likely doesn't really have much impact on each of our daily lives. It's also a small subsection of the overall market. I mean, we're just riding bikes here!

{{< img tinfoilhat >}}

For those of us less familiar with all of the above technology, think about the fun correlations you can use [Strava](https://www.strava.com) for when it comes to comparing yourself with your past times up certain segments to those you follow or to your previous efforts. Now imagine having access to more raw information and imagine an Elon Musk robot reading through that data at a rate of millions of times per second.

Okay, maybe that's too nefarious of a comparison. [But maybe it's not?](https://www.youtube.com/watch?v=Ra3fv8gl6NE) Who knows these days!

# Bringing it all Back to SRAM
So while Hammerhead has never traditionally been in the position to even be on Shimano's competitor radar, once they were acquired by SRAM, they suddenly were. A lot of the Di2 metrics and details that are run via Shimano's e-tube proprietary technology were, to my understanding, meant to be displayed _but not to be saved_ anywhere.

I'm guessing this is where Shimano and Hammerhead are going to have to go when it comes to renegotiating their licensing agreement here.

## My (non-engineer) final thoughts
I really like my Karoo, and I plan to keep using it. But unfortunately this whole experience has really sullied my experience with Shimano. I've loved Shimano and have exclusively used their products on my bike since getting into the hobby.

But if a company like this is so flippant when it comes to its end users, it gives me pause for concern. Concern that I didn't have once I started looking up wireless standards and protocols. To me, all of this sets the tone that they enjoy their position of power and that the market defers to them, rather than them providing what the market wants.

And it's not like Shimano has publicly stated any of this, either! Perhaps a lot of this would have been handled better had their PR department not been asleep at the wheel.

{{< img asleep >}}

So here's to hoping that Hammerhead can work out an updated deal with Shimano where they promise not to store any of Shimano's super-secret-proprietary shifting data! I can drink to that.

In the meantime, I'm holding off on updating my Karoo with any new software. I like my little pretty bubbles that tell me what gear I'm in.
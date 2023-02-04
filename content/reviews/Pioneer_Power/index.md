---
title: "My Pioneer Power Meter Review"
date: 2022-03-20T16:45:47-07:00
summary: "A no-longer-supported power meter still has some customers."
description: "Non-sponsored product review of the Pioneer Power meter used for detailed metrics for cyclists and coaches."
image: "power_meter_box"
type: "reviews"
categories: ["Product Reviews"]
tags: ["Pioneer", "Power Meter", "Product Review"]
keywords: [
    "Pioneer Power Meter review",
    "Pioneer Cycle Sports",
    "Pioneer power meter magnet",
    "Pioneer power meter app",
    "Pioneer power meter battery cover",
    "Cyclosphere app",
    "Power meter review",
    "Pros and cons Pioneer Power Meter",
    "Independent review Pioneer power meter",
    "How to fix Pioneer power meter",
    "Pioneer power meter dual ANT bluetooth"
]
draft: false
resources:
- src: '*/box.jpeg'
  name: "power_meter_box"
  title: "NOT an unboxing video"
  params:
    alt: "Box of Pioneer power meter before being installed on to a bike"
- src: '*/clean_crank.jpeg'
  name: "clean_crankset"
  title: "After a good cleaning"
  params:
    alt: "A clean Pioneer power meter after having been removed from a Factor O2 VAM bike frame"
    width: 50
- src: '*/force_vectors.png'
  name: "force_vectors"
  title: "Screenshot from Pioneer's site"
  params:
    alt: "A screenshot of how force vectors work on the Pioneer Power meter, taken from Pioneer's website"
    width: 75
- src: '*/fry.gif'
  name: "fry"
  title: "Not sure here..."
  params:
    alt: "Philip J Fry from Futurama not sure about something meme"
    width: 40
- src: '*/wahoo_pioneer.png'
  name: "wahoo_pioneer"
  title: "I mean, it's on their website, so it should work, right?"
  params:
    alt: "Screenshot from Pioneer's website showing Wahoo's integration with their detailed power meter metrics"
    width: 70
- src: '*/mode_switch.jpeg'
  name: "mode_switch"
  title: "Taken after sorting all of this out, of course"
  params:
    alt: "The Wahoo Elemnt Bolt devices page showing the Pioneer Mode Switch option"
    exclude_gps: true
    width: 50
- src: '*/sad_trombone_homer.gif'
  name: "sad_trombone"
  title: "Womp womp"
  params:
    alt: "Homer Simpson playing a sad trombone sound in bed"
    width: 50
- src: '*/battery_cover.jpeg'
  name: "battery_cover"
  title: "And I've tried to be good about this, too"
  params:
    alt: "Battery cover for Pioneer power meter non-drive side crank arm, showing wear and tear"
    width: 50
- src: '*/eh.gif'
  name: "eh"
  title: "Eh, what ya gonna do?"
  params:
    alt: "Patton Oswald saying 'eh'"
    width: 50
---
# Okay, so some quick background on this one...
With the intention to not make this too long of a read, I'm going to have to skip over why I feel like you may want or need a power meter, along with what you may need a power meter for generally.

I wanted to write about this particular power meter because I have a lot of mixed thoughts on it after owning two iterations of it. Plus, something recently occurred (for the second time) that made me realize that there needs to be more documentation and/or personal experiences for this power meter. It may help others who are struggling with the same issue.

And this is not to mention that Pioneer, as of March of 2020, [will no longer be in the power meter business](https://www.bicycleretailer.com/industry-news/2020/02/04/pioneer-exits-powermeter-market).

# First off, why Pioneer?
Out of all the power meters available, and from what I've gathered over the years, the Pioneer power meter is technically one of the most full-featured ones that are available. Some of its selling features include:

* It was one of the first power meters that worked reliably well (aside from [SRM](http://www.srm.de/product/powermeters/origin-road/))
* It's crank-arm based, meaning that you get _true_ left / right balance wattage metrics
* Battery lasts quite a while (they say 180 hours on their [website](https://www.pioneerelectronics.com/ephox/StaticFiles/PUSA/Files/Cycle%20Sports/Pioneer%20Cycle%20Sports%20-%20General%20FAQ.pdf))
* With the appropriate head unit (much more on this), you get a vast amount of metrics, some of which I've never seen anywhere else (i.e., force vectors throughout 12 points of your pedal stroke)
* It looks sweet with the battery cover that's built into your Shimano crankset body

## So, flip the script, what's not so great?
This is what I came here to write about. When the unit works, it works fantastically well, and you'll have zero issues with it. But, and this is a big but, there are some points to consider here:

* The device has (traditionally) been a black box of magic
* The left crank battery case is a soft plastic that, no matter how gentle you are with it, will start to strip out
* There's basically zero support out there when things go awry
* The unit dual emits ANT+ and Bluetooth and it isn't always clear to you as the end user what the differences are
* Confusion around why magnets are included on a newer power meter
* Older units don't have access to their Cyclosphere app to manage the device, and the interaction of said app is not great in my (very limited) experience
* I'm not so sure they're going to keep making these, or if they technically still (actively) support them

## Why should you listen to me and keep reading?
Well, I've owned two of these things, one of the first generation when I got my [Giant TCR]({{< ref "/blog/Introspective/N_Plus_One_Rule/index.md" >}}) in 2015, and another in 2019 when I got my [Factor O2 VAM]({{< ref "/blog/Introspective/N_Plus_One_Rule/index.md" >}}).

{{< img clean_crankset >}}

I've also been through two situations where a firmware update on my bike computer basically bricked my respective unit.

## So what happened?
In September of 2018, right before I was about to board a plane to visit [Girona]({{< ref "/travel/Spain/Trek_Travel_Girona_2018/index.md" >}}) on a fantastic cycling trip, a new update was pushed out to my {{< amzn asin="B06XT3YX7T" text="Wahoo Elemnt Bolt" >}} device. The idea behind this particular update was to integrate all the incredibly detailed metrics that no other power meter out there has (to my knowledge) to the Wahoo platform, a first for Pioneer.

### Detailed metrics, you say?
This means force vectors (directions your foot is actually pressing on the pedal) at 12 independently measured points around a single rotation of the cranks (you can see a depiction of this on the box above). I'm sure a few other things are included here, but to be honest, I've never used these features before. It requires magnets installed on specific points of your bike to get them, along with obviously a head unit that can actually pick up on these details.

{{< img force_vectors >}}

Previous to this update, only {{< amzn asin="B00KFK08CA" text="Pioneer's specific head unit" >}} (yeah, the one nobody really uses) would show these to you. And given that you get power, L/R balance, cadence, and other metrics without them, there isn't a lot of reason to put weird looking magnets on your shiny new road bike.

### So...what broke?
What broke during this particular firmware upgrade was a few things:

* The Wahoo mistakenly put the mode of the device into Bluetooth mode, rather than Dual ANT+ mode (technically some kind of proprietary private ANT band, so I'm told)
* To get the full metrics, you need to be in the Dual ANT+ mode, which meant that suddenly nothing was being read by my Wahoo, despite being paired with it
* There's no mechanism via the hardware to actually switch modes, and Wahoo didn't include this option via software in their update
* Wahoo had removed the previous firmware from their website, not allowing me to roll back my device

I basically had to make a last minute decision to buy a new power meter before my trip, which ended up being the dual sided {{< amzn asin="B07P5J1CT9" text="Favero Assioma" >}} pedals. They actually worked very well, I just didn't end up keeping them because I'm not a fan of the Look style cleat they come in, along with their increased stack height, and how they're weighted (they spun a lot for me). I'm sure I could talk about my experience here in a future post.

### How I fixed it
I had a lot of back and forth phone calls and text messages with a sales rep from Pioneer down in Long Beach who helped me do some initial debugging, none of which panned out unfortunately. He eventually connected me to someone who used to work for Pioneer who was a bike mechanic for [Studio Velo](https://www.studiovelocycling.com), up in [Mill Valley](https://www.google.com/maps/place/Mill+Valley,+CA+94941/@37.9067306,-122.5632255,14z/data=!3m1!4b1!4m5!3m4!1s0x808590733c5a3c93:0xd27fa4ddcff9d586!8m2!3d37.9060368!4d-122.5449763).

I had to drive my bike up there to see this bike guru who understood how all of this magic worked. He used a Pioneer bike computer that he had on hand to set the power meter back into Dual ANT+ mode for me, which then allowed me to connect back to it like normal again. Hooray!

## Fast forward a few years
Most recently, I went through a similar experience, this time with my [Hammerhead Karoo 2](https://www.hammerhead.io/products/hammerhead-karoo-2). Which is unfortunate, because after getting the above all sorted out, I have had zero issues with this power meter. Similarly with the newer one I had installed on to my Factor. Sure, I've seen it occasionally slow to wake up, and sometimes requires a refresh of my ANT+ connection to the device (thanks Hammerhead for providing that option!), but it has generally been great. I think most power meters still suffer from these occasional issues.

Last week, an [innocuous update](https://www.hammerhead.io/blogs/change-logs/karoo-software-build-version-1-279-1168?utm_source=Klaviyo_Campaign&utm_medium=email&utm_campaign=03102022_SoftwareRelease&bxid=HZmB9u&_kx=bfY3pt0Ez3BGzCvpnN7LYRTQLi0MCdxaFLKjMThyodY%3D.Qeyn8x) came through (Hammerhead is fantastic with these), and suddenly I couldn't find my power meter again. My Karoo lists out available ANT+ devices separately from Bluetooth ones, so I noticed that my device was appearing in both listings, despite not providing actual power details in either scenario. The ANT+ connection basically disappeared as soon as I managed to connect to it, and the Bluetooth one took a long time to connect, after which it only read zeros.

Frustrating, I know. But it all felt eerily reminiscent.

{{< img fry >}}

## What I did this time to fix it, and why I'm writing this
I reached out to Hammerhead for support. They were quick to respond and told me that no changes were put into this most recent firmware update to change the way these devices were being handled. Huh, okay.

The response recommended me unpair the device, then power cycle the Karoo. After doing so, I did manage to find my power meter again via the ANT+ devices page, but I didn't see any data come through for it. I actually couldn't reconnect to it after this initial pairing anyway. At the same time, I saw the unit also emitting on the Bluetooth band, too, which was basically the same behavior as last time.

At this point, I was resigned to the idea that I was going to have to drive up to [Studio Velo](https://www.studiovelocycling.com) to find this bike wrench guru again and try to force my device back into the ANT+ mode. That, or buy a whole new power meter arrangement.

At this point, [Rotor's modular setup](https://rotorbike.com/catalog/default/rotor/road/cranks.html) was starting to look pretty good to me, not going to lie!

### But then I realized something
I still have my Wahoo! In the last 3 years or so, I'm _sure_ some of this whole "process" has matured. Plus, from looking at the details page on Pioneer's website, I had a sneaky suspicion that perhaps the Wahoo could do this "mode switch" for me.

{{< img wahoo_pioneer >}}

So I booted it up, did a firmware update (it had been a while), then connected up my power meter. Luckily the Wahoo found it initially, and then I went into the device custom settings and, lo and behold, found the option to mode switch it.

{{< img mode_switch >}}

After a fretful minute or so, the switch was successful and the power meter was saying "Dual ANT+" in the Wahoo configuration settings. _This_ is the setting that the Pioneer power meter needs to be in to work as an ANT+ device properly.

Next up, I booted up the Karoo, and went scanning for ANT+ devices. Sure enough, it found the device, connected up to it, and after doing [today's ride](https://www.strava.com/activities/6856741129), it worked just as before!

# My Final Take on Things
Okay, that all is a lot to digest. That is, if you're not already neck deep in weird device compatibility stuff. It seems that there aren't a lot of great resources online to help out when it comes to using this power meter.

## If you like data...
It's fantastic. Especially if you like true left / right balancing of power, since there are two sensors (one in the crank spider and the other in the non-drive side crank). Some other spider based power meters like [Power2Max](https://www.power2max.com/en/) and [Quarq](https://www.sram.com/en/quarq) approximate this balance by only reading power measurements on the downstroke on each crank side, then doing some math to approximate the balance, left to right. I'm told it's actually pretty good, but is technically not a _true_ measurement.

## If you're working with a coach or were previously injured
If you're working with a trainer or coach, you may find value in some of this, too. I've heard good things about having something that measures left and right balancing accurately if you're coming back from an injury, as having this available to you during a ride can be helpful to re-train yourself. But if you're already within a 45-55 percent range left / right balance, it's likely that this number can just contribute to noise. Just one more thing to obsess over instead of just enjoying riding your bike.

## If you have a Wahoo or Pioneer head unit
Then it makes sense that you can use this device to its intended purpose. You have more direct control of the device and can change the internal hardware settings via remote software calls that the rest of us simply have to assume are correct before using the device.

If you additionally install the magnets (there's a little card that comes with the device that helps you install them correctly), you can also get some really cool metrics. If you're looking for info on how to this, I found a [video](https://www.youtube.com/watch?v=TDCswByI8xY) on YouTube about how to do it properly. They're just things I've never directly used. Which is funny because you'd think I'd be all over that one.

## If you get one of the newer versions
Then perhaps all of the above is a little less problematic. I believe there were / are three different generations of this power meter, and the newer ones from the third generation onward intrinsically support the Cyclosphere application. 

Although a quick Google search shows that the [Cyclosphere](https://cyclo-sphere.com) application's support has been terminated. Seems that you need to use [Shimano's Connect Lab](https://connect-lab.shimano.com/signin) instead.

{{< img sad_trombone >}}

Sad trombone, indeed, Homer.

Either way, perhaps this would remove a lot of the "black box" nature of this device. I haven't used either application really, so I can't speak to it directly. Sounds like very few may have, at this point.

## However...
This power meter is [not going to continue in production](https://www.bicycleretailer.com/industry-news/2020/02/04/pioneer-exits-powermeter-market) at this point, as of March of 2020. I doubt Pioneer will be putting any kind of budget towards it, outside of warranty claims, and to my knowledge, not a single pro team is using them for training (most seem to be going with the [Shimano crank-based power meter](https://bike.shimano.com/en-EU/product/component/duraace-r9100/FC-R9100-P.html) arrangement). The market has changed significantly since this device was first made available, with many alternative options that have nearly all the same metrics and options, each with much newer interfaces and updates. Most are also a lot easier to get support for and operate a bit more "naturally" in this particular age of connected devices we live in.

Oh and don't forget about the battery cover on the non-drive crank side. It's a problem unfortunately.

{{< img battery_cover >}}

The replacement product number is [SGY-LC910](https://www.pioneerelectronics.com/PUSA/Cycle+Sports/Accessories/SGY-LC910), and appears to no longer be available. Bummer.

# Wrap Up
So I guess for now, I'll be keeping my Pioneer power meter. But only because it doesn't make sense to get rid of it, as it does the job for me in my current configuration. I still generally like it, the looks, the data, the fact that it's so integrated into my crankset, it's usually not something I have to think about very often.

But given the above caveats, along with the fact that I'm not using any of the real in-depth features it has, my next power meter will likely be something else entirely.

{{< img eh >}}

Hope this was helpful to someone out there! I know I would have really appreciated knowing what I know now.
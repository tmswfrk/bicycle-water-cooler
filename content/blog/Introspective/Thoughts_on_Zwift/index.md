---
title: "Some thoughts on Zwift"
date: 2020-05-30T17:04:39-07:00
summary: "I have a lot of thoughts on this one."
description: "My thoughts on Zwift, the indoor fitness training phenomenon that's actually fun."
image: zwift_gorby
categories: ["Virtual Training and Riding"]
tags: ["Zwift", "Virtual Riding"]
keywords: ["Zwift", "riding a bike indoors", "riding a bike on a smart trainer", "indoor training on a bike"]
draft: false
resources:
- src: '*/zwift_gorby.jpeg'
  name: "zwift_gorby"
  title: ""
  params:
    alt: "My thoughts on Zwift, the indoor fitness training phenomenon that's actually fun. Image contains: virtual rider, virtual riding, Zwift, Watopia."
- src: '*/peloton_bike.jpg'
  name: "peloton"
  title: "It looks pretty similar to a regular spin bike, really"
  params:
    alt: "Stock image of a Peloton bicycle unit"
    width: 50
    exclude_gps: true
- src: '*/Watopia.jpeg'
  name: "Watopia"
  title: "Wheee!"
  params:
    alt: "A virtual world within Zwift with a cyclist avatar riding a bike through the desert"
- src: '*/my_zwift_setup.jpg'
  name: "my_zwift_setup"
  title: "Definitely don't feel like those wheels are being used properly"
  params:
    alt: "A Giant TCR bicycle mounted into a direct drive smart trainer indoors overlooking a window with a small desk in front"
    width: 50
    exclude_gps: true
- src: '*/directdrive.jpg'
  name: "directdrive"
  title: "The gearing arrangement should match the one your wheel"
  params:
    alt: "The CycleOps Hammer smart trainer with a Giant TCR bicycle mounted on to it"
    width: 50
    exclude_gps: true
- src: '*/badtime.gif'
  name: "badtime"
  title: "A bad time, indeed."
  params:
    alt: "South Park GIF of ski instructor having a bad time"
    width: 50
- src: '*/fluidtrainer.jpg'
  name: "fluidtrainer"
  title: "Get a special, hard, red tire for this one put on to your wheel"
  params:
    alt: "Stock image of a bicycle trainer that uses fluid to provide resistance for physical training"
    width: 50
- src: '*/terror.jpeg'
  name: "terror"
  title: "Still strikes terror in my heart"
  params:
    alt: "Stock image of a cyclist on a bicycle that is on a set of bike rollers for use with coordination training"
    width: 50
    exclude_gps: true
- src: '*/supertuck.jpg'
  name: "supertuck"
  title: "Look at how pro I am! Virtually, of course"
  params:
    alt: "A virtual avatar cyclist in Zwift performing a supertuck in-game"
- src: '*/dog.gif'
  name: "dog"
  title: "Who's a good bike rider? You're a good bike rider!"
  params:
    alt: "GIF of a dog riding a bicycle down a street"
- src: '*/trex.png'
  name: "trex"
  title: "Rawr"
  params:
    alt: "Drawing of a T-Rex on the back of a bicycle"
    width: 35
- src: '*/wkgdiff.jpg'
  name: "wkgdiff"
  title: "At the same w/kg, each rider will go up the hill at a different speed"
  params:
    alt: "Two happy looking cyclists riding their bikes up a hill"
    width: 50
- src: '*/yeahright.jpg'
  name: "yeahright"
  title: "Suuuuuuuuuure you do, number 10"
  params:
    alt: "Zwift Companion App leaderboard showing different kinds of riders, including one who appears to be cheating"
    width: 50
---
# The recent craze for bike riders
So for those of you NOT familiar with Zwift, imagine the idea of ["gamification"](https://en.wikipedia.org/wiki/Gamification) applied to bicycle riding. Let's first mention a few things as to what Zwift is NOT, since I think there are some misconceptions here to the uninitiated.

## It's NOT Peloton
After their famous [Superbowl ad](https://www.youtube.com/watch?v=ijof8uw4OHs), Peloton suddenly went from pretentious, single image marketing campaigns to a common household point of interest. A lot of the news around the ad claimed sexist vibes, but it certainly has helped increased their market share. In short, [Peloton](https://www.onepeloton.com/) is a "spin style" bike that most everyone is familiar with from the gym, but with nice sensors to measure your cadence (rpms), "speed" (let's put that into quotes), power (watts), and the main selling point, a _big ol' screen_. It's with this screen that you virtually attend classes that are put on by those blessed by the genetic lottery, sometimes live and sometimes recorded.

{{< img peloton >}}

The name comes from the French term used in professional cycling, loosely meaning "platoon", referring to the mass of riders drafting each other during a race.

Despite how it may sound, I'm on board with the concept of Peloton. I actually chatted with them at length about their Python code base back at PyCon in 2018 in Cleveland, and I've seen a lot of coworkers of mine suddenly take an interest in riding it for fun and for exercise. 

It's a subscription based model (I think $40 a month) and while it has its purpose, it's NOT Zwift.

## It's NOT Spin Class at the Gym, Either
Perhaps this was implied by my previous point, but while Spin classes are great at the gym, they're not the same thing as Zwift. I guess a gym also has a subscription model, too, huh?

My point in mentioning this separately is that the spin style bikes typically have a flywheel that it uses for resistance. By its very construction, there's a lot more inertia saved in these things, which is why when you spin really fast on them, you'll often feel it pushing your legs around even after you've stopped applying force to the pedals.

## So what IS Zwift?
So back to "gamification", a term that marketing has been obsessed with off and on for a few years. Let's apply the element of gameplay to working out. Imagine riding your bike in real life, but inside your house, and while _pretending_ to ride in a virtual world with a lot of cool stuff to look at!

{{< img watopia >}}

### Getting Started
So to get started with Zwift, you first need some hardware.

* Your bike
* A "trainer", as it's called
* Some kind of video device, your phone or table will do
* A Zwift membership (or get on board with a 7 day trial)
* Oh, and likely a big fan(s) and a lot of water

I tend to leave one of my bikes in the trainer nearly 100% of the time, only to take it out when I need to move something in the room or maybe swap it out so my girlfriend can use my equipment for indoor riding.

{{< img my_zwift_setup >}}

#### What's a "trainer"?
Basically it's the thing you put your own bike into that gives back some level of resistance. There are a few types of these things, and it's important to know the differences before you attempt to go purchasing one of them.

##### Direct Drive
What I own, specifically the Cyclops Hammer. This uses a separate cassette gears in the back that you directly place your chain into as if you were putting your bike wheel back on.

{{< img directdrive >}}

You'll want to get a separate cassette for this (no reason to take it on and off from your wheel), so you'll want to make sure to get the same gearing / ratios as what you use on your bike wheel, otherwise you're gonna have a bad time.

{{< img badtime >}}

The main drawbacks to these are that they are very expensive. Some of these cost as much as people spend on their bikes! But good news, they're not as expensive as a Peloton!

##### Mag / Fluid Drive
It's basically a rotating mass that your back tire presses against and uses sheer friction to drive. This means that you're going to be chewing through tires like it's nobody's business. There are special, often red in color, trainer tires that you can use. I'm a fan of [Vittoria](https://www.amazon.com/Vittoria-Zaffiro-Home-Trainer-Fold/dp/B007IEHWDO) tires in general.

{{< img fluidtrainer >}}

While I don't own one of these, i've used them every so often when getting my bike fitted or fixed somewhere. Due to the sheer friction and weight along a big to small wheel transition. the pedal rotation as you experience it from the pedals is going to feel very weird at first. It's going to feel kind of "bumpy" in a way, at least until you get up to speed.

##### Rollers
You either love these or hate them. I used to have a set, but they scare me to this day! Basically you rest your bike on small rotating tubes that line up with your wheels and you get on the bike and spin on them, allowing the bike to freely move, in place, side to side. It's a fantastic way to develop core muscles, balance, with the side benefit of spectacularly falling in your own living room.

{{< img terror >}}

##### "Smart" Trainers, Generally
An important distinction to make here, too, is that nearly all trainers these days are "smart" trainers, in that they connect via Bluetooth. There are others who do not, but to truly use Zwift as it was intended, you're going to want the added sensors (particularly power in watts) and wireless connectivity that a smart trainer will do for you.

### What All This Gets You
When paired with a smart trainer, the real beauty of Zwift that separates it from simply just watching a video on YouTube while riding a bike inside, is the _feedback_. When you see a hill in the game or virtual world, your trainer makes riding more difficult. When you go down the other side, your trainer makes it easier.

{{< img supertuck >}}

Simple concept, but considerably more engaging!

#### This also means better training
Since there's feedback, combined with smart power resistance, the real thing that has caused Zwift's monumental ride to fame has been its ability to provide very specific and awesome training regimens. You can do FTP (Functional Threshold Power) tests, do some "sweet spot" training, intervals, you name it. You can even create your own workouts if you'd like.

#### Integration with Other Apps
Zwift can even be connected up to other applications for very specific and dialed-on training regimen, think [TrainerRoad](https://www.trainerroad.com/) or [The Sufferfest](https://thesufferfest.com/). These applications offer very pointed and directed training workouts and workout plans that are backed by professionals of the sport, and Zwift can be the mechanism that you use to specifically _do_ them.

Even GCN (The Global Cycling Network) on [YouTube](https://www.youtube.com/user/globalcyclingnetwork) has done videos about how these programs, specifically The Sufferfest, [with their presenters](https://thesufferfest.com/blogs/training-resources/do-the-plan-with-dan-from-zero-to-hero-in-10-weeks). 

#### Full disclosure
While I absolutely am on board with these integrations and fully encourage others to do the same, they are not something to which I currently subscribe to. I like to ride hard when I feel up to it, but am often a bit torn between the simple enjoyment of riding your bike and using it as a tool to increase my physical fitness and performance.

{{< img dog >}}

### Racing and Events
Several months back, Zwift actually introduced a new feature - _racing_. How does one race in a virtual setting, you may ask? Well, much like Puff Daddy said in the 90's, "it's all about the watts per kilo".

#### Watts, Watts, Watts
A _watt_ is a measure of power. It can be applied to nearly anything, generally, and is something a lot of us learn about in high school Physics and then quickly forget about. It's basically a measure of force over a period of time. And since YOU are the engine when riding a bike, _power_ is a measure of how strong of a rider you are.

{{< img trex >}}

However, it's not all about the power number alone. Real world conditions definitely make for a fuzzy final picture. So what generally works well for people in this sport is a measurement referred to as "watts per kilogram", or w/kg for short.

#### Little Riders vs Big Riders
Imagine you're on your bike. You weigh maybe 180 or even 200 pounds (which for those of us not in America, 81 to 90 kg). Going up that steep hill means that you have to not only overcome the friction from the road and drag your bike along with your own body weight, but now you also have to overcome that pesky thing called gravity. How hard you have to push those pedals is going to translate into some quantifiable number in watts.

Imagine you're a considerably smaller rider, now, going up that same hill. There's a lot less weight that you have to carry up that hill, so you basically don't have to push _as hard_, at least in absolute, numerical wattage.

{{< img wkgdiff >}}

What we then use to essentially equalize both of these situations is your body weight. Besides, a bigger person is carrying a larger amount of weight with them at all times, anyway, so it's a bit of a normalizing function. Thus, _watts per kilo_. 

#### Bringing it back
Zwift uses this w/kg measurement to more properly normalize riders against each other in events. It helps level the playing field a bit in the virtual world. **So don't cheat**. 

{{< img yeahright >}}

The person in spot number 10 on this screen shot is clearly 1) not accurately representing their weight in the Zwift app, and 2) in the wrong race (topic for another discussion). If you look at their numbers, their weight listed in Zwift is 36kg (just under 80 pounds)! Not only is 7.0 w/kg a level that only professional cyclists can realistically attain, but it's also not very realistic for someone to be cycling at that level at 80 pounds!

This is sometimes referred to as "weight doping", and it gives people unfair advantages in the system. To be honest, it's just dumb, as this should be a workout!

#### Zwift Companion App
The screenshot above is actually from the Zwift Companion app, which is great. It can show you events coming up, you can sign up for those events, get reminders for them, and then see all of your statistics while riding on your main screen and app combo in a more focused way. I've found that doing workouts with this app is wonderful, as it helps you narrow in on what interval you have coming up or what kind of wattage you may be doing next as part of your training plan that day.

Definitely recommended. No cost needed!

## Final Thoughts (for now)
This post is definitely a lot longer than I had planned for it to be!

As the world shut down in March 2020 for COVID, a lot of people suddenly took to using Zwift to ride their bikes as a break to their daily lives that were (and frankly, still are) full of madness. The wonderful thing here is that the company has actually scaled quite well to meet the demand. I haven't really heard of any problematic issues generally of services like races or events being taken offline or unreachable, and overall game performance has been largely the same. In fact, MORE events have been set up to help encourage all of us to ride our bikes more through these odd times.

So to loosely quote Charles Dickens, it definitely feels like the worse of times and the best of times, and Zwift, I feel, is a great example of what wonderful options we have these days for riding our bikes!
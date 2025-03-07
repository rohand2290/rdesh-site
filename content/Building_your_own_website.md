+++
date = '2025-03-07T12:47:27-08:00'
draft = false
title = 'Building your own website'
+++

## Why?
Remember when Tiktok shut down and millions of people thought they were about to lose their livelihoods because of the app? 
Easily could have been prevented if they built services that didn't rely on a centralized platform.

In general though, we live largely on the internet as serfs or tenants on a company's social media platform.
While I'm not such a zealot as to delete my accounts from them (mainly because everyone uses them,) I do think a lot of problems would be solved if people had their own websites. 
Not just websites, but personal services as well, like a git server. No more DMCA takedown requests (although those could still happen, but probably with less chances.)

Right now, I have this website, a self hosted [cgit](https://git.rdesh.xyz) instance, and a calibre instance for my own personal library.
I know that a corporation won't be going after me if I post something they don't like on their platform. I do want to create like a little small community that'll actually check this however.

### Artistic Freedom
Another small thing here to note is the artistic freedom you get while managing your own blog or personal website.
Here, I can easily change the appearance or CSS of my website, and add as much instances of other self-hosted services to my VPS, provided I don't go past the 2gb of RAM limit.
I can't really do that on any other platform; I'm at the mercy to what they allow me to do. 

That being said, later on I might add on a Mastodon instance to connect with other communities.
I haven't researched much into the Fediverse, but it does sound like a cool concept that I wish more people would take seriously instead of having accounts on large social media websites controlled by billionaires.

### Algorithms
Using big social media websites such as Instagram and TikTok put you at the mercy of their algorithm.
This can easily put you down a big rabbit hole of content that can change your way of thinking for the worse.
I'll write an article later on how you can change your mindsets and beliefs and the way you should do them that won't get you down a rabbit hole, but for now just know the the algorithms that the big social media websites use are probably the number-one thing dividing our population at the moment.

## How?
Firstly, there are a few things to keep in consideration:
1. Privacy. Not as much of a concern for me as it is for some other people, but it is something to be wary of.
I don't end up really doing anything nefarious, I just want the freedom to write and have my own opinions on a platform I like to use. 
If you really do care about this, make sure to not use any services that are in a [Five Eyes](https://en.wikipedia.org/wiki/Five_Eyes) country.
2. Ease of use. It would be a good idea to be knowledgeable on how to use a Linux distribution on the server, such as Debian or Ubuntu. Otherwise it's going to be a pain to host your services.

That being said, you'll want 2 things: a VPS provider, and a domain name.

### VPS provider
I use [RackNerd](https://racknerdtracker.com/). 
They offer super cheap VPS's, sometimes for only a few dollars a month. 
I pay 18 bucks yearly for mine, and it has about 2GB of RAM and 40GB of storage, which is more than fine for my own needs. 
Don't go on their main website: the page I linked to has deals which are extremely good. 
If you want to splurge, you could even go for something that's 50 bucks a year and you'll get 4GB of ram and 105GB of SSD storage.
Not too bad considering most other VPS providers are 12 bucks a MONTH. 

### Domain registrar
I use [Namecheap](https://www.namecheap.com/), but there are plenty of other options here. 
All will work fine. 
Most domains go for about a dollar a month; Namecheap does have deals where you'll end up paying 2-4 bucks your first year, and then 12 bucks your 2nd. Still pretty affordable for most people. 

### Setup
Maybe I'll write a blog post in the future on how I set up my own website, but for most people the [LandChad](https://landchad.net/) guide by primarily Luke Smith will work just fine.
There are a few gripes I have with it though, but if you're a beginner his advice will work. 
He gives tutorials on how to set up HTTPS so people won't be scared trying to visit your website, as well as other tips and tricks. 
The Hugo [theme](https://github.com/LukeSmithxyz/lugo) I use is also made by him, with my own modifications to the color scheme.

### Raw HTML/CSS vs SSG
I would recommend using an SSG (static site generator) like [Hugo](https://gohugo.io/) for building your main page.
There are many themes available for it, and your pages will still be fairly minimalist, work well with mobile devices, and not have unecessary Javascript bloat like React or some framework that'll cause a 300mb download. 

Bloat's definitely a joke to an extent, but the truth is frameworks like React are useful for only building interactive web apps, not static web pages. 
Some of my projects use React but that's when I have to get data from a user - otherwise just HTML and CSS is fine.

### Host your own services
From here, you can end up hosting your own services that you need.
For example, I have my cgit instance for my git repos, though I might switch to Gitea later just for ease of use.
I also have a Calibre instance for books.
In general, it would be a good idea to host as many things as you need to be somewhat independent on the internet within reason - for example, I could set up an email server but using my student one <rbdeshpande@ucla.edu> probably adds more credibility to me.


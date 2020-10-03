# Simple Podcast Landing

I've been hosting my podcast for more than 5 years now and I always struggle setting a website I really feel is helping promoting and converting visitors into listeners. I still don´t kow if this is it but I think it is a very good restart.

## What was I looking for?

First of all I wanted to get rid of all the administration duties a CMS demands. Also I wanted to reduce hosting costs (app and data servers). But the most important thing is I wanted to give people an easy way to find, listen and subscribe to my podcast. A few months ago I started doing things i visual studio code and Azure and I realized it can be the way to go. So summarizing this are my goals for this design.

1. Users will easily find my podcast on Spotify, apple podcasts or google podcasts. And hopefully subscribe once they are there. 
2. Usars will be able to listen to my most recent episode directly in my website
3. Users will be able to watch my live episodes
4. Users will be able to listen to past and featured episodes

## Some considerations on the design

My first website was a wordpress template I bought a couple years ago that has some plugins that consume my podcast feed and from there it shows the episodes. However I had to do a lot of things to keep it up to date. So after I produce an episode, which is also a time consuming work, I had to manually update the plugin, set the episode cover which for some reason the plugin never retrieve and wait for the cache to be updated. I didn´t want that anymore.

I also wanted it to look good on any screen without having too much to do and have the ability to update it as I wish quick. Having an HTML snippet I copy and paste and an embed code for my podcast copy pasted have to be enough.

So I came up with the idea of basing the expeience on Cards, a more or less common concept. and I thought cards will be good for posting each episode directly from spotify or anchor embeded. (Sorry apple, you don´t have easy to find ways of embedding episodes).

Cards are created based on Boostsrap and I only change the embed code I can copy from my podcast distributors. Then I realized I could tweak card design by changing colors to show info, donation, episode, feature episode cards and so on, how clever of me. I played a bit with bootstrap to make the cards flow and stack accordingly to the screen size. That needs polishing. 

Anyway you can use the code and customize it for your own purposes and likes and even deploy directly from github to your preferred hosting. Since this is a static design, I use Azure static websites which is cheaper than a wordpress instance.

![Desktop screen](https://github.com/rickersilva/SimplePodcastLanding/blob/master/img/desktopscreen.png?raw=true) ![Desktop screen](https://github.com/rickersilva/SimplePodcastLanding/blob/master/img/mobile%20screen.png?raw=true)

## Anything else?

If you need anything else, just write me or contact me here.

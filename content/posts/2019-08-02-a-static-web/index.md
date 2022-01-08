---
author: Keith Lindsey
date: "2019-08-02T22:41:00Z"
title: A Static Web
tags:
- Markdown
- Jekyll
Params:
  ShowReadingTime: true
---

Every time I reboot this website I inevitably make the first post the equivalent of "I am now going to tell you about my website," and this one won't be any different. However, I will try to tell a story this time.

Websites and I have had a long and complicated relationship. Not only are they things I spin up with good intentions and neglect, but they remind me of the difficult time I had starting out.

It was the summer of 2005. I had graduated high school and had been working part time in a warehouse picking orders for a wholesale distributor. The person who at the time created marketing materials and managed their website was quitting so she could be a stay at home mom. Management knew I was familiar with computers so as a temporary fix they asked if I wanted to give it a shot. I figured it would be a good opportunity, and it got me out of the warehouse during the hottest Texas months.

| ![Nelson Wholesale circa 2005](/images/2019/08/nelsonwholesale-2005.png) |
| :--------------------------------------------------------------: |
|     _Wayback Machine's copy of Nelson Wholesale around 2005_     |

I didn't get much training beyond these are the programs I use, here is a list of passwords, and good luck. The website at the time was a digital catalog, but the stores who would use it typically didn't have internet. This meant that part of my job was regularly copying the website to CDs, printing labels and mailing them out.

| ![Nelson Wholesale circa 2007](/images/2019/08/nelsonwholesale-2007.png) |
| :--------------------------------------------------------------: |
|     _Wayback Machine's copy of Nelson Wholesale around 2007_     |

I more or less continued this, adding and removing products, restructuring, trying to make a static site consistent across pages and generally fighting HTML and CSS in Dreamweaver. After a few years of working summers and part time while I was in college I started trying to find a better way. We tried a local guy who turned me on to Joomla, and although it didn't work out with him I had some kind of answer.

| ![Nelson Wholesale circa 2013](/images/2019/08/nelsonwholesale-2013.png) |
| :--------------------------------------------------------------: |
|     _Wayback Machine's copy of Nelson Wholesale around 2013_     |

By the time I graduated college in 2008 I transitioned the site to [Joomla][joomla], a CMS with modules that could be installed for extended functionality. This new solution made many things easier, but it made it far more difficult to send an offline copy out. Thankfully by this time most stores had upgraded from no internet to dialup. I ended up spending a lot of time searching for ways to compress this, trim that, and generally try to speed up page load times.

| ![Nelson Wholesale circa 2015](/images/2019/08/nelsonwholesale-2015.jpg) |
| :--------------------------------------------------------------: |
|                        _Mockup from 2014_                        |

After I graduated I transitioned to full time and started creating marketing materials: brochures, fliers, business cards, and product design. The website probably peaked around 2011, and I was told that it was good the way it was. More and more I grew to resent the website and avoided maintenance. I eventually moved on from the website and marketing into a system administrator role where I assisted with an ERP change. I did one last redesign in 2014 before I handed the website off to another.

All the while social media is happening. I signed up first for MySpace in 2004, then Facebook in 2006, Twitter in 2008, Google+ in 2011, and Instagram in 2012. I closed my account for all of them at least once. In high school, when I was louder and more annoying, I complained on MySpace about the quality of material that gets passed around. This was met with a mix of "yeah, you're right" and "chill out, it doesn't really matter." It didn't matter. This was normal.

{{< youtube dINgx0y4GqM >}}

It wasn't until later in 2014 I watched [Indie Game: The Movie][indie-game-movie]. In it [Edmund][edmund-mcmillen], one of the creators of Super Meat Boy, explained that a big draw of making video games is his need to connect with people, but also wanting to avoid those people because he probably wouldn't like them. It was an ah-ha moment for me. He said exactly what had bothered me about social media. The solution for now seems to be a blog. I can feel like I'm sharing, but without all that comes with social media.

After I let my hosting lapse, got the itch, and setup hosting. I went with Wordpress because it was easy to deploy and easy to use. After a few months I wanted to do something different, and my interest had been piqued about this Jekyll thing. [Jekyll][jekyll] is a ruby solution that takes [markdown][markdown] files and creates statics pages, but allows for theming and customization.

For now I'll be writing in [iA Writer][iawriter], saving to Dropbox and running Jekyll to create the static pages to FTP to the web server.

[joomla]: https://en.wikipedia.org/wiki/Joomla
[jekyll]: https://jekyllrb.com
[edmund-mcmillen]: https://en.wikipedia.org/wiki/Edmund_McMillen
[indie-game-movie]: https://en.wikipedia.org/wiki/Indie_Game:_The_Movie
[markdown]: https://www.markdownguide.org
[iawriter]: https://ia.net/writer

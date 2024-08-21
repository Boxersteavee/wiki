---
layout: default
title: Main Website
nav_exclude: false
has_children: false
parent: Projects
search_exclude: false
last_modified_date: 2024-08-21
---
# My Website
{: .no_toc}
I have a [website](https://boxersteavee.dev) that I built using an [Astro](https://astro.build). This article explains the story of how it changed over time, and how it became what it is today.
{% include toc.md %}
## Where it began.
I bought the domain `boxersteavee.dev` in the beginning of September 2021, and at first, I didn't
really know what to do with my domain, and left it hanging for a while. A couple months later, I
setup a google site. which lasted about a year or so whilst I kept going with school. and other
things in life. I also played around with [Ghost](https://ghost.org) for a bit, but I didn't really do much with it.
## The astro-nomical discovery.
(excuse the pun)
Around December 2022, [a friend named alfie](https://itsmealfie0.com) told me about Astro. I gave it a bit of a tinker about, setup a basic site using the default template and gave it a test. I found it cool, but didn't really know what else to do with it. This all changed when that same friend told me about Astro Templates. I had a look, and picked the same one he did, a portfolio site. I customised it, and over time, made it what my site looks like now (as of August 2024). 
## Where to run?
Initially, I just ran a Google Site, which Google hosts. When I setup Ghost, I "ran" (more like light jogged) it on an old Raspberry Pi 2B. That Pi was the start of my HomeLab journey, but you can read about that (when I make that article). When I learned about Astro, I initially tried to do the same, but it wasn't exactly great. 

Alfie then told me about Oracle Cloud, and after setting up a free tier account, he guided me through setting up [CapRover](https://caprover.com) and hosting my Astro Site on there. This is where my Website ran for quite a while, as it worked, was fairly stable, and didn't have many problems.

I later discovered Cloudflare Pages, and how easy it was compared to what I had for Caprover, and it has a very good uptime. Moving over was as simple as linking my GitHub account and Cloudflare Accounts, setting up a deployment and clicking "Deploy". My site now runs on Cloudflare and has an uptime on-par with most websites. It pretty much only goes down when I do something stupid, or when [Cloudflare has an outage](https://blog.cloudflare.com/post-mortem-on-cloudflare-control-plane-and-analytics-outage/), which is fairly rare, and usually affects a very large percentage of the internet.
## Conclusion
Overall, I'm very happy with my website, and I am happy with how it's being hosted. At some point I would like to change Astro Templates, basically giving it a complete re-design, but that would take a lot of time and effort to move all of the pages over as a lot of the content is very dependant on individual components of the template.
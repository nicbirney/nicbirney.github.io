---
title: Journal Entry
date: 2023-09-11
categories: journal technology
tags: web-hosting zola jekyll small-web static-sites
---

Hi! I am embarking on the journey of actually keeping up with a blog. I've decided to try to use an [SSG](https://www.cloudflare.com/learning/performance/static-site-generator/) to try and create a [small web](https://benhoyt.com/writings/the-small-web-is-beautiful/) blog, that has minimal javascript and is easy to load. In fact, because nobody else is reading any of this, I currently am able to host on my own raspberry pi. If more people ever started reading this, I'd probably have to switch that around and host somewhere else.

I decided to use [Zola](https://www.getzola.org/documentation/content/page/) as my SSG. Mainly, this is because it was the easiest to get going on my Raspberry Pi. The really popular one, [Jekyll](https://indieweb.org/Jekyll), looks really great for this specific purpose. Unfortunately, I really had a helluva time getting it to play nice on my Raspberry Pi, due to some dependency issues. I suspect this is because Raspbian is a bit out of date. While a secondary goal of this blog is to showcase my technical skills, I don't want that to override my goal of actually adding content to a blog. So I opted for Zola, since it is dependency-free and as a bonus, is coded in my current favorite systems language, Rust. 

Some pain points I have already  noticed:  
1. Because the site is statically generated, it's not going to just immediately update when I post something. I'm going to have to rebuild the site when I make a new post. For the purposes of a blog with just one author, that is trivial. If it were a bigger enterprise, I'd have to figure out some way to rebuild often enough to keep posts fresh, without too often, since rebuilding is going to be the most expensive part of using an SSG. In that case, though, maybe an SSG just wouldn't be the right tool for the job.
2. There is still a bit more complexity than I expected. The learning curve is kind of steep, compared to my expectations. I guess I thought "small" = "simple." I think that might be more of a "me" problem, and less of a Zola/SSG problem. Specifically, figuring out how to work with the themes, since each theme has pretty different requirements.

Speaking of themes, I'm currently using the [Hook](https://www.getzola.org/themes/hook/) theme. I really like it. The goal is to make this whole thing more "mine" by creating my own theme, but for now this is really nice. My one complaint about this theme is that it doesn't seem to have any functionality for taxonomies. That probably helps keep complexity down, and keep the site small, but I would like to be able to categorize this post, for example, as a "journal" post, so that if you're here for my stories, you could just find "fiction" posts.

Anywho, I'm having a grand old time exploring all this stuff. Thanks for reading!

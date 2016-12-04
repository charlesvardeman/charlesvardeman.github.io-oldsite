---
layout: post
comments: false
title: Selecting a bloging platform
categories: Blogging Platform
---

The first couple of posts of this blog will be about the mechanics of setting up a blog and how to select a platform that has some "semantics" built in to make content machine discoverable.

There is quite a bit of material available online about selecting a blogging platform. I chose [Github Pages](https://pages.github.com/) and the static content generating framework [Jekyll](https://jekyllrb.com/) as a starting point. This lets me track changes and publish content on a platform, github, that I'm already familiar with and use for code tracking already. Jekyll is an extensible platform that has a sustainable community already behind it that can be leveraged if needed. There is a rich ecosystem of plugins and extensions available for providing a rich experience. [Smashing Magazine](https://www.smashingmagazine.com/) has nice [summary](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/) of the features that make Jekyll an attractive bloging platform.

The last major requirement was that I wanted something in a style similar to [Medium](https://medium.com/), which I find very readable in terms of fonts and a simple layout. I also wanted something that is responsive on a variety of platforms and browsers, particularily mobile platforms. Google has started the [Accelerated Mobile Pages](https://www.ampproject.org/) effort to produce a platform for content that is responsive on mobile devices. A [template](https://github.com/ageitgey/amplify) based on Jekyll was created by [Adam Geitgey](https://github.com/ageitgey) that I forked in github to become the beginning of my blogging framework. That framework will evolve as I extend the existing JSON-LD support Adam built into the templates to have some more extensive coverage of [Schema.org](http://schema.org/) and other vocabularies.

In the mean time, here is Google's pitch for getting started with AMP.
<amp-youtube data-videoid="lBTCB7yLs8Y" layout="responsive" width="480" height="270"></amp-youtube>

And a series of nice introduction to JSON-LD by Manu Sporny, one of the developers of the JSON extension for representing Linked Data.

<amp-youtube data-videoid="vioCbTo3C-4" layout="responsive" width="480" height="270"></amp-youtube>

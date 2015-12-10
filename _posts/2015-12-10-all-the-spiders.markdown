---
layout: post
title:  "All the spiders"
date:   2015-12-09 01:03:44
categories: side-project machine-learning
---
I started working on the various parts of this side project. It would had been easier doing services/consumers via php.
But doing so in python is altogether a different challenge. Currently I'm using scrapy to create an on-demand spider, that could be
run whenever the user logs in his app. It would then update the db upon finish. I just have to say, writing a good reusable code
for an all around spider is actually a rather painful effort, probably given the fact that my internet connection is uber slow,
and the xpath structure of my sources are highly inconsistent. Thus rather than working directly with the files served,
I segmented the spider to pipeline the tasks into different stages of data preparation. 
Given the latency, I decided to store the test pages to local, and test it from there
to make for faster debugging. Everything seems all in well. But no, after a few hours of working on it,
I tested it on live, and after twenty or thirty content pages in, the dom tree suddenly changes, into an alternating nested
series of placeholders, resulting in lots of missing content. Using xpath is nice, but in dynamically changing layouts,
it seems that css selectors are more convenient. Anyway, I'm sort of rambling on here.
It would have been great if I had a faster connection, and knew about this beforehand, so I dont have to refactor 
a sh*tload of things. sigh.
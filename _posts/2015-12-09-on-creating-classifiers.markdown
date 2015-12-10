---
layout: post
title:  "Creating classifiers for jurisprudence"
date:   2015-12-09 01:03:44
categories: side-project machine-learning
---
A year ago, I've made a data miner / scraper for philippine jurisprudence. My initial plan for this was to create an API that would allow
any user to query any given tag, or term, like 'criminal law' or 'lukban v. villavicencio', mostly because I was interested in exploring
flask, implementing API standards and using elasticsearch library for nodejs. Useful as a jurisprudence API, may seem to be,
it seems hardly practical as there are already ebooks and pages online that has digested such cases.
So I'm thinking of using this project instead to apply some of the things I'll be studying, with regards to data science, and
machine learning.  I'm actually excited to embark on this project, as I had been discovering many interesting implementations
and applications along the way (hadoop ;-)).
I was thinking of crawling precedence histories, and quantifying factors that may cause different outcomes in related cases.
I could use bayesian classification by then, to predict the likelihood that the court will rule given a bunch of data.
Highly ambitious, but yeah, this is just for fun.
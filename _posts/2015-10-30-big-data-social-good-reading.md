---
layout: post
title: A Gentle Technical Reading List for Big Data for Social Good
date: 2015-10-30 12:52:21.000000000 -07:00
type: post
published: true
status: publish
categories:
- Conferences
- Research
tags:
- bdsg
- dssi
- NSBE
meta:
  bitly_url: http://2smb.link/1Hh0O75
  bitly_hash: 1Hh0O75
  bitly_long_url: http://www.sarahmbrown.org/big-data-social-good-reading/
  _edit_last: '1'
  _wpas_mess: A Reading List for Big Data for Social Good
  _wpas_done_all: '1'
  _publicize_twitter_user: "@BrownSarahM"
  _jetpack_dont_email_post_to_subs: '1'
  _snap_forceSURL: '2'
  snap_MYURL: ''
  snapEdIT: '1'
  snapLI: 's:210:"a:1:{i:0;a:7:{s:2:"do";s:1:"1";s:9:"msgFormat";s:38:"I published
    a new blog post: (%TITLE%)";s:8:"postType";s:1:"A";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";}}";'
  snapTW: s:199:"a:1:{i:0;a:7:{s:2:"do";s:1:"1";s:9:"msgFormat";s:27:"New post (%TITLE%)  -
    %URL%";s:8:"attchImg";s:1:"1";s:9:"isAutoImg";s:1:"A";s:8:"imgToUse";s:0:"";s:9:"isAutoURL";s:1:"A";s:8:"urlToUse";s:0:"";}}";
  _yoast_wpseo_primary_category: ''
  _yoast_wpseo_content_score: '30'
author:
  login: smb@sarahmbrown.org
  email: smb@sarahmbrown.org
  display_name: Sarah Brown
  first_name: Sarah
  last_name: Brown
excerpt: Here I provide a list of some of my favorite (mostly) accessible machine
  learning papers that I think are good reading material for someone broadly interested
  in machine learning for social good but is not an expert in machine learning yet.  These
  will help you begin to get some perspective on the relevant technical matters and
  research questions without being bogged down by details.
---
As a machine learning researcher, __Big Data for Social Good__ is my take on this year's NSBE conference theme of __Engineering a Cultural Change__.  Today, I'm presenting a workshop at the NSBE Region 1 Fall Regional Conference on that topic, but there's so much to share, this is mostly intended as additional information for the attendees, but I think this could be useful more broadly.  My research, isn't exactly on Big Data for Social Good, but I do applied machine learning research and I think there's some important commonalities.  I begin from a real problem and design smart algorithms to help domain experts make sense of their data- this is exactly what a Data Scientist working at or with a nonprofit would do.  In my graduate work my collaborators have been psychologists who want to ask categorically different questions- questions so novel that traditional experimental designs and analysis techniques don't get the job done. Since I've spent so much of my time outside of the classroom and lab dedicated to social impact through NSBE so Big Data for Social Good is a personal interest and possible future direction for me.

Machine learning and big data appear all over lately but there are a number of key resources that I think anyone interested in data driven methods for decision making, even if outside of the technical realm should consider and support making sense of. These are, however, challenging problems . There is additional research that must be done toward this end. Here I provide a list of some of my favorite (mostly) accessible machine learning papers that I think are good reading material for someone broadly interested in machine learning for social good but is not an expert in machine learning yet.  These will help you begin to get some perspective on the relevant technical matters and research questions without being bogged down by details.

### [Model Based Machine Learning](http://research.microsoft.com/en-us/um/people/cmbishop/downloads/Bishop-MBML-2012.pdf)
In this paper he develops the storyline of what model based- as opposed to feature engineering based- machine learning looks like. Along the way, he describes the basics of probabilistic graphical models- a language for expressing statistical models - and concludes with a new type of programming language designed specifically for machine learning. This paper is helpful not only because that easy to read tutorial provides knowledge that will make reading many other papers easier, but because models are a widely understood idea- many other researchers use models of some form. For me, that makes model based machine learning especially important when working with data from any application domain, especially one where decision makers may not be as strong in math and computer science. There's also a [forthcoming book](http://www.mbmlbook.com/) on the topic.

###  [Big Data, Machine Learning, and the Social Sciences: Fairness, Accountability, and Transparency](https://medium.com/@hannawallach/big-data-machine-learning-and-the-social-sciences-927a8e20460d#.svhzu617z)

There have been a series of workshops lately on fairness, accountability, transparency in ML. This medium post by Hanna Wallach -she's also a founder of [WiML](http://wimlworkshop.org/) and pretty awesome in general- summarizes a talk she gave at the first FATML workshop.  She focuses on data, questions, models, and findings to highlight the state of the field and some of the key challenges in computational social science with respect to fairness accountability and transparency.  She begins with a few different definitions of big data- what makes the current trend in big data different from large and a pretty clear overview of some of the challenges facing machine learning if applied to social science problems.

### [Machine learning: Trends, perspectives, and prospects](http://www.cs.cmu.edu/~tom/pubs/Science-ML-2015.pdf)

This clearly written survey name-drops just about every sub area in machine learning and paints a pretty clear picture about how the areas relate or compare. This article will serve as a great launching point if you think you might be interested in machine learning but want to This concludes by highlighting some of the core challenges facing machine learning going forward.

### [Machine Learning that Matters](http://icml.cc/2012/papers/298.pdf" target="_blank)

This paper reads more as a position paper, it's again, not technical but this essentially argues that too many machine learning papers and journals focus on the incremental discovery of machine learning techniques without actually attending to the data on which the methods are applied. It highlights a systematic problem in machine learning: reusing the same data sets repeatedly for tasks that may or may not have actually been of interest to those who generated the dataset. Arbitrary measures of performance declare the author's proposed new method better than another, but don't declare clearly why.  There was also a follow up special issue of [Machine Learning Journal on Machine Learning for Science and Society](http://link.springer.com/article/10.1007%2Fs10994-013-5425-9).

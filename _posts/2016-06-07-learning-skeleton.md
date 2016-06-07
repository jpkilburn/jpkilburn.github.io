---
layout: post
title: "Learning Skeleton"
date: 2016-06-07
excerpt_separator: <!--more-->
image: "https://cdn.tutsplus.com/webdesign/uploads/2013/10/skeleton-retina.png"
---

Jumping straight into some (slightly) new material, I've decided to start doing some learning and development with <a href="http://getskeleton.com/">Skeleton</a>. Skeleton is a lightweight CSS boilerplate for producing responsive designs. It doesn't come with all of the additional features you'll find in Bootstrap and some other frameworks, instead allowing the developer to add in what their site needs. It reduces bloat and is a strong fit for small scale sites, or ones that are primarily delivering static content.<!--more-->

Up until this point I've generally turned to Bootstrap for all of my responsive needs. I was first introduced to frameworks with Bootstrap and it's a standard tool to use, so it's not really something I've paid a second thought to. However, after looking through some negative sentiments of it on Reddit, I decided to do some reading of my own. What I found wasn't entirely against Bootstrap; like many technologies, there are alternatives and there are certain times when those alternatives may be a better option. I did find an <a href="http://www.zingdesign.com/5-reasons-not-to-use-twitter-bootstrap/">article by Zing Design</a> that I read through and found some valid points on, though.


Generally speaking, most of the functionality I use out of Bootstrap are for responsive layouts and the embeds. While I take advantage of the templated navbars and other functionality, those aren't the main reason I use Bootstrap. All of the additional classes and JavaScript functionality is somewhat wasted as a result; and while it may not be perceivable to me when browsing from my high speed connection, excess like this does lead to some noticeable bloat on other devices and connections.


Enough about Bootstrap; On to Skeleton. Skeleton is a lightweight boilerplate consisting of two files and only roughly 400 lines of code in the primary CSS file. It mainly deals with responsive formatting for columns, though it does include some minimal stylings such as default buttons and an imported Google font (which seemed to cause some loading issues, so I've removed it from my test project). Though it lacks classes for images and videos, I was easily able to write in some CSS for a responsive image class and a wrapper for Youtube iFrames, and now my test site has a fully responsive design, with much less code!


There's obviously some extra work involved in using Skeleton, but it's definitely not a bad thing to have some experience writing your own responsive CSS. I'm going to continue working with the current page I have running on my local files, and when it's finished I plan to upload it onto this site, possibly as the foundation for my CSS Garden. In the future I may even look into converting this current layout into one running on Skeleton. While I definitely wouldn't say I've abandoned Bootstrap (it has a ton of wonderful functionality, and on some sites it's certainly going to be more highly utilized), I feel that this site likely doesn't make use of it enough to justify using it over Skeleton. I'll likely resist the urge to get on that right away, and continue looking into some other tools first; I've only just completed this site, and it feels like it would be a bit of a waste to just continually iterate on it while I could be developing other skills.
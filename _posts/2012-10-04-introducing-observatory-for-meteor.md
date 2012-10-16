---
layout: post
title: "Introducing Observatory for Meteor"
description: ""
category: observatory
tags: [meteor, observatory, logging, javascript]
---
{% include JB/setup %}

![Observatory screenshot](/img/observatory-scr-s.png)
We started our next project using [Meteor](http://meteor.com) and very quickly ran into issues with logging. Meteor is amazing,
if you are not familiar with it yet I highly recommend to [check it out](http://meteor.com) - you can do top-notch applications
running on the web with it in a fraction of a time and it's all pure javascript (or [coffeescript](http://coffeescript.org) 
for that matter) on both front and backend. However, it's still a preview version at the time of this writing (0.4.2) and as such
lacks all the bells and whistles of a mature framework. One of that was logging, we needed it to debug our meteor applications
and in a couple of evenings we have created [Observatory](http://observatory.meteor.com) which has subsequently somewhat outgrown
the initial idea and turned into logging & monitoring package for Meteor.

What it does is gives you nicely formatted (and yes, it's even themable) logs (both client and server side!) right inside your 
meteor app and provides monitoring for some key meteor internals - templates, events, session object etc. Detailed documentation
is available on [Observatory website](http://observatory.meteor.com), but it's so easy and good looking (I know, I'm biased :) that
you don't want to miss it.

We have some crazy ideas on where to take this further and would love to hear what you think - so do leave a comment!

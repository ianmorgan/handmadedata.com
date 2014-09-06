---
layout: post
tags:   million_song_challange pig
disqus: true 
---

In an earlier post I mentioned [a Pig example](https://github.com/andrewclegg/pig-data-mining-talk) presented 
at the London Hadoop User Group.

I spent some time setting this up, but bar one missing library, its actually very easy. So, for Hadoop
and Pig virgins like myself

1.	**Easy**. You don't need to waste time installing Hadoop, Pig can run in a local mode with an
embedded Hadoop, and for this smallish dataset, that is sufficient. Just download the latest stable release (I used 0.10.0)
and follow the instructions. Its very simple, then check the notes on local mode. 

2.	**Slightly tedious**. To get the data used in the talk just register with Kaggle and follow the 
notes in the demo.

3.	**A pain**. The Pig Latin script requires some third party libs.
Missing is *piggybank.jar*,  basically a collection of utility classes for Pig. It's not mentioned in the notes as I assume most 
"proper" installs of Pig will already have it. Annoying this jar isn't part of the binary release and needs to 
be built from source.  I found a few compiled jars on the web, but all were too out of data to work.
When building from scratch the Ant scripts crashed (Ivy didn't find all the dependancies) 
 and eventually I resorted to some manual hacks to get a compiled jar. It's on the web at
[DropBox](https://www.dropbox.com/s/rpn1x2n6513d79y/piggybank.jar). Download and place in Pig's lib directory. I wouldn't 
trust it on a production server, but for this demo its fine.

This should be all you need to run the Pig Latin script in Andrew's demo.

_btw, I'm running on a 4GB MacBook Pro with Snow leopard and Java 6_











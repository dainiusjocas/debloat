---
layout: post
title: Technical software bloat
description: "Yet another aspect of bloat"
modified: 2014-03-12
category: articles
tags: bloat, Java
image:
  feature: so-simple-sample-image-1.jpg
  credit: Michael Rose
  creditlink: http://mademistakes.com
comments: true
share: true
---

There are many aspects of bloated software, e.g. big executable, complicated to use, etc. Among other there is I'd say technical bloat.

Technical bloat means that software is using more resources than necessary, that causes mostly performance and memory issues. 

Runtime bloat: software expends a prodigious effort to accomplish relatively simple bits of functionality.[^1]

Object-oriented programming, as a culture, encourages a certain kind of excess. Rather than paying attention to storage, the culture encourages us only to pay attention to our models[^1].

We define the memory bloat factor as (t − d)/t, where t is the total number of bytes consumed by live objects, and d is the number of bytes storing actual application data[^1]. Memory bloat is a problem of long-lived data.

Abstraction has a high performance price. Programmers trust the libraries and frameworks they reuse, and assume the code that reuses their own code will be a good citizen. In reality, programmers can’t intelligently make design choices and trade-offs without understanding the larger context. 

Because of object byte footprint overhead the Java cache suffers from a poor hit rate.[^1]


Excessive generation of temporary objects is termed “object churn” and is a form of software bloat that often leads to performance and memory problems.[^2]



[^1]: Mitchell, Nick, Edith Schonberg, and Gary Sevitsky. "Four trends leading to Java runtime bloat." Software, IEEE 27.1 (2010): 56-63.

[^2]: Bhattacharya, Suparna, et al. "Reuse, recycle to de-bloat software." ECOOP 2011–Object-Oriented Programming. Springer Berlin Heidelberg, 2011. 408-432.
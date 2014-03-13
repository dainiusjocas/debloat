---
layout: post
title: Unikernels
description: "Idea of unikernels and what benefits it brings"
modified: 2014-03-05
category: articles
tags: unikernels, minimization
image:
  feature: so-simple-sample-image-1.jpg
  credit: Michael Rose
  creditlink: http://mademistakes.com
comments: true
share: true
---

While reading random papers about how to develop software which contains only valuable features I've discovered the idea of unikernels[^1].

> Unikernels are single-purpose appliances that are compile-time specialised into standalone kernels, and sealed against modification when deployed to a cloud platform.

The idea here is terribly simple: generate single purpose non-modifiable virtual machines that serves only one service. 

The benefits of this technique are:

* significant reduction in VM image sizes,
* improved efficiency (no unneeded services),
* improved security (reducing number of lines of code reduces the attack surface),
* reduced operational costs.

So far so good. It seems to me that this approach is exactly on the other end of the spectrum than bloated software. I'd call it an "ascetic software". In that sense unikernels are exactly a method to fight against bloated software.

Of course, there are technical difficulties to produce these ascetic VMs but these are solvable at least to some extent. Authors of the paper are refering to Mirage OS[^2].

Since Mirage OS is pretty big project and they now have plenty of content should I investigate them more or they are not so relevant?



[^1]: Madhavapeddy, Anil, et al. "Unikernels: Library operating systems for the cloud." Proceedings of the eighteenth international conference on architectural support for programming languages and operating systems. ACM, 2013.
[^2]: http://www.openmirage.org/
---
layout: post
title: What is a feature of a software product?
description: "First and foremost question of the thesis"
modified: 2014-03-06
category: articles
tags: feature
image:
  feature: so-simple-sample-image-1.jpg
  credit: Michael Rose
  creditlink: http://mademistakes.com
comments: true
share: true
---

The foremost question that I have to solve in order to proceed with my thesis is the answer to the question: what is a feature?

You can hear about the features everyday, feature this feature that. But what about definition of it that can be somehow mapped to the source code? This mapping is needed if we want to have a tooling for working with features.

As described by Eisenbarth[^1]:

> A feature is a realized functional requirement of a system (the term feature is intetionally defined weakly because its exact meaning depends on the specific context). Generally, the term feature also subsumes non-functional features are relevant, i.e., we consider a feature an observable behavior of the sustem that can be triggered by the user.

Another definition by IEEE 829[^2]:

> "A distinguishing characteristic of a software item (e.g., performance, portability, or functionality)."

One more way to describe a feature is used in future-driven development[^3]:

> feature is an increment in program development or functionality

or

> a client-valued functionality[^4]



> Software users and developers have different perspectives. Users are focused on the
problem domain, where a system's features are the primary concern. Developers are
focused on the solution domain, where a system's life-cycle artifacts are key.[^5]

The jargon file describes feature as[^6]:

> 1. [common] A good property or behavior (as of a program). Whether it was intended or not is immaterial. 2. [common] An intended property or behavior (as of a program). Whether it is good or not is immaterial (but if bad, it is also a misfeature). 3. A surprising property or behavior; in particular, one that is purposely inconsistent because it works better that way -- such an inconsistency is therefore a feature and not a bug. This kind of feature is sometimes called a miswart; see that entry for a classic example. 4. A property or behavior that is gratuitous or unnecessary, though perhaps also impressive or cute. For example, one feature of Common LISP's format function is the ability to print numbers in two different Roman-numeral formats (see bells whistles and gongs). 5. A property or behavior that was put in to help someone else but that happens to be in your way. 6. [common] A bug that has been documented. To call something a feature sometimes means the author of the program did not consider the particular case, and that the program responded in a way that was unexpected but not strictly incorrect. A standard joke is that a bug can be turned into a feature simply by documenting it (then theoretically no one can complain about it because it's in the manual), or even by simply declaring it to be good. "That's not a bug, that's a feature!" is a common catchphrase. 


[^1]: Eisenbarth, Thomas, Rainer Koschke, and Daniel Simon. "Locating features in source code." Software Engineering, IEEE Transactions on 29.3 (2003): 210-224.

[^2]: http://en.wikipedia.org/wiki/Software_feature

[^3]: http://en.wikipedia.org/wiki/Feature-oriented_programming

[^4]: http://en.wikipedia.org/wiki/Feature-driven_development

[^5]: Turner, Carlton Reid. Feature engineering of software systems. Diss. University of Colorado, 1999.

[^6]: <a href="http://www.eps.mcgill.ca/jargon/jargon.html#feature">Jargor file</a>
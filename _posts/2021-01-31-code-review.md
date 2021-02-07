---
layout: post
title:  Code review
#categories: [HTML,Code]
excerpt: One important aspect of the code review process
---
One of the common aspects of my work as a developer is reviewing the code written by others. There are tons of articles that talk about best practices when doing so, however I found [this one](https://mtlynch.io/code-review-love/) from [Michael Lynch](https://twitter.com/deliberatecoder) particularly interesting, as instead of talking about the reviewer's role, it focuses on the author of the code (*reviewee*).

### A typical scenario
In this post I'd like to specifically refer to one advice that I found particularly insightful. It describes the typical scenario which goes something like this:
- A reviewer points to a line in code and suggests that this particular change is somewhat unclear, or maybe incorrect.
* An author responds to that comment providing great, detailed explanation of what that particular change is about or why it's actually a valid change.
* A reviewer reads that response and concludes that indeed the author was right and the change is absolutely legit.

That scenario described above is very common in all sorts of pull requests and at the first glance looks like a productive way of resolving issues like that. It makes the reviewer understand the change well so they are happy to approve it and it makes the author even more convinced and sure about their code change .

Is there something important missing here? Indeed.

### How to do it better
- Change the code
- Explain by this to everyone reading the code, including the author in the future.

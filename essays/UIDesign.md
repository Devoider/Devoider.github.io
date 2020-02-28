---
layout: essay
type: essay
title: Semantic UI and Seemningly Arbitrary Limitations
# All dates must be YYYY-MM-DD format!
date: 2020-02-27
labels:
  - Semantic UI
  - UI Design
  - Limitations
---

## Semantic UI
Semantic UI is frustrating to learn. Throughout the process of learning Semantic UI I have run in to countless little problems that have made the learning curve steeper simply because the documentation for Semantic UI does a great job of explaining what it can do, and a terrible job of explaining what it cant. 
# Class Limitations
The classes in Semantic UI are brilliant: beautifully simple and able to do almost anything I want simply by using the language I would normally use for it. The problem is that the use of the simple laguage implies that it can be used near universally when that is far from the truth. Often I found myself trying to use various class on elements that they could not be used on. For example
```html
<a class="ui text item centered"></a> --> this Works as expected
<i class="ui text item centered"></i> --> this does not
<div class="ui text item centered"></div> --> this sometiems does
```
This inconsistency was the root of most of my fighting with Semantic UI over the course of the learning exercises. In hindsight the reasons are often very clear but due to there being almost no feedback when a class is not doing anything, I often found myself throwing classes at the problem till it worked
# Experience
Becoming "Good" at Semantic UI will come with lots of time spent using it, learning which classes work where. Semantic UI is great, until it isnt. Semantic UI is intuitive, until it isnt. Learning those incongruities is what I have struggled with most.

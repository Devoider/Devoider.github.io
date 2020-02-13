---
layout: essay
type: essay
title: Dyslexia and Coding Standards
# All dates must be YYYY-MM-DD format!
date: 2020-02-12
labels:
  - Dyslexia
  - Reading
  - Standards
---

## Dyslexia and Dysgraphia
I am both dyslexic and dysgraphic. In short, due to physical differences in my brain, I struggle to read and I struggle to write. Reading takes longer and my writing is often disorganized and hard to read. For programming, my dysgraphia is often an asset rather than a liability. I have had to learn to adapt to my difference and that ability to think about organization in abstract ways lends itself well to programming. However, my dyslexia makes programming far more difficult.

## Saved by the Standards.
When working on large projects, especially with multiple people, keeping track of everything is difficult for a normal person. For me, keeping track is excruciating. Trying to figure out what things do and what different variables mean is a struggle. Coding standards save me from most of that hassle. Many of ESLint's little "nitpicky" features that I've heard others complain about are designed specifically to make it readable to someone like myself. For example, the code:
```js
if(foo==foa){
```
is substantially more difficult to read than:
```js
if (foo == foa) {
```
For someone like me, those spaces are the difference between taking 30s to read a line and taking the normal 2 seconds. On any group project, if coding standards aren't used it is almost impossible for me to contribute in any meaningful way.

---
layout: essay
type: essay
title: Loving and Hating Javascript
# All dates must be YYYY-MM-DD format!
date: 2020-01-23
labels:
  - Javascript
  - Hate
  - Love
---

## Javascript?

I'd never touched Javascript, not even touched java before this class and through this first week of class I've learned a lot about Javascript. It is a brilliant abomination of a programming language and over my less then a week of using it I have been both frustrated and in awe of what it is capable

## What blew my mind. &#128165;
I have been deeply ingrained into the C programing language from the beginning of the engineering program. I came to school with almost no prior serious programming experience and so I can only claim proficiency in C. So the first time I had a function create its function and the first time I had a variable change its type my mind was sufficiently blown. Most of my preconceived notions about programming were shattered. The limitations of C are nothing when compared to the beautiful simplicity of javascript looseness.

## Danger of Simplicity
The trick with simplicity and the absence of limitations is that often the limitations are in there for a reason. I recently tried to make sure an array was empty and thinking I was being tricky I used:
```js
if([] == ![]){
  ...
```
instead of something more logical, like :
```js
if(arr.length==0){
...
```
and apparently
```js
( [] == ![] ) = true
```
I spent ages trying to troubleshoot this and in fact, it was causing an infinite loop. Because of a quirk in JSfiddle, infinite loops are impossible to break out of! the official solution on the JSfiddle documentation is to 1)make a new tab so the jsfiddle tab gets minimized. 2) Stop the chrome process because closing out doesn't work. 3) reopen JSfiddle and never open that script again.
Though this is a problem with the interpreter/compiler and not with the language itself, it is telling of the types of issues my time with JavaScript has caused. 
## Verdict
In the end, I quite like Javascript. Its powerful, simple, and limited only by its finicky problems and not by its interpretation and compilation. I am very glad to be learning and understanding a new language, especially one as expressive as Javascript.

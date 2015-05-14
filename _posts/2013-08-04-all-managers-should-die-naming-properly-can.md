---
layout: post
title: All "Managers" have to die - naming properly can save your life.
date: '2013-08-04T11:10:00+02:00'
tags:
- SOLID
- Manager
- Naming
---
No, It is not about my boss. I’m talking about XXXManagers classes. When I find a class in the source code with this name it’s ALWAYS because responsibilities are not well defined.

Maybe I’m wrong and there is some cases where this name make sense but until now I have not encountered it. For me this name is a disease symptom. I will probably find something strange, not “SOLID” compliant, with several responsibilities hidden and really smelly.

But why this name is always “popping” ?

 > [There are only two hard things in Computer Science: cache invalidation and naming things.](http://martinfowler.com/bliki/TwoHardThings.html)

### Because naming is hard and we have to accept that. Naming has to be a team work, BEFORE implementation.

The easiest word to describe relationship is “manage”. It’s describing a fuzzy relationship between entities. So it’s logical to try to use it at first when something is not clear.

To be honest, when I analyze something on my white board with someone of my team, at first, I say : “I need to manage XXX with that”, but as I know it’s a disease symptom, I just draw a box WITHOUT A NAME. And this reflex simplifies my life. 

![UMLClassWithoutAName](/images/2013-08-04-ClasseWithoutName.png)

As I don’t write something wrong, I accept that I need to think deeper the responsibility of my class. Then I describe the situation, and it helps me to find the right name. The team as to be trained to detect such situation, admit that you don't currently know names, even your design seems good.



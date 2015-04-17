---
layout: post
title: All "Managers" should die - naming properly can save your life.
date: '2013-08-04T11:10:00+02:00'
tags:
- SOLID
- Manager
- Naming
tumblr_url: http://blog.thomasleguillou.fr/post/57321249849/all-managers-should-die-naming-properly-can
---
No, I’m not talking about my/your boss. I’m talking about classes XXXManagers. When I find a class in the source code with this name it’s ALWAYS because responsibilities are not well defined.
Maybe I’m wrong and there is some cases where this name make sense but until now I have not encountered it. For me this name is a disease symptom. I will probably find something strange, not “SOLID” compliant, with several responsibilities hidden and really smelly.
But why this name is always “popping” ?

There are only two hard things in Computer Science: cache invalidation and naming things.
– Phil Karlton

The easiest word to describe relationship is “manage”. It’s describing a fuzzy relationship between entities. So it’s logical to try to use it when something is not clear at first. And that’s the problem, you need to pass after the first analysis.

To be honest, when I’m trying to analyze something on my white board with someone of my team, at first I am saying “I need to manage XXX with that”, but as I know it’s a disease symptom, I just draw an empty box. And this reflex simplify my life. Because if I doesn’t write something wrong, I’m accepting that I need to think deeper the responsibility of my class. Then I try to name the environment classes, and it’s helping me finding the right name.

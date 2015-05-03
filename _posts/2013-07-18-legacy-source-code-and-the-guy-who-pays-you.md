---
layout: default
title: Legacy source code and the "Guy Who Pays You" - Strategy helps you !
date: '2013-07-18T12:44:00+02:00'
tags:
- legacy
- communication
- Redesign
- technical debt
tumblr_url: http://blog.thomasleguillou.fr/post/55772012935/legacy-source-code-and-the-guy-who-pays-you
---
The story usually begin with someone from the support saying :

“Guys, your firmware sucks, and you create regression bug on each release. The prehistoric version X.X.X was enough reliable, so why did you change something ?”

And on the following meeting you hear something from the marketing saying :

“WHAT ? You need so much time to add this new feature ?”

And those guys didn’t see all the work you have done, trying to improve the situation of this firmware.
When you hear all of that, you need to know it, you are trapped because you have to deal with a legacy firmware situation.

All teams have ideas to change something “technically” on the firmware, a lot of notes are popping on the wall, a lot of books, articles, video are talking about this subject. But for me it’s not the biggest problem.
If you only see the situation with a “technical” approach you are not fighting for a  long run, you are sprinting while you are in a marathon. What you need is a battle plan, a strategy, and a way to communicate it to the guy who pays you (or the GWPY) (and by the way it’s a good exercise to identify the real guy who pays in your organization).
This communication is really “dangerous” because at first you will be the honest guy, the guy wanting to convince the GWPY, explaining him honestly that : “the team is suffering”, that we corrected the “ultra critic” point due to a design flaws, and we take time to “refactor this core feature”. Until one day when he will answer you :

“What ? You take 2 months to change this part A and the bug BASE-# just popped !”

And he said that, even BASE-# bug is absolutely not linked with the part A. This situation is really not comfortable.
Currently, I suggest (thanks to my team :) ) three strategic points to improve the way you deal with this situation:
Step back : facing this legacy code, you need to have a high level idea of the situation within the team. Where is the complexity, where do you often commit in the source code, how features are placed in the map, where have you absolutely never been. Before redesigning something you will need to have this vision, it will be your tool to see the technical progression of your work..
Quantify the technical debt : you need to know “how much” the difficulty is. It will be absolutely helpful to follow the improvement of the situation and to communicate it to the GWPY. It could be the number of regression bugs detected,  a “Quality Deficit Index” or some synthetic analysis results but absolutely nothing technical. The GWPY will support your work if you can show  him a concrete improvement of the situation, not technical concept he doesn’t well understand.
Involves all the team in the redesigning work : I think this part is the hardest. Some experienced people have an idea of what to do and how to do it, efficiently. But others will continue to work on the source code, and generally increase the technical debt if they don’t think they can do something in their everyday developments. If your are able to lead all the team in this direction all the “low priced, high value” actions will be completed smoothly on the flow.
So these ideas are not easy to follow and required a big work with the team to obtain metrics, and redesign skills/methods. But the biggest indicator to follow is : “Did something changed since last time I asked”. If not, you are lost, and if you do nothing the situation will be more and  more painful for everyone.

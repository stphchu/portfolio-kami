---
layout: post
title: Hey Alexa (pt. 2)
tags: Bloc, Alexa
---

I just completed the second part of the Alexa project ("Build a Fact Skill") and, no less than three times, found myself completely frustrated to the point of considering changing to another project. Similar to the first checkpoint ("Build a Trivia Skill"), the instructions were slightly outdated, which wasn't too bad since the implied steps were easy to figure out.

The problem came when there _was_ a problem.

Every time I encountered an error, I never knew why or where to look because the messages were so vague. They might have all well been, "_There was an error or something somewhere because of one or more things didn't happen correctly but here's a link to how we handle errors in case you're wondering_," and I would've been left with just as much information on how to handle them.

{:.center}
<img src="/assets/dont_understand.gif" width="300" height="220" />

On my first attempt, I encountered an error during the certification step (the ); it kept failing during the "functional test" and I had no idea why. After poring over everything I entered and all the steps again, I eventually decided it was going to take more time to pinpoint and fix whatever error it was than to just start all over -- which was what I ended up doing. The second attempt went smoother, though I wish I knew what I had missed the first time around.


<small>
    {% for tag in page.tags %}
    <a href="/tags/{{ tag }}/">{{ tag }}</a>
    {% endfor %}
</small>

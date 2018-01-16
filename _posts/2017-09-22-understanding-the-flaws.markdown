---
layout: post
current: post
cover: assets/images/ballofmud.jpg
navigation: True
title: Better Patterns, Better Teams, We Can Do Better
date: 2017-09-22 10:32:27 +0100
tags: [Design Development Creativity]
class: post-template
subclass: 'post tag-design-dev-creativity'
author: donalrafferty
---

This week we had three readings to complete for the Design, Development, Creativity class all of which gave me thoughtful and considered insight into very real problems I contend with on a daily basis.

First up for me was Foote, B. & Yoder, J. Big Ball of Mud. {% cite ballofmud %}

This article suggests that the big ball of mud is in fact a valid architecture pattern and proposes that this is true because it is the most widely used and therefore most successful pattern that can be seen in use throughout software development.

But a big ball of mud is hard to traverse and difficult to understand, Foote & Yoder suggest that we should be able to do better.

## Resist the power of the dark side

In the article the forces that cause us to build big balls of mud are laid bare, they are all too familiar to me, time, cost, experience, skill, visibility, complexity, change. Compelling reasons are given as to why these forces cause us to accept the controlled chaos of the mud. The problem is we often forget to clean up when we gain more control over these forces.

The article goes on to visit several different patterns describing how they can help or hinder a big ball of mud architecture. It highlights many of the flawed processes used that lead to this mess of a pattern and disseminates information on how to detect and avoid these flaws. For me this information is invaluable to further my growth in understanding the problems I endure in my job as a software engineer. I believe I am astute at understanding and identifying problems in the approach my team takes and even that I can propose and implement solutions to these issues. However I have never been able to fully understand the reasons why the problem exists in the first place and the reason my proposed solutions lead to improvements.  

I am quickly gaining huge insight into not just the reasons behind these problems but also understanding how I can evaluate the problem and understand where the root cause is coming from myself. For example in the past I have been guilty of making prototypes too high quality and of giving in to now throwing away throwaway code. The issues that appeared at a later stage I identified and fixed but I never attributed these issues to my initial poor decisions.

Many of the further patterns described in the article such as Piecemeal Growth, Shearing Layers and Keep it Working can be identified in the projects I have worked on, they have offered me an insight into the language and descriptions I need to use to portray to my team and management what needs to be done to improve.

![image-center](https://firebasestorage.googleapis.com/v0/b/donals-blog.appspot.com/o/teamwork.jpeg?alt=media&token=9b7fab51-f8e2-46a4-9305-241290086e25){: .align-center}

## Mind tricks don’t work on me

The second article I read this week was Sawyer,	S. Software	development	teams {% cite devteams %}

This dealt with the different social aspects of software development teams including how people interact, behave and organise. Again this article gace me great insight that I could directly map to my current and past teams in my software development role.

It's very interesting reading an article that describes the tell tale signs of how a team works only to be able to directly see these traits in your own team. Furthermore the article describes the benefits and drawbacks of the different social archetypes that can be seen in software development teams, thus arming me with the knowledge to understand how my very team is performing and allowing me to pinpoint areas I can improve.

The article describes three different archetypes, sequential, group and network. While also stating that most teams adopt a hybrid of all three. I can see this in my team and I intend to dig deeper into the negative traits within my team and propose solutions to improve, I was particularly interested to read about members contributions not being recognised as a reason they leave within the network archetype.

![image-center](https://firebasestorage.googleapis.com/v0/b/donals-blog.appspot.com/o/waterfall.jpeg?alt=media&token=0a540e36-d0c1-4212-890d-5c4d4335bb0d){: .align-center}

## It's a trap!

The final article I read was Royce,	W.W. Managing Development of Large Scale Software Systems {% cite waterfall %}

Royce is the computer scientist who is credited with the waterfall development methodology and this is the article that describes it. As someone who has years of experience as a high level programmer my opinion of the waterfall model is tainted with disdain. I must admit I was a little confused as to why we were tasked with reading this and also I wasn't really looking forward to having to traipse through something describing the waterfall model.

However it quickly became clear why we were asked to read this and I quickly changed my attitude towards it. Within the article is the very interesting seeds of what we would call agile development today. Royce proposes such practices as iterative relationships between stages of development, building twice, once rapidly to get feedback akin to prototyping and then a second using the knowledge gained from the first. He even points out the flaws of the rigid step by step process. His ideas are not as flexible and adaptable as agile today but for the time they would have been an excellent guide given the slower cycles of change.

It becomes clear that his approach to development was either misinterpreted or that the elements of his methodology that seem risky or perceived as too costly for the benefit fell by the way side and the step by step rigid approach that Royce warned against became the norm. Just like the big ball of mud it became successful in spite of it's flaws, not because of it's benefits.

For me this is a very important understanding to make, in software development we frequently pick what we feel are the best bits or the parts that suit us best while ignoring the entire picture, we would be wise to make sure we fully understand what someone is proposing before choosing to use only the sections we like.

References
----------

{% bibliography --cited %}

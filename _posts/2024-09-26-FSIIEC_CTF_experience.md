---
title: How to create a CTF
date: 2024-09-26 +0200
tags: []
categories: [Articles]
---

# Introduction:

Hey guys ! It's been a long time since i didn't write an article so I decided to come back with a completely different subject from what I'm used to propose on this blog.  
Basically I usualy write technical articles about tools that I create or write ups of ctf challenges, but today the topic will be **Creating a CTF from an admin point of view**. In fact with my security club SecuritIIE we organized a CTF called FSIIEC CTF, accompanied by FSEC-SS the security club of APU. This article will be mix of advices and feedback from the organization of our CTF.  

Before starting, please note that this won't be a technical article, I won't dive deep into how we set up our infra or challenges, it will be more sort of an experience feedback and some advices that I could give to people who wanna create their own CTF with their friends/colleagues.

## What is a CTF ?

You can skip this part if you are used to CTF haha.  

CTF are basically cybersecurity competitions where people can compete on many topics such as web security, cryptography, reverse engineering...  
Each category can have its own challenges to solve in order to gain *points*, yea you understand that the more you have points the more you are high ranked !  
This competition can be either team or solo, online or presential and with many details that admins can change regarding the rules.

## How to start ?

Now that you know what is a CTF let's say you wanna create one, what's the starting point ?  
Okay first you should have already been involved in CTF participation as a player, thus you will be able to understand what a player expects from this competition.  It can be regarding the type of challenges, difficulty, rabbit holes, organization...  This will give you a great experience to use as an admin for your next CTF.  

Next you will start to plan about some key points of your CTF :
- Will it be competitive or educative ? For instance ours was educative, so the challenges were easier so that beginners can also join.
- Who you wanna target ? We targeted only students from 3 universities with whom we have a partnership.
- How long it will last ? This point is often underestimated while it's very important. In fact if you choose to make it longer, it means that you will have
to handle the platform during a longer time, so more awareness (and more tiredness haha), but it also means that if you have an incident you have more time to repare it. If you choose to make it shorter you will have probably less work regarding the number of the challenges to make, but it will be more intense. Our CTF was a 24 hour one, I will get into details about our CTF later in this article.

## Building your team

That's a *crucial* question, are you building this ctf with friends, colleagues ?  
In our case all the members of our security club + two students from the same school joined together for that CTF.  
From my experience it's important to keep it as few as possible, too much people means harder communication, harder communication means more complex organization... Ya understand !  

So it's important to maintain a balance between the number of people and the tasks assigned, so as not to spread yourself too thinly or end up with too much imbalance in the work done.  

Going back to our CTF, we basically had multiple persons with various skills : cryptography, reverse engineering, web... So it wasn't hard deciding who will be in charge of what in priority. But don't forget that one must not keep himself too focused on one category, helping others is part of the process too !  

## Creation and testing of the challenges

YOU. MUST. FOLLOW. A. PROCESS.  
Yes.  

I know that many people don't like conforming to processes, but that's literally what will save you time and protect you from errors !  

Let's take a step back to our CTF to see how this has played out in practice : 

The first step was to choose a collaborative platform, **GitHub** was *perfect* for that.  

Secondly, set up the rules for approving and testing the challenges. How we did that ?  
Three stages : totest, approved, final.  
- The first folder contains challenges to test technically, the challenge and its solution must work.  
- The second contains challenges to approve globally, not only for the technical part but all the requirements regarding the difficulty, the statement...  
- Finally the third one contains the challenges that are ready to deploy to the infra, they are 100% good including details like flag, open port...  
One important rule that we've put in place : Every time a file is moved from one stage to another, it must be verified by someone other than the person who created the challenge, in order to avoid mistakes that a designer can't see, and to promote collaborative understanding.  

That's for the static part, but testing must also be done when the challenges are deployed. Otherwise you'll encounter bugs that you didn't expect. (happened to us haha)  

## Errors that you can avoid

- Always **TEST** your challenges, at each step.  
- Plan everything you're going to do : challenge production, deployment, communication... That gives you a path to follow when you feel lost, but don't feel too rigid about it.  
- If you are at the top of organization like I was, beware of not giving enough responsibility to your collaborators : you are responsible for steering the ship, but you can't take it all on !  

## Sponsors

An important part of your organization will be finding sponsors to finance the winners' prizes. In our case, the sponsor was directly found: our school has a fund that enabled us to award the prizes to the ctf winners ! Presenting your project to your sponsors in a way that convinces them that it will give visibility to their brand is crucial.

## Promotion

Lastly the part that engineers hate : Promotion & Marketing !  
Obviously, the goal is to get as many players as you can within the limits of your resources. In our case, we were open to students from 3 universities, which gave us over 200 players in the end.  
We had 3 directions for communication: our school's discord server, our club discord server and linkedin. Creating posters that are adapted to each platform and easy to understand is crucial to reach the maximum number of people. Using a qr code to transfer potential players to your site is a good idea (which we have implemented).  
Note that we were not alone in promoting this event, as we organized it with FSEC-SS members from APU, who also helped us !

## The End

That's it guys, I hope you learned some things with this article. Feel free to tell me what could be missing, I might update it to make it more complete !
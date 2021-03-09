---
layout: post
title:  "On the Bleeding Edge of Teaching Machine Learning"
date:   2021-03-09 11:00 -0500
categories: ML PBL
---

# Overview

At the end of January, I started working with my AP Computer Science Principles students on a Machine Learning project. Prior to this, they had worked with google's [Teachable Machine](https://teachablemachine.withgoogle.com/) on its own and designed a model that they connected to some sort of output (generally, through [P5](https://p5js.org/)). So, it made sense that this project would scale up in scope once more. The general idea was to come up with a problem they wanted to use Machine Learning to try and solve, research ways they might be able to solve it, then attempt to solve it. 

This sounds like a straightforward project that is not really on _the bleeding edge_. 

There are a couple of things that make this project interesting from the bleeding edge perspective.

1. Following up on a previous experiement, I decided to co-create the rubric with my students. 
2. This was designed as a group project, but I had the crazy notion that the groups could be formed with students across sections. File this under the _what does covid-19 make possible?_ heading.  
3. I don't know a lot about Machine Learning. 

## Co-Creation of the Rubric

This was actually the least successful aspect of this project. My students _seemed_ really enthusiastic about this idea, and there was some mild success on a previous project, but after much prompting and suggestion, the only piece the students wanted to add was some sort of group accountability. 

The idea was that I had certain things I wanted out of the project, and I allocated 60 of 100 points to those things. The other 40 points were theirs to play with and they did not play with them. This is fine. 

## Cross-Section groups

The students were enthusiastic about this idea and our technological infrastructure makes this a possibility, so this was really a no-brainer. It allowed the students to make the groups on their own with very little friction, which is always nice. My general group formation policy is this:
> 1. State the exact structure of the groups (for this project it was, exactly ten groups of three)
> 2. Give a fixed amount of time by which the groups have to be constructed (I gave them several days) 
> 3. Let all the students know that unless 100% of the class is happy with their groups at the end of the allotted time, that I will blow up all the groups and make them myself.  

Students collaborated using [repl.it](https://repl.it/) and whatever collaborative document creation software was available to them. Repl.it is a really nice tool, actually, because it includes version control and supports a variety of platforms (some students want to code in JavaScript and others in Python).

## Lack of Subject Knowledge

I gave exactly three lessons on Machine Learning this semester. 

1. Showing them how the Teachable Machine works, along with a video from CGP Gray called [How Machines Learn](https://www.youtube.com/watch?v=R9OHn5ZF4Uo), relating that content back to the Teachable Machine, and setting some design challenges. 
2. Showing the students how to connect the output of the Teachable Machine to a P5 sketch, along with a proof of concept. 
3. Walking the students through the Tensor Flow and [ML5](https://ml5js.org/) websites, showing them the pre-made models and doucmentation, and walking them through a proof of concept.    

I also showed them this Machine Learning project that predicts a men's college basketball team's performance in the NCAA tournament by looking at [The Four Factors](https://www.basketball-reference.com/about/factors.html)

In short, I gave them a broad overview of the sorts of problems Machine Learning is currently being used to solve, some resources for how to simply implement Machine Learning, and provided a few examples. 

# Project Structure

1. I asked the groups to create a description of their project, including some sort of visual aid. They could complete this step using any format or tool they wanted (document, presentation, video, audio, etc.)
2. The students needed a biography of their data. The requirements were modled after the lovely data biographies on the ML5 website. ([CharRNN Example](https://learn.ml5js.org/#/reference/charrnn?id=model-and-data-provenance)). 
3. An analysis of how their project peforms. What does it work well on, what makes it fail, what steps did you take to correct the behavior? This was written, but I have regrets about that. 
4. The finished project. 
5. Bi-weekly self and peer reviews. 

# Reflection

When I do this again, I'll change a few things. 

1. During the co-creation of the rubric, I would give the students the full 100 points to play with and make it a design exercise in the Think-Pair-Share model. I may sit in on a group, or show a model I generate in advance with a colleague. 
2. I'll have an initial due date for their data biographies, but won't finalize their grade on this until the end. 
3. I'll actually have two analyses due, one early and one final, since revision of the model is part of the process. 
4. The analyses will be able to be in any format. 
5. The self and peer reviews will also include a group rating. 

# Showcase

Pending
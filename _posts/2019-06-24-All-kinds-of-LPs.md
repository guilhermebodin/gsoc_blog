---
layout: post
title:  "End Of The First Month"
date:   2019-06-10 12:00 -0300
---

Hello!

JuMP automatic dualization can dualize all kinds of Linear Programs, assuming you don't write an interval constraint. To finish the first month at a steady pace, we just need to finish writing a good test base for those LPs! Once this is ready, we can set up a Travis ci environment for the project.

Most of my time on the project during the last two weeks was on understanding how to do all my functions using the existing MathOptInterface structures. This is important because this way, we can preserve sparsity and do a better performant tool for the users.

During this week I did a hard test dualizing a problem with 400+ variables and 800+ constraints,  a linear classifier. The code can be found on a notebook [here](https://github.com/LAMPSPUC/Teaching.jl/blob/master/Optimization/Class1/Linear%20Classifier.ipynb) 
I suppose this is a good test example for our test base

The next step is to start with SOC and SDP constraints!

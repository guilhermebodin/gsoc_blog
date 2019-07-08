---
layout: post
title:  "Dualizing cones"
date:   2019-07-08 14:00 -0300
---

Hello!

For the past few weeks we have been dualizing cones, so far we have already implemented Second Order Cones and Rotated Second Order Cones, all of course with their tests. The next step is to implement a JuMP Full bridge optimizer so you can dualize all problems that can be written as Second Order Cones and Rotated Second Order Cones. An example is that you could dualize quadratic programs (not initially supported) because you can rewrite a quadratic program as a second order cone program.

Another major step we took is to add continuous integration to the package, now Travis CI runs the tests every time a new Pull Request is made!

The Project is entering an exciting part where my peers are starting to propose future projects that can use the automatic dualization feature.

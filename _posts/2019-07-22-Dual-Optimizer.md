---
layout: post
title:  "Dual Optimizer"
date:   2019-07-22 14:00 -0300
---

Hello!

End of month 2, we are getting to the final sprint of the project! This month we implemented the duals of the Positive Semidefinite cones and more importantly, we implemented a `DualOptimizer`. It works like a standard solver, but it solves the problem via its dual representation. This feature is exciting because some problems have such a structure that solving the dual is faster than solving the primal. Now other projects can exploit this advantage by doing `DualOptimizer(Any JuMP solver you wish)`. 

For this final month, we must get ahead on documentation, finish with the last cones (Exponential Cone and Power Cone). We will also build a naming convention. This way if someone wants to query problem constraints, it can do it easily without having to deal with the model backend.

Excited for the last month :)

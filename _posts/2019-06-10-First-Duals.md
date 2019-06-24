---
layout: post
title:  "First Duals"
date:   2019-06-10 12:00 -0300
---

Hello!

JuMP automatic dualization is alive! The feature can already dualize most Linear Programs. Right now attaching the dual model to a classic JuMP model is not straightforward but it works! There are some script examples in the Dualization.jl repository, more specifically in the `dual-min-lp` branch on `simpleLP.jl`.

The most challenging tasks I faced during these first two weeks were having to create a proper data structure to handle sparsity of constraints and objective functions in a memory efficient way. And defining an architecture so I can scale some essential functions such as `add_dual_model_variables` for every MathOptInterface.jl `Function` and every  MathOptInterface.jl `Set` easily. 

Another challenge was to write code that fits the JuMP style guide. I would say that this is just a matter of getting the habit, although it seems a little silly it is one of the most critical points of the project. Writing easily maintainable code.

The next steps are to finish all possible ways of defining Linear Programs in MathOptInterface.jl and then close the first PR in Dualization.jl. 

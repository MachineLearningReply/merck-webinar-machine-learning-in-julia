![julialogo](https://raw.githubusercontent.com/JuliaLang/julia-logo-graphics/master/images/julia-logo-mask.png)

# Webinar - State-of-the-art Machine Learning in Julia

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MachineLearningReply/merck-webinar-machine-learning-in-julia/master?filepath=main.ipynb)

This Webinar is for you, if you like to learn more about Julia and how it features advanced machine learning.

What you will learn

* How to use Julia and Multiple Dispatch, Julia's powerful core design
* the simplicity of [**Flux.jl**](https://fluxml.ai/) and [**scientific machine learning**](https://sciml.ai/)

Preparatory material & requirements

* You should have a beginners knowhow on programming

Author: Stephan Sahm, s.sahm@reply.de, [Machine Learning Reply](https://www.reply.com/machine-learning-reply/de/), [Julia User Group Munich](https://www.meetup.com/Julia-User-Group-Munich/).

<img src="https://d11wkw82a69pyn.cloudfront.net/siteassets/images/logos/companies/machine-learning-reply-logo.png" alt="" height="50"/>
<img src="https://d11wkw82a69pyn.cloudfront.net/machine-learning-reply/de/content/siteassets/juliausergroupmunich.jpeg" alt="" height="100"/>


## Why Julia?

**Why was Julia created?**

Definitely read this now impressively old post by Julia founders by Jeff Bezanson, Stefan Karpinski, Viral B. Shah, and Alan Edelman https://julialang.org/blog/2012/02/why-we-created-julia/.

Here my favourite passage

> We want the speed of C with the dynamism of Ruby. We want a language that's homoiconic, with true macros like Lisp, but with obvious, familiar mathematical notation like Matlab. We want something as usable for general programming as Python, as easy for statistics as R, as natural for string processing as Perl, as powerful for linear algebra as Matlab, as good at gluing programs together as the shell. Something that is dirt simple to learn, yet keeps the most serious hackers happy. We want it interactive and we want it compiled.

**Why this needs to be an extra language?** Why cannot Python be made that fast for instance?
Checkout the official compact answer to this in the julia manual F&Q https://docs.julialang.org/en/v1/manual/faq/#Why-don't-you-compile-Matlab/Python/R/%E2%80%A6-code-to-Julia?-1

Here my favourite passage

> Julia's advantage is that good performance is not limited to a small subset of “built-in” types and operations, and one can write high-level type-generic code that works on arbitrary user-defined types while remaining fast and memory-efficient.
> Types in languages like Python simply don't provide enough information to the compiler for similar capabilities, so as soon as you used those languages as a Julia front-end you would be stuck.

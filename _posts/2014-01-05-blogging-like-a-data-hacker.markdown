---
layout: post
title:  "Blogging Like a [Data] Hacker"
date:   2014-01-05 17:29:00
tags:   
 - blogging
 - data hacker
 - infographic

---

I use [Wunderlist](http://www.wunderlist.com) to organize my
todo-lists. The todo-list that has seen the most activity in the last
year is called *Future Blog Posts*. 

{% include bladh/wunderlist_infographic.html %}

As it almost always happens, [quantifying your own
behavior](http://quantifiedself.com) leads to interesting insights. It
quickly became apparent that the most reasonable way to contain such
an unsustainable growth of potential creativity was to removing items
from that list. 
Hence blogging.

> Getting out of the door is the hardest part

When I start something, I usually spend an insane amount of time
researching on all the possibilities. Then I move on to something
else. A good way to counter this is to embrace the *make-first, think
later* motto. In my books, this means blog like you code, using your
favorite revision control system and editor.

## Blogging Like a Hacker

[Github](http://github.com)'s Tom Preston-Werner says it all in [Blogging Like a
Hacker](http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html).
Blog like you code. Prototype fast, see changes live, use the tools
you're already proficient with.

These days that concept has evolved into [Github
Pages](http://pages.github.com), a free hosting service for static
webpages, on *Github*. The number of people who are hosting their
personal pages on *Github Pages* is quickly increasing:

{% include bladh/github_io_infographic.html %}

However, the reason why I want my personal pages on *Github* is not
even a matter of tools. It's a matter of principle. 

> If you make something good, people will use it.

No, they won't. They most likely won't even know you did it. 

If you want others to build on your work, you have to lower the
entrance barrier. Open source is not even the point anymore, it should
be a given. There's plenty of open source code sitting in poorly
documented archives stored on some academic's page. That's not useful,
if the metric on which we measure usefulness is even only somewhat
correlated to "the common good". 

*Github* is a brilliant solution to the entrance barrier problem. It
 makes it dead-simple to get started building on the work of others, and
 safeguards the concept of intellectual property, which is
 automatically built in the forking process. 
In addition, *Github* provides social filters (rankings, voting) to
 allow the good content to get recognition. 

I envision the world applying the Github mantra to other things than
code. Like this recipe? Fork it, replace garlic with shallots, re-share. Love
this songs but want to change the lyrics? Love the movie but not the
ending? Maybe some days we'll fork artworks, companies, and even
physical objects.

Like this? [Fork it, make it
better](https://github.com/LucaFoschini/lucafoschini.github.io)!


## Beauty Matters

As soon as I settle on *Github Pages*, and therefore, *Jekyll* which
is their processing engine, my ADHD kicks in. 

> Responsive, typography-oriented, mobile first. Beautiful. 

I spend some time tinkering with the idea of making something like [Bret
Victor](http://worrydream.com/)'s page. Then I woke up. 

I'm not a designer. I have an eye for design but don't know how to
make it, much like one can love food without being a chef. 
To make good food I must follow recipes, perhaps slightly
twist them to meet my needs. Cutting down on salt, add some vinegar,
but don't wing amounts or cooking times, that's a recipe for
a recipe disaster. So, templates.

I spend a few hours looking around *Jekyll* themes with non-boring yet
minimal typography, and that look good on mobile. 
See [this series of
articles](http://paulstamatiou.com/responsive-retina-blog-development-part-1)
by [Paul Stamatiou](http://paulstamatiou.com/about), and [this](http://nicolashery.com/fast-mobile-friendly-website-with-jekyll/)
concise-yet-precise by [Nicolas Hery](http://nicolashery.com/) for
some background on the topic.

I then come across *Ghost* and *Vapor*. [Ghost](https://ghost.org/) is the
new kid on the block among the blog platforms, the media [waxed
poetic](http://techcrunch.com/2013/05/07/ghost-will-take-your-boring-blog-to-the-next-astral-plane/)
about it. *Vapor* is a *Ghost* theme by [Seth
Lilly](http://sethlilly.com/), designed for responsiveness and with an
eye on typography. 

*Ghost* and *Vapor* look great. Except, they're not based on Jekyll,
 nor they can be hosted on *Github Pages*. Make first, think later: I
 ported *Vapor* to *Jekyll*.
[Go grab it](https://github.com/LucaFoschini/jekyll-vapor), see it live [here](http://lucafoschini.github.io/jekyll-vapor/).

## Data. Data. Data.

> The data tells the story.

Data-driven journalism is officially a thing.

{% include bladh/data_driven_journalism_infographic.html %}

Moreover, I personally have a hard time reading articles where claims
are not supported by data (read: visualization). It's just a matter of
bandwidth. 

That means, there must be nice charts and [iPython
notebooks](http://ipython.org/notebook.html) floating around.
*Jekyll* is a winner again on this front, as it makes simple to include
*gists* and content from other external sources.

## Wrap up

Desiderata:

 * on *Github*
 * Beautiful
 * Mobile First
 * Data Oriented

{% include bladh/venn_blog_space.html %}

This is my attempt of making a blog for data hackers.

Hackers make the tools to collect, process, and visualize data. Data
journalists use those tools. Data hackers live in between. They
focus on data but know how to make their own tools to collect it,
process it and visualizing it. 



---
layout: post
title: "Attack Plan"
date: 2014-08-26 22:05:05 -0400
comments: true
categories: renderscript, UI, UX

---
<!-- 150 wpm, Renderscripted Custom Views, part 1/5 -->

### 'Renderscripted' Custom Views, part 1/5 

{% img right /images/posts/the_battle.png 256 The Battle %} 

My current goal is to show how Renderscript could be used to create innovative and dynamic UI components. Let's aim to [Echant and Amaze and](https://developers.google.com/events/io/sessions/326368573) and... hmm, what am I forgetting here? :)

One thing to realize is that Renderscript is a tool that can solve new and *[interesting](http://streamcomputing.eu/blog/2013-06-03/the-application-areas-opencl-can-be-used/)* problems. Comparatively, drawing primitives and rendering text are mostly solved problems on Android.

As outlined in [Custom Drawing](http://developer.android.com/training/custom-views/custom-drawing.html), you can programmatically render lines, shapes, text and so on. Also note that [Drawable and Animation Resources](http://developer.android.com/guide/topics/resources/drawable-resource.html) can be defined as xml resources.

This leaves us with a solution (a high performance number crunching tool) looking for a problem. Since we can crunch large data sets, [beautiful visualisation](http://shop.oreilly.com/product/0636920000617.do) of data is one interesting area of exploration.

Another avenue is [live graphical content generation](http://en.wikipedia.org/wiki/Procedural_generation). We can render complex geometric shapes to add [pizzazz](http://www.merriam-webster.com/dictionary/pizzazz) and flair to our apps. Think [fractals](http://en.wikipedia.org/wiki/Fractal), special effects, sounds even, animations...


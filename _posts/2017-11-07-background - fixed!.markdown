---
layout: post
title:  "Background - fixed!"
date:   2017-11-07 10:42:09 +0700
categories: jekyll update
---
After alot of work just trying things out, apparently it wasn't so difficult after all.
The first idea came from someone on slack, which just added their folder to the SRC location to make it work, that still didnt quite do the trick for me though.
My first fix was just adding "localhost:4000" before my image-folder, which impressivly worked, after i did the step of moving images to SRC.
So, since this wouldn't be a very good fix for a finished stage, I then looked at the map-structure in _site, and realized that my image-folder now existed in _site (it didnt before), which made me try the fix I was trying much much earlier which was adding ../ infront -- this did the trick.
Shortly put: "../images/imagename.jpg" worked, as long as "images" was located in "src".





---
layout: post
title:  "Pre-Compiling CSS"
date:   2019-11-18 17:20:00 +0100
categories: general
og_title: Pre-Compiling CSS
og_description: Pre-compiling CSS is a very clever way to write CSS, in my opinion. It was pretty tricky in the beginning, but when I got my head around how it worked I started to really like it.
og_type: website
og_image: /assets/img/og_image.jpg
---
Pre-compiling CSS is a very clever way to write CSS, in my opinion. It was pretty tricky in the beginning, but when I got my head around how it worked I started to really like it.

The biggest differences compared to regular CSS that I find are that you can nest things (which is awesome) and you can use variables to avoid having to repeat yourself a lot, especially when it comes to colors and measurements.

I decided to use the minima theme that came with Jekyll and modify it. The reason is I wanted to look at how you can do things when pre-compiling CSS and learn from it on the spot.

I used variables a lot. I set a few new color variables and used them and the sizing/measurement variables a lot throughout the website. I thought it was great! I also used mixins, partials and modules as well as @extend.

The pros of pre-compiling CSS are that nesting makes it much easier to read the code, that variables makes it much easier to change details like colors and measurements in an instant throughout the web site, and that it simply feels more organized.

The cons for me personally at this stage is that it's a lot of new things to learn to fully be able to utilize CSS pre-compiling. At this level I didn't find debugging so much more difficult than usual, but I can imagine it gets worse with bigger web sites and more complex designs.

Pre-compiled CCS is simply more complex than regular CSS, which is both positive and negative.
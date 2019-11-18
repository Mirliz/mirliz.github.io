---
layout: post
title:  "Implementing Comments"
date:   2019-11-15 12:28:00 +0100
categories: general
og_title: Implementing Comments
og_description: Implementing Disqus comments on blog posts sounded pretty straightforward, but I still ended up running into some trouble along the way.
og_type: website
og_image: /assets/img/og_image.jpg
---
Implementing Disqus comments on blog posts sounded pretty straightforward, but I still ended up running into some trouble along the way.

I had an account on Disqus from before, so I went there and registered a web site (which is something I hadn't done before despite having an account). The 
installation instructions for the Universal Embed Code was easy to understand, and since I copied the html file for the comments from the default minima template 
I just had to check the configuration and add my Disqus shortname.

All set! Should be up and running! Or so I thought... The comments box didn't even show up.

After thoroughly reading the comments template file I removed the condition that Jekyll should be in production mode for the comments to show - and now the box 
loaded.. sort of. I got the error that the comments couldn't be loaded and I should read the Troubleshooting Guide. From there I went on to read the JavaScript 
configuration variables documentation, and from there I gathered that I needed to add the variable for the page title to the comments template.

After I did this, everything looked as it should.

(Gonna re-add that condition that Jekyll should be in production mode before I publish the web site, though.)
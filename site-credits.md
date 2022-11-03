---
title: Site Credits
layout: page
permalink: /site-credits
--- 

This site was built with Jekyll, using [Celeste](https://github.com/nicoelayda/celeste) as the basis. Celeste is based on [Poole](https://github.com/poole/poole), the Jekyll butler. I honestly don't know what that means yet, but I am picturing Tim Curry in *Clue* serving me a website. Most of the design comes from this basis, but I tweaked the typography, line-spacing, and content width (I like to play around with the [Golden Ratio Calculator](https://grtcalculator.com/)). I've tried getting set up with Jekyll in the past and went down a few different rabbit holes of complex themes that promised a lot of features but also required digging through a lot of circular documentation! It turns out I wanted a simple site with a clean look and Celeste made this possible.

For the design of the landing page, however, I borrowed heavily from the [Jekyll Academic theme](https://github.com/gaalcaras/academic), by Gabriel Alcaras. I wanted the profile pic and contact information front and center and I liked the overall design of this theme. Unfortunately, the theme repository hadn't been updated for a few years and I was a bit worried that there might be issues down the road, so I stuck with the simple vanilla Jekyll and recreated the look in my own layouts.

With Celeste, however, there wasn't any mobile menu built into the default layout. I was able to fudge something together using the [Toggle Menu](https://jekyllcodex.org/without-plugin/toggle-menu/) script from the Jekyll Codex site. It's not perfect, but it will do.

Another tweak was adding previous and next post links to the bottom of the blog post pages. Celeste had pagination links on the posts index page, but once you opened up a full post there was no way to cycle through other posts without returning to the main blog page. These [instructions from bytedude](https://www.bytedude.com/jekyll-previous-and-next-posts/) worked perfectly!

I relied on the documentation for the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme to help me understand how to think about includes and layouts, and it pointed me towards using Jekyll's collection feature for my projects page. I pulled the documents-collection, archive-single, and figure includes from that theme, slightly adapting them for my needs. I also borrowed its "teaser" label for assigning thumbnails, and learned how to set a default image for projects in the config.yml file. The feature rows include helped me develop my own topic-links include which will, hopefully, allow me to drop a nicely-formatted list of links into posts and pages.  I learned a little about [CSS grids](https://www.freecodecamp.org/news/how-to-use-css-grid-layout/) by trying to recreate those feature rows, and am now also inching closer towards conversance with SASS. 

Finally, I added Twitter Card metadata (it sorta works?) and I drew upon the head.html file in the [Ed theme](https://github.com/minicomp/ed/blob/main/_includes/head.html) to add DublinCore metadata for Zotero. I also borrowed the idea of using a publication-date in the frontmatter in addition to the post date for projects that were posted on the site after being made available elsewhere.

Oh, and how did I get everything out of WordPress to populate the site? When I first decided to try out Jekyll I'd found an exporter that did the trick. But it was so long ago I have lost the details. 

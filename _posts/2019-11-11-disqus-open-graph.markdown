---
layout: post
title: "Disqus and Open Graph"
author: dan
categories: [IT]
---

## Disqus

I used Disqus to implement comments to my blog posts. It has a pretty good integration with Jekyll and it was easy to set up. I created an account on the Disqus website and got a so called shortname. 

Jekyll's minima theme already has a file in the _includes folder (disqus_comments.html) which contains the settings and javascript code you're supposed to paste from the Disqus site. I included this file at the end of each post which has "comments: true" in the front matter (which is all of them because of the common post layout) and added the Disqus shortname in _config.yml.

## Open Graph

Open Graph provides information which enables any web page to be richly represented within a social graph (for example, it allows the page to have the same functionality as other objects on Facebook). You only need to add metadata to your page in the form of \<meta\> tags in the <head> element and you're good to go!

I used the built-in Jekyll SEO tag in the head.html include file. It takes care of the most important Open Graph properties (title, url, image, type, locale, site_name, description) by reading global site variables defined in _config.yml or in the front matter of a specific page. I used the same image for all the pages and I declared it in the "defaults" section of _config.yml (and so you don't have to repeat it in front matter).
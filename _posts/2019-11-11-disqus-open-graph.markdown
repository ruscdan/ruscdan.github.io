---
layout: post
title: "Disqus and Open Graph"
author: dan
categories: [IT]
---

## Disqus

I used Disqus to implement comments to my blog posts. It has a pretty good integration with Jekyll and it was easy to set up. I created an account on the Disqus website and got a so called shortname. 

Jekyll's minima theme already has a file in the _includes folder (disqus_comments.html) which contains the settings and javascript code you're supposed to paste from the Disqus site. I included this file at the end of each post which has "comments: true" in the front matter (which is all of them because of the common post layout) and added the Disqus shortname in _config.yml.


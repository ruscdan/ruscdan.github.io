---
layout: post
title: "Robots and humans"
author: dan
categories: [IT]
---

## Robots.TXT

The file robots.txt is a simple text file in the root of your domain which instructs robots (typically search engine robots) how to crawl and index pages on their website. If your site doesn't have this file then all the search engines and other "crawlers" are free to index all the content on your site which can have a negative impact on the site's performance.

In the case of my blog I have blocked indexing of certain parts of the site for all search engines. I'm referring to files and folders used by Jekyll to configure and build the site (_data, _includes, _layouts folders and _config.yml). I allowed indexing of .scss, .css and .js files by all search engines (which is recommended) and also allowed Google to index the whole site including the images.

## Humans.TXT

This is also a text file (in the root of your domain) that contains information about the people who have contributed to building the website. It usually contains three sections: the main persons involved (TEAM), the contributors (THANKS) and information about the site itself (SITE).

I have listed myself as TEAM, together with my Facebook page (not very much going on there), where I live now and where I come from. Contributors are of course Mats Loock and Johan Leitet, but also my wife as moral support. The SITE section includes when it was last updated, language, what software was used to build it and where it is hosted.
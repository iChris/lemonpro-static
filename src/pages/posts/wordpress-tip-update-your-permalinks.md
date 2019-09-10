---
title: 'WordPress Tip: Update Your Permalinks'
date: Fri, 06 Jan 2012 21:14:59 +0000
draft: false
tags: [Blogging]
---

The other day I went on 4 or 5 toot rant on Twitter about issues I often come across in websites I visit. It was a bit of a letting off of steam and on Twitter, where you're limited to 140 characters, it's not that helpful since I just complained and didn't provide any real solutions to the issues I was complaining about.

The Problem
-----------

When you first setup a [WordPress](http://wordpress.org/) website/blog/etc., the pages and posts you create all get a unique URL which is great. Helps computers and people to be able to tell the different pieces of content apart. The problem is that the default setting is for the URL to look something like www.websitename.com/?p=123 and www.websitename.com/?p=124. Not very easy to tell what kind of page you're getting when you visit that URL, nor is it easy to tell someone later on to just go to www.websitename.com/?p=123 to find the information you need.

The Solution
------------

### Video Version

http://vimeo.com/35915918 _Direct link to [Vimeo](http://vimeo.com/35915918) or [YouTube](http://www.youtube.com/watch?v=L2acDZ6pnVU) version._

### Text Version

Luckily, as with most thing WordPress related, the solution is pretty simple. Here's the xx step process to make your URLs look nice for everyone.

*   Login to the WordPress admin
*   Go to "**Settings**" and then "**Permalinks**" (should be something like http://www.website.com/wp-admin/options-permalink.php)

[![](http://www.lemonproductions.ca/wp45/wp-content/uploads/2012/01/WordPress-Permalink-before-580x289.png "WordPress Permalink-before")](http://www.lemonproductions.ca/wp45/wp-content/uploads/2012/01/WordPress-Permalink-before.png)

*   Choose "**Month and Name**" (My personal preference but "Day and Name" works too)
*   Click "**Save Changes**"

Once you do that, WordPress will automagically change page links from things like www.website.com/?page\_id=2 to the more human readable and easier to remember www.website.com/about/ for Pages and www.website.com/2012/01/title-of-post for Posts. It makes Google happier for search results and makes your users happy because they can navigate and find things on your website much quicker and easier.
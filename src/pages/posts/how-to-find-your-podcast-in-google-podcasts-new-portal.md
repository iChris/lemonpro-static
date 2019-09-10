---
title: 'How to Find Your Podcast in Google Podcasts New Portal'
date: Thu, 21 Mar 2019 13:13:29 +0000
draft: false
tags: [google play podcasts, google podcasts, Podcasting]
---

This isn't for finding your podcast in Google Play Music Podcasts (take a breath after that mouthful) - this is for the new Google Podcasts app/portal launching in 2019.

When it officially launches with an iOS app, this should be easier to figure out. And maybe there's an easier way than this (let me know in the comments below!)

But for now...

### Get Your Podcasts's RSS Feed URL

![Podcast Feed URL](http://www.lemonproductions.ca/wp-content/uploads/2019/03/Podcast-Feed-URL-1140x530.jpg)

Using [Baseline](https://goodstuff.fm/baseline/) as an example, I'd right click on the Subscribe to RSS Feed text and end up with this:

```
https://goodstuff.fm/baseline/feed.xml
```

### Figure Out Your Podcast's ID With Google Podcasts

Go to [Google's Podcast Publisher Tools](https://search.google.com/devtools/podcast/preview) page and paste your RSS Feed URL in and click **Generate**:

![Google Podcast Publisher Preview dev tool](http://www.lemonproductions.ca/wp-content/uploads/2019/03/Google-Podcasts-Preview-1140x516.jpg)

That super long URL it generates for you links to a page that will currently work on Android devices - [here's Baseline's version](https://www.google.com/podcasts?feed=aHR0cHM6Ly9nb29kc3R1ZmYuZm0vYmFzZWxpbmUvZmVlZC54bWw%3D) - but doesn't help anyone else out on iOS or a computer.

![Google Podcasts Baseline](http://www.lemonproductions.ca/wp-content/uploads/2019/03/Google-Podcasts-Baseline.jpg)

To get a link to your podcast in Google Podcasts, you need to copy everything after "_podcasts_" in the link generated for you.

So for Baseline the URL was this:

```
https://www.google.com/podcasts?feed=aHR0cHM6Ly9nb29kc3R1ZmYuZm0vYmFzZWxpbmUvZmVlZC54bWw%3D
```

So I need to copy this bunch of random letters and numbers:

```
?feed=aHR0cHM6Ly9nb29kc3R1ZmYuZm0vYmFzZWxpbmUvZmVlZC54bWw%3D
```

Then just simply paste that long string at the end of the URL for the new Google Podcasts portal, https://podcasts.google.com, like so:

```
https://podcasts.google.com?feed=aHR0cHM6Ly9nb29kc3R1ZmYuZm0vYmFzZWxpbmUvZmVlZC54bWw%3D
```

Which, when you [go to that page](https://podcasts.google.com?feed=aHR0cHM6Ly9nb29kc3R1ZmYuZm0vYmFzZWxpbmUvZmVlZC54bWw%3D) from anything other than an Android device, should give you a nice view of your podcast in Google Podcasts like this:

![Baseline in Google Podcasts](http://www.lemonproductions.ca/wp-content/uploads/2019/03/Baseline-in-Google-Podcasts-872x800.jpg)

Android devices should open the Google Podcast app already installed on your device.

Thanks to [James Cridland and Podnews](https://podnews.net/update/google-podcasts-web) for the heads up about Google Podcasts new portal.

By the time I hit publish on this, Google might have updated their [Podcast Publisher tools](https://play.google.com/music/podcasts/publish?u=0#) - and hopefully figured out how to combine Google Play Music Podcasts with Google Podcasts so we only have 1 podcast portal to worry about at Google.
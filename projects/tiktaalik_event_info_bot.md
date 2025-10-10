---
layout: project
type: project
image: img/tiktaalik/bots_logos-250x250.png
title: "Tiktaalik Event Info Bot"
date: 2019-2021
published: true
labels:
  - Python 3.7
  - Flask
  - Tweepy library
  - Google AppEngine
  - Telegram API
  - Twitter API
summary: "A Python bot that allowed informing of an event date countdown via Twitter posts and Telegram replies."
---
 
<img class="img-fluid" src="../img/tiktaalik/bots_logos.png" alt="Tiktaalik Event Info Bot Logo">

***Tiktaalik Event Info Bot*** is a python bot I created as personal project and then made available freely under a GPL v.3 license, while also offering commercially assistance to set it up. The bot addressed my need to communicate regularly via Twitter and Telegram messaging app about how much time was left to the date and time of certain event. As I could not find any bot offering such functionality, neither open-source nor a commercial product, I decided to implement it myself.

***Tiktaalik Event Info Bot*** was implemented using Phython 3.7, the Flask web framework, the then availble Twitter API (before it became Musk's X platform), the [Telegram API](https://www.transbankdevelopers.cl), the [Tweepy library](https://www.tweepy.org), and [Google AppEngine](https://cloud.google.com/appengine) (optionally).

While developing this product I learned how to create a bot that would work either in any regular server or taking advantage of Google Cloud Platform's AppEngine service. This bot was able to simultaneously reply to requests of both Twitter and Telegram users via using a a Flask REST application. Additionally, by triggering cron-regulated tasks that would hit certain REST URL, the bot was able to regularly post broadcast tweets at any predefined times.

A specially tricky part of making the bot work as expected was the fact that it had to handle not only dates but also time differences, even taking into account time zones and daylight savings time adjustments. This was required to ensure that the countdown was always precise, down to the second.

<span class="text-decoration-underline">___To Do___</span>: As the Twitter platform was taken over by Elon Musk to try to forcibly steer the public opinion towards his far-right political views, he restricted the public access to the platform's API by means of eliminating the free-access tier. Then, he began charging insane fees for access to the most basic level. As this makes mostly prohibitive to try deploying a bot like this for most use-cases via the now X platform. Therefore, I intend to eventually replace the Twitter service for the Bluesky platform, and maybe add more platforms.

***The product page is available online*** [in my website](https://tiktaalik.dev/tienda/productos/tiktaalik-event-info-bot). This page provides detailed explanations of the bot characteristics and functionality.

***The open-source code repository is available on*** [Github](https://github.com/tiktaalik-dev/Event-Info-Bot).

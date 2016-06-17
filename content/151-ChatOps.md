---
draft: false
slug: "what-the-heck-is-chat-ops"
author: Alan Bush
date: 2016-06-17T13:00:00-06:00
show_date: 2016-06-16T13:00:00-06:00
number: 151
title: "What the heck is ChatOps?"
summary: "What the heck is ChatOps? We didn't know, so we brought in Martin Smith, from Rackspace's Fanatical Support for AWS team to share how they define ChatOps on their team, what problems ChatOps solves, how we're using it to help our customers. This was a great show, full of useful information, and maybe, just maybe, a surprise visit from comedic legend Martin Short."
youtube_id: uEVZiuiaQaw
featured_image: http://drops.albush.com/151-ChatOps-PostShow.png
calendar: https://plus.google.com/events/cibf9ls6jvqc2jfifgdpptb49pk
duration: "52:04"
length: 37.5
mp3: http://drops.albush.com/what-the-heck-is-ChatOps.mp3
ogg: http://drops.albush.com/what-the-heck-is-ChatOps.ogg
ogg_length: 103.1
tags:
- Rackspace
- Fanatical Support
- AWS
- ChatOps
-
hosts:
- albush
- drewcox
guests:
- martinb3
---

<!--more-->

## Highlights

- What is ChatOps? [(5:14)](https://youtu.be/uEVZiuiaQaw?t=5m14s)
- Working remote [(9:15)](https://youtu.be/uEVZiuiaQaw?t=9m15s)
- Synchronizing communications/transparency [(14:30)](https://youtu.be/uEVZiuiaQaw?t=14m30s)
- Standardizing procedures through ChatOps [(18:19)](https://youtu.be/uEVZiuiaQaw?t=18m19s)
- Contingency plans [(23:22)](https://youtu.be/uEVZiuiaQaw?t=23m22s)
- Testing and ChatOps [(27:35)](https://youtu.be/uEVZiuiaQaw?t=27m35s)
- How to get started with ChatOps [(30:10)](https://youtu.be/uEVZiuiaQaw?t=30m10s)
- Monitoring/prioritizing information [(32:05)](https://youtu.be/uEVZiuiaQaw?t=32m05s)
- Prioritizing the people side of operations [(36:20)](https://youtu.be/uEVZiuiaQaw?t=36m20s)
- Fun with ChatOps [(42:34)](https://youtu.be/uEVZiuiaQaw?t=42m34s)
- ChatOps with Rackspace Fanatical AWS [(49:48)](https://youtu.be/uEVZiuiaQaw?t=49m48s)

## Additional Advice from martinb3

Here are some additional tips and tricks straight from our guest, Martin Smith.

### How do I start?

Make it iterative! Just watch out for the pitfalls in final wisdom section below.

#### Software for chatops

Pick a language you will actually use, not just a hip language or fad.

- [Hubot][1]: GitHub’s bot written in CoffeeScript and Node.js
- [Lita][2]: Written in Ruby
- [Err][3]: Written in Python

#### Three steps to Getting Started

1. Get API driven. Software is eating the world. You need everything to have an API.
1. Pick _something_ and deploy it. It can be serverless, less on your monitoring server, etc.
1. Implement one action. Even if it's just to squelch the monitoring or the bot in general. Anything.

Or make it fun -- SlackAttack! Engagement at an all time high.  

<!--- BTW, Alan has won the last three Slack Attack competitions in a row. Just saying. --->


#### Final wisdom

1. Bots not required. Start with integrations! Not the full power, but it's a huge step, even just webhooks.
1. Invest up front. Don't think of ChatOps as an add-on. Make it your control plane.
1. Consolidate your control plane -- don't just map existing systems to chat.
1. Bots are a conversation: Make threads! Make your bot tell *YOU* when something is wrong.

## Links & shoutouts

- [ChefConf 2016][4] in Austin in July. Martin will be there, and would love to talk about FAWS & automation.
- [New Relic Blog: To Boost DevOps, Try ChatOps][5]
- [VictorOps: ChatOps Toolkit][6] - Including "ChatOps for Dummies" (requires email address...)
- [Pager Duty: So, What is ChatOps? And How do I Get Started?][7]


[1]: https://hubot.github.com/
[2]: https://www.lita.io/
[3]: http://errbot.net/
[4]: https://chefconf.chef.io/
[5]: https://blog.newrelic.com/2015/08/18/chatops/
[6]: https://victorops.com/chatops/
[7]: https://www.pagerduty.com/blog/what-is-chatops/

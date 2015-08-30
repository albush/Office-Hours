+++

Title = "Hanging out with Justin Phelps"
Date = "2015-08-11"
author = "Alan Bush"
number = "109"
duration = "50:01"
length = "36,010,736"
mp3 = "http://drops.albush.com/Racker%20Spotlight%20-%20Ansible%20Certified%20Engineer%20Justin%20Phelps.mp3"
ogg = "http://drops.albush.com/Racker%20Spotlight%20-%20Ansible%20Certified%20Engineer%20Justin%20Phelps.ogg"
youtube_id = "t384JnmvcuQ"
summary = "Justin Phelps is one of the first two people to earn the Ansible Certified Engineer Award. He's our guest on our Rackspace Office Hours Hangout."
tags = [ "Ansible", "GitHub", "Static Websites", ]

+++

Last week's hangout featured a spotlight on Racker Justin Phelps. Justin is a 3 and a half year Racker working in our DevOps Engineering teams. He was one of the first 40 people certified as a SaltStack Engineer, and just this last week earned his Certified Ansible Engineer award.

We took the time to ask Justin about Ansible, how it can help our customers, and where they can get started with Ansible. We also spent some time talking about creating and hosting static websites, and how to incorporate those into a larger application design.

I had a hard time choosing highlights this week; I could pretty much recommend the entire episode. I have a few links to highlights in the sections below, and the entire video is embedded at the end of the blog post. I hope you enjoy watching as much as I enjoyed hosting.

{{< audio >}}

{{< youtube >}}

## Ansible's simplicity and consistency

One of Justin's favorite aspects of Ansible is the simplicity. In this clip, Justin describes how easy it is to [get started with Ansible](https://youtu.be/t384JnmvcuQ?t=4m16s). A bit later, Justin and I chatted about how he uses Ansible in his own projects to achieve a [consistent environment](https://youtu.be/t384JnmvcuQ?t=8m15s). Finally, we talked about using images vs configuration management to build new servers. [Justin recommends](https://youtu.be/t384JnmvcuQ?t=9m21s) using configuration management in your development environment, then creating a stable image from that dev environment once you push to production.

## Ansible vs other configuration management solutions

Just like pitting two colas, or [text editors](http://www.rackspace.com/blog/text-editor-madness-bracket-vote-for-your-favorite/) against each other, configuration management solutions are often matters of personal preference and project use case. Justin gives a good description of the [pros and cons of Ansible](https://youtu.be/t384JnmvcuQ?t=12m25s) and other configuration management systems.

## Getting started with Ansible

Justin had a few tips for [getting started with Ansible](https://youtu.be/t384JnmvcuQ?t=19m17s). His first suggestion is to just start playing with Ansible. They have a great [getting started section](http://www.ansible.com/resources) in their documentation, including a very easy to follow video. He also recommends [starting off with automating the installation of packages and services](https://youtu.be/t384JnmvcuQ?t=22m34s). Especially for common web tools like Apache and PHP, the modules for these tools are very useful. Another good use of Ansible with a high return on time investment is pushing [security updates to multiple nodes](https://youtu.be/t384JnmvcuQ?t=25m19s) in your environment, especially when using a dynamic inventory.

## Static websites

We finished our conversation with a chat about using static (html, css, javascript only) web content to host simple blogs, or even as a part of a larger web application. [Justin hosts his own blog](https://youtu.be/t384JnmvcuQ?t=30m58s) on [Rackspace Cloud Files](http://www.rackspace.com/en-us/cloud/files), and uses some of the same DevOps principles he uses with customers to help automate the creation and deployment of his blog. That process has undergone some [iteration](https://youtu.be/t384JnmvcuQ?t=33m35s), which helped him to improve the automation.

Finally, we discussed how developers can include [static sites as a failover provision](https://youtu.be/t384JnmvcuQ?t=40m13s) within more dynamic web applications - the "circuit breaker pattern."

This episode is just packed full of great information, I recommend watching the whole video below.
Join us next week for our hangout TBD.

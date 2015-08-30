+++

author = "Alan Bush"
date = "2015-08-18T13:49:24-05:00"
number = "110"
duration = "54:56"
length = "39,556,388"
mp3 = "http://drops.albush.com/Windows%20Development%20with%20Rackspace%20Developer%20Don%20Schenck.mp3"
ogg = "http://drops.albush.com/Windows%20Development%20with%20Rackspace%20Developer%20Don%20Schenck.ogg"
summary = "We were joined by Rackspace Developer Don Schenck, to talk about his OpenStack automation utility for PowerShell: PoshStack. We also discussed how Don went about building PoshStack, and many of the lessons he learned while developing it."
tags = ["PowerShell", "PoshStack", "Open Source", "Development"]
title = "Lessons Learned in Opens Source Development"
youtube_id = "u7dlGhhQ48k"

+++

If you're curious how a Windows developer would go about starting an open source project, you aren't alone. In fact, our most recent Office Hours Hangout guest, Don Schecnk, found himself ready to start an open source project, and didn't know where to start. Fortunately for us, he documented his process, and spoke with us about it on our hangout. We didn't just cover the process, we also covered the product of his efforts, PoshStack, the PowerShell client for OpenStack. I'm including a few selected highlights, but the entire video can be viewed below. This was a fun interview - I know I learned a lot.

{{< audio >}}

{{< youtube >}}

## PoshStack

We started our conversation by speaking about PowerShell: what it is, why developers and administrators use it. Don related the [story of PoshStack came to be](https://youtu.be/u7dlGhhQ48k?t=3m29s). Don also shared a story of being able to [spin up dozens of servers](https://youtu.be/u7dlGhhQ48k?t=9m9s) for a training event. PoshStack made it possible to automate that deployment (and subsequent spin down). Another task for PoshStack is to work in conjunction with a configuration management solution, such as Ansible. Don himself worked with the creators of Ansible to build the Windows version of Ansible, and enjoys the [consistent environment](https://youtu.be/u7dlGhhQ48k?t=15m23s) he's able to reproduce with these tools. I really appreciated how this bit of the conversation was an extension of our Hangout last week, with [Ansible Certified Engineer Justin Phelps](http://www.rackspace.com/blog/ansible-certified-engineer-justin-phelps-video/).

## The experience of building an open source project

PoshStack is a great tool for anyone working extensively on Windows severs. It's also a great case study in building an open source project. Don is new to open source, so he decided to document his [experiences building an open source project?](https://youtu.be/u7dlGhhQ48k?t=19m15s), eventually turning his experience into a presentation given at various conferences. During our conversation, Don outlined several [lessons learned](https://youtu.be/u7dlGhhQ48k?t=21m20s), [tools used](https://youtu.be/u7dlGhhQ48k?t=29m11s), and things he would have [done differently](https://youtu.be/u7dlGhhQ48k?t=36m16s). I enjoyed chatting with Don on these points; they're great advice for anyone interested in getting started in open source, and probably even a few with plenty of experience. Among the things to try differently, I found his advice around slowing down to be especially helpful. Don recommended paying extra attention to the README file. That introduction to your project should give potential users and contributers a solid foundation to start with. Don recommended that [each README contain four characteristics](https://youtu.be/u7dlGhhQ48k?t=38m1s): A description, a list of prerequisites, complete installation instructions, and notes on how to contribute. Most importantly, Don encourages anyone interested in working on a project to [just get out there and start contributing](https://youtu.be/u7dlGhhQ48k?t=42m50s).

## rack cli

We wrapped up our conversation with a [discussion](https://youtu.be/u7dlGhhQ48k?t=43m38s) on the new [rack command line interface](https://developer.rackspace.com/blog/introducing-rack-global-cli/) for Windows, Mac OS X, and Linux. Rack cli is very easy to install and configure - I was able to get up and running in about 5 minutes. The interface allows the user to command Cloud Servers, Cloud Files, Cloud Block Storage, and Cloud Networks. Rack cli even [integrates well with PoshStack](https://youtu.be/u7dlGhhQ48k?t=45m13s); users can send rack cli output directly into PoshStack for further work.  

I truly enjoyed chatting with Don. [It's obvious that he loves his job](https://youtu.be/u7dlGhhQ48k?t=53m28s), and that love shows in the amazing tools he's built. You can view the entire discussion below, and don't forget to check out our next hangout, Thursday at 1pm.

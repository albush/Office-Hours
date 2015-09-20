---
Author: Alan Bush
Date: 2013-12-05
Title: Lessons Learned from the HealthCare.gov Relaunch With Rackspace CTO John Engates
duration: "01:03:15"
length: 60726960
ogg_length: 43161737
mp3: http://drops.albush.com/Lessons-Learned-form-the-HealthCaregov-Re-launch-With-Rackspace-CTO-John-Engates.mp3
number: "035"
ogg: http://drops.albush.com/Lessons-Learned-form-the-HealthCaregov-Re-launch-With-Rackspace-CTO-John-Engates.ogg
summary: ""
tags:
- healthcare.gov
- John Engates
- Rackspace
- ecommerce
youtube_id: dyNmIPJQRww
---

The main reason that Drew and I started the Cloud Office Hours Hangout was to help new and existing businesses learn how to leverage the power of the cloud. In particular, we try to provide information that can be helpful for businesses to scale their website or application for an onslaught of traffic. Preparation is the key to ensuring that a website is up and available.

One website learned the hard way about the importance for handling massive amounts of traffic. The launch of HealthCare.gov was lampooned widely throughout the media and call-in shows. The mistakes they made could have been avoided. Still, many companies fall into those same traps. The only difference was the amount of people that were affected and level of political scrutiny placed on this particular launch. To help sort through the mess, Rackspace CTO John Engates was invited to Washington, D.C. to [provide insights and expertise][1] on how to fix HealthCare.gov. We caught up with John after his trip to the White House and the website’s operations center. Here are some of the highlights with the [video of the entire Hangout][2] embedded below.

   [1]: http://www.rackspace.com/blog/more-transparency-helps-get-healthcare-gov-on-the-road-to-recovery/
   [2]: http://www.youtube.com/watch?v=dyNmIPJQRww&feature=share

{{< audio >}}

{{< youtube >}}

  * At the beginning of the conversation, John talked about the [experience of being invited to the Situation Room][3]. While this wasn’t part of the technical discussion, it sets the stage for what the trip was like.

   [3]: http://www.youtube.com/watch?v=dyNmIPJQRww&feature=share&t=13m9s

  * John mentioned that one way HealthCare.gov [differs from typical ecommerce applications is that consumers spent a longer time][4] on the site. While a typical ecommerce transaction might take two minutes to complete; users were spending upwards of an hour gathering a lot of information to complete their insurance transaction.

   [4]: http://www.youtube.com/watch?v=dyNmIPJQRww&feature=share&t=23m2s

  * One thing that was underestimated was [the complexity of running the HealthCare.gov site][5]. Ultimately, launching the site was only one of many tasks that were part of the Affordable Healthcare Act. On top of that, the hosting was only a portion of putting together the site and ultimately got placed towards the back of the pack.

   [5]: http://www.youtube.com/watch?v=dyNmIPJQRww&feature=share&t=24m58s

  * Another issue that arose was that there [was not proper load testing performed for HealthCare.gov][6]. This was predominately because there was not enough time to actually do testing. This underlines the importance of load testing your site to know exactly the amount of traffic that it can handle (which was a [topic of a previous Office Hours Hangout][7]).

   [6]: http://www.youtube.com/watch?v=dyNmIPJQRww&feature=share&t=25m44s
   [7]: http://www.youtube.com/watch?v=btdOLlD7C6Q

  * John talked about the [importance of placing the lightweight transactions upfront to prevent the site from going down][8]. Typically, the heavy computational part happens at the end of the process, where the person enters their credit card and personal information. HealthCare.gov inverted that funnel, placing tasks with heavy transactional load upfront (such as credit analysis for subsidies and username creation). This effectively bogged down the system as massive amounts of people flooded to the site.

   [8]: http://www.youtube.com/watch?v=btdOLlD7C6Q

  * Finally, John mentioned the importance of [considering the user experience when building a site][9]. With HealthCare.gov, the last step was for people to click a button that said something to the effect of, “Under penalty of perjury I guarantee all the information I put in is 100 percent accurate.” The cart abandonment rate was astronomical because people were scared to click the button due to fear of making a mistake inputting data along the way!

   [9]: http://www.youtube.com/watch?v=dyNmIPJQRww&feature=share&t=50m10s

# Cloud Architecture Trends: Cloud Office Hours Hangout Recap

The New Year begins with a fresh start and new ideas. If you happen to be working on a new application—or are redesigning one that you have in production—you may want to consider architecting your app to run on the cloud. To assist you with this, Rackers BK Box, Caleb Groom and Ryan Walker authored a white paper title " [Cloud Application Architecture Trends](http://www.rackspace.com/knowledge_center/whitepaper/cloud-application-architecture-trends)." They were guests on our weekly Cloud Office Hours Hangout  to discuss their paper, and dive a little deeper into these trends. I've embedded the entire video at the end of this post, but here are a few highlights from the show:

### New service layers are making it easier to control hardware through code.

The first trend identified is "Controlling Hardware Through Code," one of the early reasons technologists were excited about the potential of the cloud. As [Ryan Walker notes](http://youtu.be/2SvEewYysuA?t=12m8s), even though much of the underlying technology has been available for several years. Features like Rackspace Cloud Orchestration—built on OpenStack Heat—has eliminated a lot of the need for building DIY solutions. This enabled cloud app developers more free to focus on building their application, rather than tools to scale their application.

### "Everything has a purpose, and it's really good a that purpose."

Implementing services into your application was the second trend mentioned in the white paper. While Service Oriented Architecture (SOA) may have been around for a while, we think it's very important for cloud application architecture. We are also seeing a trend toward [smaller and smaller "micro-services" in applications](http://youtu.be/2SvEewYysuA?t=20m45s).

### Docker, Rocket and CoreOS: Containers are hot in 2015

"Docker" was probably the 2014 word of the year within most IT circles—but as John Engates noted in his [Cloud Predictions piece](http://www.rackspace.com/blog/cloud-predictions-for-2015/), containers will be big in 2015. Docker has helped bring existing container technology to a larger user base. With new container technology like Rocket launching (#sorrynotsorry for the pun) and the development of the CoreOS operating system, containers are poised to continue their dominance in 2015. Be sure to check out [Ryan and BK's favorite uses of Docker](http://youtu.be/2SvEewYysuA?t=35m5s) from the Hangout.

### Service discovery means less manual intervention

Service discovery, the final cloud architecture trend, is coming into its own this year. Essentially service discovery allows an application to grow without needing to pre-define all of the components that will potentially be part of the application. Watch us discuss the example [of confd and etcd](http://youtu.be/2SvEewYysuA?t=41m34s) working together to connect new application nodes (hardware controlled by code) to the right application micro services (service oriented architecture).

This Hangout had a lot of solid information and I encourage you to watch the whole show embedded below.

<video>

Be sure to sign up for our next Cloud Office Hours Hangout as we discuss a new WordPress training program developed by our friends at CloudU.

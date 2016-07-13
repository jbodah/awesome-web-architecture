# awesome-web-architecture
a list of links to help you make various important architectural decisions 

* [Awesome Web Architecture](#awesome)
  * [Overview/Layers](#overview)
  * [General](#general)
  * [Load Balancing Tier](#load-balancing-tier)
  * [Web Tier](#web-tier)
  * [App Tier](#app-tier)
  * [Cache Tier](#cache-tier)
  * [Database Tier](#database-tier)

## Overview

* [A Comprehensive Guide to Building a Scalable Web App on Amazon Web Services](https://www.airpair.com/aws/posts/building-a-scalable-web-app-on-amazon-web-services-p1) - Gives a great introduction to the roles of the various layers in web applications. Focuses on AWS, but most of the concepts generalize easy to open source technologies

## General

* [The Architecture of Open Source Applications](http://aosabook.org/en/index.html) - Explains the architecture of various high-profile open source technologies including load balancers, web servers, message queues, continuous integration, configuration management, and many more

* [7 Lessons Learned While Building Reddit To 270 Million Page Views A Month](http://highscalability.com/blog/2010/5/17/7-lessons-learned-while-building-reddit-to-270-million-page.html)

## Load Balancing Tier

## Web Tier

* [Web Servers vs. App Servers in Ruby; Performance Characteristics of Different Server Architectures](http://stackoverflow.com/questions/4113299/ruby-on-rails-server-options#answer-4113570) - Apache vs. Nginx, Apache vs. Passenger, Unicorn vs. Puma, threaded vs. forked, evented vs. non-evented; this StackOverflow answer has lots of great detail answering these questions
* [Scaling Ruby Apps to 1000 Requests per Minute](https://www.nateberkopec.com/2015/07/29/scaling-ruby-apps-to-1000-rpm.html) - A nice overview of various application server choices in the Ruby landscape

## App Tier

* [SOA Choices in Ruby](http://codeincomplete.com/posts/2014/9/1/soa/) - Pros and cons of various choices you'll need to make when building a SOA
* [Microservices vs. Service-Oriented Architecture](https://www.nginx.com/microservices-soa/) - Short ebook on the differences between SOA, microservices, and monoliths

## Cache Tier

## Database Tier

* [Designing Data-Intensive Applications](http://dataintensive.net/) - NoSQL is all the buzz. This book does a good job of explaining the design tradeoffs and feature differences between different database technologies to try and help you pick the right one for your application

## TODO
* Explain topics like high availability
* Security
 * HTTPS/SSL, private networks
* CI
* Backup & disaster recovery
* Deployment, config management
* Logging
* Monitoring and alerting

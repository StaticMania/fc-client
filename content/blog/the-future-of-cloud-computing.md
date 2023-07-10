---
title: " The Future of Cloud Computing"
date: 2023-05-25T20:18:07+06:00
featureImage: images/blog/clouds.jpg
author: David Young
authorThumb: images/author/david.png
---

### Cloud 1.0

At Joyent, my previous startup, we literally invented "cloud computing". We figured developers would appreciate the ability to purchase an "on-demand data center" in order to build web applications at scale without the enormous up-front infrastructure costs previously associated with datacenters.

This all seems like old-hat today, but at the time, in the early 2000s, we were felt like pioneers.

![blog image](/images/blog/single-blog-1.jpg)

### Centralization Sucks

What happened with cloud infrastructure is a story, in the technology universe, as old as time. All the innovative companies were bought up by those companies with large checkbooks and the concentration of offerings results in much higher prices, lower flexibility, and constant threats of "de-platforming" if the work done on the "big cloud" isn't "approved".

While it is still true the *initial* capex and opex of "Cloud 1.0" is a vast imrpovement over the old datacenter, over time the costs of "Cloud 1.0" balloon to be much more expensive. The APIs and services offered by these centralized clouds either don't keep up, change arbitrarily, represent significant lock-in, and don't quite do what the developer, the Customer wants/needs.

### Cloud 2.0

Federated Computer exists to work on a new model for cloud computing. We seek to build a distributted, point-to-point cloud that devolves control and innovation away from the "centralizer" back to the developer/Customer.

In order to do this, Federated Computer and industry partners working on this shift, must continue to work on a few challenges, among others.

1. We must standardize ways to enable distributed "devops" without access to the data/secrets on a machine. I believe there are a number of ways to begin to tackle this problem. At Federated Computer, we are using a technology invented at Google called a "macaroon" to allow fine-grained access to a system without being "root".

2. Communication between systems must be decoupled so that a Customer can decide to "subscribe" to "devops" services from Vendor A or Vendor B beased on their needs rather than the needs of the Vendor. Federated is using "Nostr" as a platform for systems communications. This allows for full privacy, full control for the Customer.

3. Ultimately, we must address abilities for Customers (end-users) to re-mix data principles from various "applications" into a single view for their own business. This is in *no way* a new idea. Earlier projects like Apple's "Cyberdog" attempted ways to publish/subscribe into a single "frame" allowing customers/developers to build for-purpose applications. Earlier web technologies like RSS began to explore these options, but were swept away by a rush to "control".

### The "Why" for Federated Computer

If you want to know the "why" of Federated Computer, this is it. We want to disrupt the enormous world-wide cloud-computing industry with a new paradigm for cloud that is free, inexpensive, and interoperable.

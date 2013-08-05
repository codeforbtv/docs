---
permalink: /local-cloud-proposal/
layout: default
title: Local Cloud for Burlington, Vermont (Proposal)
---

Local Cloud for Burlington, Vermont
===================================

Proposal

Contribute to this proposal by forking this document on GitHub:  
<https://github.com/codeforbtv>

This work is licensed under the Creative Commons Attribution 3.0 Unported license (<http://creativecommons.org/licenses/by/3.0/>).

### Summary

The local cloud collaborative proposes to colocate a server rack within Burlington Telecom's gigabit network. Using this server rack, the local cloud collaborative will make cloud computing resources available for non-commercial Internet applications with a focus on public, educational, and government access. With an uplink to Burlington Telecom's gigabit network, the local cloud will provide the infrastructure and platform on which to deploy next-generation Internet applications.

### Introduction

Burlington has one of a handful of gigabit networks in the country. These gigabit networks are islands of super-fast connectivity. It is only within (and to some extent between) these networks that the true potential of gigabit can currently be realized. Until the rest of the Internet catches up, the potential of Burlington Telecom's gigabit network can only be realized with applications deployed inside the network.

As a US Ignite Partner, the City of Burlington is looking to showcase next-generation Internet applications that provide transformative public benefit in the areas of education & workforce, energy, health, public safety, transportation, and advanced manufacturing. Applications focused on any of these areas could be hosted in the local cloud. Some examples of gigabit applications to be hosted in the local cloud include:

* **Lakecraft**: educational tool that engages youth and adults in science by gamifying the Lake Champlain Basin
* **School Juice**: application that will present the energy usage data of all area schools in a way that can be searched, accessed by API, and visualized
* **Live Streaming**: gigabit networks would allow for 1080p (or even 4K or 8K) streaming where most existing services are limited to 720p at best

One unique benefit of the local cloud would be in the area of public safety. The Vermont Digital Economy Project has found that communities with digitally connected non-governmental organizations are more resilient after natural disasters such as Tropical Storm Irene. Collaborating with the Vermont Digital Economy Project, volunteers working with Code for BTV, a Code for America Brigade, have built or improved websites for several non-governmental organizations and plan to work on many more of these websites. Having these websites hosted together in the local cloud would allow the Vermont Digital Economy Project to improve security, provide options for disaster response, share content between organizations, and more easily link the organizations together.

Many organizations lost a great deal of data during Tropical Storm Irene including donor lists, photos, and other information critical to their operations. In addition to web hosting, services such as cloud storage and cloud backup could be provided in the local cloud. Local cloud hosting, cloud storage, and cloud backup services available to Vermont’s non-governmental organizations (and possibly local governments) would make Vermont a leader in resilience to natural disasters.

### Approach

![cloud computing layers](http://upload.wikimedia.org/wikipedia/commons/3/3c/Cloud_computing_layers.png "cloud computing layers")

The first cloud computing resource provided by the local cloud will be an Infrastructure as a Service (IaaS) layer. This layer will most likely be managed by OpenStack, an open source software project backed by more than 200 companies. The IaaS layer will make it technically possible to run almost any application in the local cloud.

In the future, the local cloud may also host a Platform as a Service (PaaS) layer. The PaaS layer would most likely be managed by OpenShift Origin. This would make it easier to deploy applications written in common programming languages such as Node.js, Ruby, Python, PHP, Perl, or Java. OpenShift Origin also supports several common databases including MySQL, PostgreSQL, and MongoDB.

The IaaS and PaaS layers will allow developers to deploy Software as a Service (SaaS) applications in the local cloud. When the average person uses the word "cloud" they are typically referring to the SaaS layer of the cloud. A wide variety of innovative SaaS applications could be hosted in the local cloud with direct access to Burlington Telecom's gigabit network.

---
layout: default
title: Local Cloud for Burlington, Vermont
---

Local Cloud for Burlington, Vermont
===================================

Strategic Plan

Contribute to this strategic plan by forking this document on GitHub:  
<https://github.com/codeforbtv>

This work is licensed under the Creative Commons Attribution 3.0 Unported license (<http://creativecommons.org/licenses/by/3.0/>).

Background
----------

The Vermont Digital Economy Project has recognized that communities with digitally connected non-governmental organizations are more resilient after a disaster, such as Tropical Storm Irene. Collaborating with the Vermont Digital Economy Project, volunteers working with Code for BTV, a Code for America Brigade, have built or improved websites for five non-governmental organizations. These organization are Deerfield Valley Rescue, Bethel Food Shelf, Woodstock Job Bank, Woodstock Community Food Shelf, and Black River Academy Museum. These websites are helping to make Vermont communities more resilient.

Through this process two things became clear. One, there is no shortage of similar organizations in need of websites. Two, finding hosting for these websites is a challenge. The Vermont Digital Economy Project is able to procure free out-of-state hosting for each organization individually, but this hosting does not allow for the installation of WordPress multisite. WordPress multisite would make the websites much easier to create and maintain as a separate hosting environment would not have to be provisioned for each organization. Having all of the websites hosted together would allow the Vermont Digital Economy Project to improve security, provide options for disaster response, share content between organizations, and more easily link the organizations together.

Many of these same organizations lost a great deal of data during Tropical Storm Irene including donor lists, photos, and other information critical to their operations. In addition to web hosting, there is also a need for cloud storage and backup services. Local cloud hosting, cloud storage, and cloud backup services available to Vermont's non-governmental organizations (and possibly local governments) would make this state a leader in resilience to natural disasters.

Vision
------

Burlington has its own gigabit network that passes between 85% and 90% of the addresses in the city. In partnership with US Ignite, Burlington's gigabit network is a test bed for "[fostering] the creation of next-generation Internet applications that provide transformative public benefit."

Many of today's Internet applications are hosted in cloud computing environments. Cloud computing is a utility model that reduces costs by sharing resources and leveraging economies of scale. Many next-generation Internet applications will continue to choose the cloud computing model.

There are only a handful of gigabit networks throughout the country. Given the state of our Internet infrastructure at the national level, these gigabit networks are islands of super-fast connectivity. It is only within (and to some extent between) these networks that the true potential of gigabit can currently be realized.

Values
------

The local cloud initiative is being facilitated by Code for BTV, a Code for America Brigade, as well as community media organizations in Burlington. Both CCTV Center for Media & Democracy and Big Heavy World have discussed providing resources to this initiative. Code for BTV values participatory government and civic engagement. CCTV Center for Media & Democracy values free speech, public access, and open networks. Big Heavy World values the potential of Vermont's youth, self-worth, diversity, positivity, civic participation, independent thought, and community. All involved in this initiative value digital inclusion. Digital inclusion is social inclusion for the digital age, a proactive effort to mitigate the causes of social exclusion.

Mission
-------

The local cloud initiative will provide cloud computing resources for Internet applications that benefit the common good. While next-generation Internet applications are a natural fit, any public interest Internet application would be eligible to use the local cloud. The local cloud will provide access to the gigabit network, in the form of application hosting, to those who might not otherwise have access.

Strategy
--------

### What

The local cloud initiative aims to colocate a server rack within Burlington Telecom's network operations center. This would place the local cloud within the core of Burlington's gigabit network. This approach has several advantages:

* Redundant infrastructure (battery backup, dedicated generator, air conditioning)
* Higher throughput
* Lower latency

To make colocation practical, Burlington Telecom will likely need to limit physical access to the server rack. Redundant hardware and virtualization of computing resources can make it possible to limit physical access to scheduled maintenance windows. An agreement on emergency maintenance should be reached, but the infrastructure should be designed to avoid emergency maintenance as much as possible.

### Who

The local cloud should be administered by an organization with experience in managing access to communication media for the public interest. Public, educational, and governmental (PEG) access television has a long history of managing the public's access to non-commercial mass media. In Vermont, an organization that takes on this responsibility is referred to as an access management organization. Burlington's access management organizations are VCAM (public), RETN (education), and CCTV (government).

Television was the fifth form of mass media to be introduced (after print, recordings, cinema, and then radio). It took until the 1970s, twenty years after the introduction of television, for PEG access to start to take shape. After television, the Internet was the next form of mass media to be introduced emerging in the 1990s (the Internet existed long before the 1990s, but not as a form of mass media). Now, twenty years later, the local cloud could serve as a model for PEG access to the Internet as a form of mass media.

### How

![cloud computing layers](http://upload.wikimedia.org/wikipedia/commons/3/3c/Cloud_computing_layers.png "cloud computing layers")

Infrastructure as a Service (IaaS), the basic building block of cloud computing, will be the first cloud computing resource provided by the local cloud. This will be a set of virtual machines running on top of the physical hardware. Lakecraft, a Code for BTV project, could be a pilot application run on the IaaS layer. Lakecraft is an educational tool that engages youth and adults in science by gamifying the Lake Champlain Basin.

On top of the IaaS layer, one or more Platform as a Service (PaaS) offerings could be provided. Web hosting would be one example of a PaaS, but there are much more sophisticated forms of PaaS as well. A basic Linux, Apache, MySQL, and PHP (LAMP) PaaS could be provided to the Vermont Digital Economy Project for non-governmental organization web hosting.

Multiple Software as a Service (SaaS) applications could be hosted on top of each PaaS layer. SaaS is the part of the cloud with which most end users interact. WordPress multisite installs could be provided by Code for BTV and the Vermont Digital Economy Project to non-governmental organization "verticals" (e.g. rescue squads, food shelfs, job banks). A food shelf, for example, in need of a new website could have this website provisioned as part of the WordPress food shelf multisite install. Each WordPress multisite install (SaaS) would be installed on top of the LAMP PaaS which would itself be running on the IaaS layer.

While the local cloud initiative is focused on next-generation connectivity, local clouds could also be colocated at the core of other networks. For example, Comcast or FairPoint could provide a server rack for a local cloud within their networks. A local cloud would still have value, even on non-gigabit networks.

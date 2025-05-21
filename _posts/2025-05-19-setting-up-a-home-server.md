---
layout: post
author: M1lachite
title: Setting up a home server
comments: false
tags: [linux, server, selfhosted]
---
Hi and welcome to my blog's debut post! I plan to use this area as a sort of journal to record my experiences delving deeply into DevOps and cloud engineering.

I want to start this journey by sharing the first step in this post, which is setting up my server. Let's get right to the point!

At first, I was determined to use a Raspberry Pi 4b to create a miniature cloud-alike environment. However, a friend interrupted me before I could begin planning with an irresistible offer: a Dell OptiPlex 9020. Score!

![optiplex9020](/assets/images/setting-up-a-home-server/optiplex.jpg)

The only catch? There was no hard drive included. No big deal, I thought. I decided to purchase an SSD separately and go with the OptiPlex. Everything came together very quickly—a true "blink of an eye" job.

![assembling](/assets/images/setting-up-a-home-server/assembly.jpg)

I therefore had a fairly good server for learning at home after all of that. The specifications are as follows:

CPU: Intel i5-4570 (4 cores) @ 3.600GHz
RAM: 16 GB
SSD: GOODRAM CX400 512GB SATA3 550/500

Although this setup may not be a super-speed demon, it should be more than sufficient for my plans as a cost-effective homelab solution. This journey is all about turning this hardware into a personal cloud, and that's where the real fun starts!

I chose Ubuntu Server 24.04.2 LTS as the operating system. My primary cause? Canonical is the same company who develops Ubuntu and MicroStack, which I seek to use for this project. I'm hoping that this synergy will make everything go smoothly. 

As a Long Term Support release, this version, 24.04 LTS (Noble Numbat), is built for stability and will continue to receive updates for many years to come. I need that stability for a homelab so that I can lay out my cloud environment at a solid base.  

After the OS has been installed and the hardware is ready, setting up MicroStack is the next major task on my list. The most interesting part of creating my own cloud environment begins here, turning this simple machine into a versatile area for any of my cloud engineering experiments. In my next post, I'll go into more detail about that.

Thank you for being a part of this initial phase of my journey!
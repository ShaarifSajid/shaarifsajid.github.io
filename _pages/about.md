---
permalink: /
title: "Hi, welcome!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
[**I am actively looking for internship opportunities for summer 2021.**]

I am a PhD student at Georgia Tech, working with [Dr. Paul Pearce](https://www.cc.gatech.edu/~pearce/). My primary areas of interest belong to the domains of network security, privacy and Internet measurement. 

You can find my CV [here](http://shaarifsajid.github.io/files/Sajid_Shaarif_PhdCS_long.pdf). I am currently working on hunting for APT (advanced persistent threat) actors using large-scale Internet analysis tools.

Here are some of the projects I have previously worked on:

Studying Application Layer Aliveness
------
This project began as an extension of the paper ["Scanning the Internet for Liveness" (SIGCOMM CCR'18)](https://ccronline.sigcomm.org/wp-content/uploads/2018/05/sigcomm-ccr-final175.pdf), which focused on characterizing what network and transport layer aliveness means. Taking this to the next step, I worked on discovering and characterizing application layer aliveness, which we define as the condition when an IP speaks the probed application layer protocol. In contrast, an application-layer active IP is one which sends a payload (valid or invalid) for at least one application layer protocol. I worked on datasets of IPv4 scans to determine how much of IPv4 space is alive at the application layer. As the datasets are in the order of terabytes, this project allowed me to learn about handling big data and working with high performance computing clusters. My collaborators include [Dr. Sheher Bano (Novi, Facebook)](https://sheharbano.com/) and [Dr. Mobin Javed (LUMS)](http://web.lums.edu.pk/~mobin/), two authors of the initial paper.

S-Cube - Building a Support System for User Security
------
I worked with a team on building a browser extension which can help users keep track of their online behaviour by providing timed-shifted feedback. We hypothesized that delayed feedback can help users significantly improve their online security decisions. Currently, our extension can detect malicious websites, detect and store instances of password reuse, measure password strength, and identify cases when users (unsuspectingly) give out their PII. A poster regarding this project was presented at USENIX Security '18. You can take a look at the poster in the [publications](https://shaarifsajid.github.io/publications/) section.

Regionalism - Exploring Internet Censorship
------
This project was done through a collaboration between [International Computer Science Institute (ICSI, Berkeley)](https://www.icsi.berkeley.edu/icsi/) and LUMS, and explores the phenomenon of server-side blocking, where website unavailability is due to the server rather than due to state/ISP censorship. One of the major challenges we faced was to verify that the blocking was indeed server-side, and not done by a middlebox. This led us to use and analyze traceroutes. Another challenge we faced was to find and characterize the types of server-side blocking, which include blocking due to geographical location or blocking due to abuse. For this, I focused on websites hosted on Cloudflare, and designed, collected and analyzed web-crawls from different vantage points done on these websites. We found signicant evidence that countries, indeed, do experience regionalism. This resulted in a published research [paper](https://www.usenix.org/system/files/conference/foci18/foci18-paper-tschantz.pdf).

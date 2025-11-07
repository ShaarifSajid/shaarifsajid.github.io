---
permalink: /
title: "Hi, welcome!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
--- 
I’m a Software Engineer at [Corpay](https://www.corpay.com/), where I work on backend development, system integrations, and API-driven platforms in the airline lodging space. I graduated from Georgia Tech with an MS in Computer Science focused on computing systems and network security, and previously completed my BS in Computer Science at LUMS.

In the past, I have actively worked on several academic research projects — here are some of them:

---

## Studying Application Layer Aliveness

This project began as an extension of the paper ["Scanning the Internet for Liveness" (SIGCOMM CCR '18)](https://ccronline.sigcomm.org/wp-content/uploads/2018/05/sigcomm-ccr-final175.pdf), which focused on characterizing network- and transport-layer aliveness. Taking this a step further, I worked on discovering and characterizing **application-layer aliveness**, which we define as the condition where an IP address speaks the probed application-layer protocol. In contrast, an *application-layer active* IP is one that sends some payload (valid or invalid) for at least one application-layer protocol.

I worked on terabyte-scale IPv4 scan datasets to determine how much of the IPv4 space is alive at the application layer. Handling such large datasets taught me about distributed processing, high-performance computing clusters, and big data engineering. My collaborators included Dr. Shehar Bano (Novi/Facebook) and [Dr. Mobin Javed (LUMS)](http://web.lums.edu.pk/~mobin/), two authors of the original paper.

---

## S-Cube — Building a Support System for User Security

I collaborated on building a browser extension that provides **time-shifted feedback** to help users improve their online security behavior. We hypothesized that delayed feedback can significantly improve user decision-making around online safety.

Our extension can detect malicious websites, detect and store instances of password reuse, measure password strength, and identify cases where users unknowingly reveal their PII. A poster describing this project was presented at **USENIX Security '18**, which you can view in the [publications](https://shaarifsajid.github.io/publications/) section.

---

## Regionalism — Exploring Internet Censorship

This project was a collaboration between the [International Computer Science Institute (ICSI, Berkeley)](https://www.icsi.berkeley.edu/icsi/) and LUMS, exploring the phenomenon of **server-side blocking** — situations where websites are unavailable due to server policies, rather than state or ISP censorship.

A major challenge was confirming that the blocking was server-side rather than caused by a middlebox. This required extensive traceroute analysis. Another challenge was characterizing **types of server-side blocking**, such as geographic blocking or abuse-based blocking.

For this work, I focused on websites hosted on Cloudflare, designing, collecting, and analyzing multi-vantage-point web crawls. We found significant evidence that countries do experience regionalism. This resulted in a published [research paper](https://www.usenix.org/system/files/conference/foci18/foci18-paper-tschantz.pdf).


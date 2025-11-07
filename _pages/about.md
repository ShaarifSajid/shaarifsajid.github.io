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

Below are some academic and technical projects I've worked on over the years:

---

## BrewMate — V60 Multi-Recipe Timer (React + Tailwind) [2025]
**BrewMate** is a mobile-first V60 pour-over coffee timer built with React and Tailwind, designed for precision brewing and accessibility. It supports multiple well-known recipes (Matt Winton, Tetsu Kasuya, James Hoffmann) and features a pour-based running weight system, step-by-step guidance, and iOS-friendly audio cues. The design places strong emphasis on UX, accessibility, and predictable state-machine behavior.

**Key contributions:**
- Implemented multiple recipe flows with instant target updates per pour  
- Built a conic-gradient progress ring, step cards, and polished mobile UI  
- Ensured WCAG-AA contrast, ≥44px tap targets, and responsive layouts  

## Studying Application Layer Aliveness [2019]
I explored the concept of **application-layer aliveness**, extending earlier work on network/transport-layer liveness from the SIGCOMM CCR '18 paper ["Scanning the Internet for Liveness"](https://ccronline.sigcomm.org/wp-content/uploads/2018/05/sigcomm-ccr-final175.pdf). This involved determining when an IP address actively speaks the probed application-layer protocol, using large-scale IPv4 scan datasets. The project required working with terabytes of data, distributed processing, and high-performance computing clusters. I collaborated with Dr. Shehar Bano (Novi/Facebook) and [Dr. Mobin Javed (LUMS)](http://web.lums.edu.pk/~mobin/), two authors of the original study.

**Key contributions:**
- Designed methods to detect application-layer aliveness at Internet scale  
- Processed terabyte-scale IPv4 scans using distributed compute clusters  
- Characterized global patterns of application-layer activity  

---

## S-Cube — Building a Support System for User Security [2019]
S-Cube is a browser extension designed to provide **time-shifted feedback** to help users make safer security decisions online. It monitors password reuse, PII exposure, password strength, and interactions with malicious websites. Our hypothesis was that delayed feedback, rather than real-time alerts, would improve long-term user behavior. This work was presented as a poster at **USENIX Security '18**, available in the [publications](https://shaarifsajid.github.io/publications/) section.

**Key contributions:**
- Implemented detectors for password reuse, PII exposure, and malicious sites  
- Designed time-shifted feedback mechanisms based on user behavior  
- Built a cross-browser extension and contributed to study design  

---

## Regionalism — Exploring Internet Censorship [2018]
In collaboration with the [International Computer Science Institute (ICSI, Berkeley)](https://www.icsi.berkeley.edu/icsi/) and LUMS, this project investigated **server-side blocking**, where website inaccessibility is caused by servers rather than government or ISP censorship. We combined traceroute analysis with multi-vantage-point web crawls to distinguish server-side filtering from middlebox interference. The study focused heavily on Cloudflare-hosted websites and revealed regional access disparities.

This resulted in a published [research paper](https://www.usenix.org/system/files/conference/foci18/foci18-paper-tschantz.pdf).

**Key contributions:**
- Designed and executed multi-region web crawls  
- Analyzed traceroutes to differentiate server- vs. network-level blocking  
- Identified global patterns and types of server-side censorship  

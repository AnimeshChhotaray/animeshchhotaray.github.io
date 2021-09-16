---
permalink: /
title: "whoami"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student at FICS Research, University of Florida (USA), advised by Dr. Thomas Shrimpton. I hold an MS in Computer Science from University of Florida, and a BTech in Computer Science from NIT Rourkela (India). After my BTech, I worked as an engineer for Samung Research Institute, Noida for two years followed by a two year teaching stint at KIIT, Bhubaneswar (my hometown). At Samsung, my work involved understanding the working of various FM drivers (e.g., Marvell, CSR) and solving bugs along with working on code optimization and stabilization. At KIIT, I taught  undergraduate students subjects like Programming in C, Computer Security, etc.

My research lies at the intersection of Cryptography and Hardware Security. In particular, I am interested in analysing security problems such as intellectual-property theft and counterfeiting, in the integrated-circuit supply chain using principles of modern cryptography.

Life outside work and research: I love sports (tennis, table tennis/ping pong and cricket), write poems and songs occasionally, and like cooking (of course, eating too).

## More about my research
A counterfeit electronic component is an electronic part that deviates from a legitimate part in terms of ownership, specification, functionality and performance. Production of counterfeit chips is a longstanding problem that remains on the rise. There has been a reported increase in counterfeit parts by 25% every year since 2001 resulting in economic losses (reported as high as $169B). Considering the scale and impact of the counterfeit market, there is a need of designing techniques that prevent counterfeiting in every stage of the integrated-circuit supply chain. Researchers have been making significant efforts to provide solutions using cryptography. But, a lack of formal treatment in terms of modern cryptography leaves gaping holes in the existing solutions. My research is aimed at closing some of these holes in a systematic and principled way.

In my CCS'17 paper ["Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property"](https://acmccs.github.io/papers/p1533-chhotarayA.pdf), we found weaknesses in the IEEE P1735 standard that leads to efficient recovery of cryptographic keys that are used by owners of electronic-circuit designs aka IP authors to enclose their circuit-design IP in a digital envelope in order to protect their IP from other adversarial IP authors in the design phase.

In my IEEE S&P'22 paper ["Hardening Circuit Design IP Against Reverse-Engineering Attacks"](https://eprint.iacr.org/2021/456.pdf), we gave provable-security foundations for design-hiding schemes that are used by IP authors to prevent adversarial foundries from learning the functionality of their circuit design, and also contructed a design-hiding scheme that is provably-secure. Paper: https://eprint.iacr.org/2021/456.pdf

## Research (Lead)
- IEEE S&P'22: Hardening Circuit Design IP Against Reverse-Engineering Attacks [[Paper]](https://eprint.iacr.org/2021/456.pdf)
- CCS'17: Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property [[Paper]](https://acmccs.github.io/papers/p1533-chhotarayA.pdf)

## Research (Support)
- CODASPY'21: Brittle Features of Device Authentication (Second author) [[Paper]](https://dl.acm.org/doi/abs/10.1145/3422337.3447842)

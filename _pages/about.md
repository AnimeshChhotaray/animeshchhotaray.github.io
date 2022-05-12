---
permalink: /
title: "whoami"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate at FICS Research, University of Florida (USA), advised by Dr. Thomas Shrimpton. I hold an MS in Computer Science from University of Florida, and a BTech in Computer Science from NIT Rourkela (India). After my BTech, I worked as an engineer for Samung Research Institute, Noida for two years followed by a two year teaching stint at KIIT, Bhubaneswar (my hometown). At Samsung, my work involved understanding the working of various FM drivers (e.g., Marvell, CSR) and solving bugs along with working on code optimization and stabilization. At KIIT, I taught  undergraduate students Programming in C, Computer Security.

My research lies at the intersection of Cryptography and Hardware Security. In particular, I am interested in analysing security problems such as intellectual-property theft and counterfeiting, in the integrated-circuit supply chain using principles of modern cryptography.

Life outside work and research: I love sports (tennis, table tennis/ping pong and cricket), write poems and songs occasionally, and like cooking (of course, eating too).

## More about my research
The modern multi-billion-dollar integrated-circuit supply chain is global and distributed as different entities come together to produce a packaged integrated circuit. Developers of these integrated circuits or IP authors as they are otherwise known, spend lots of time, money and effort to come up with an efficient design of an integrated circuit. Therefore, IC designs are considered as intellectual properties of IP authors, and security mechanisms are needed to prevent adversarial entities in the supply chain from stealing the circuit IPs. In my research, I use principles of modern cryptography to develop provably-secure defenses against IP theft.

<!-- A counterfeit electronic component is an electronic part that deviates from a legitimate part in terms of ownership, specification, functionality and performance. Production of counterfeit chips is a longstanding problem that remains on the rise. Economic loss due to counterfeiting has been reported as high as $169 billion. Considering the scale and impact of the counterfeit market, there is a need of designing techniques that prevent counterfeiting in every stage of the integrated-circuit supply chain. Researchers have been making significant efforts to provide solutions using cryptography. But, a lack of formal treatment in terms of modern cryptography leaves gaping holes in the existing solutions. My research is aimed at closing some of these holes (and finding new holes, if any) in a systematic and principled way.  -->

In my CCS'17 paper ["Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property"](https://acmccs.github.io/papers/p1533-chhotarayA.pdf), my co-authors (Adib Nahiyan, Dr. Domenic Forte, Dr. Thomas Shrimpton) and I found weaknesses in the IEEE P1735 standard that leads to efficient recovery of cryptographic keys that are used by owners of electronic-circuit designs aka IP authors to enclose their circuit-design IP in a digital envelope in order to protect their IP from other adversarial IP authors in the design phase.

In my IEEE S&P'22 paper ["Hardening Circuit Design IP Against Reverse-Engineering Attacks"](https://eprint.iacr.org/2021/456.pdf), my co-author (Dr. Thomas Shrimpton) and I gave provable-security foundations for design-hiding schemes that are used by IP authors to prevent adversarial foundries from learning the functionality of their circuit design, contructed a design-hiding scheme that is provably-secure. Paper: https://eprint.iacr.org/2021/456.pdf

## Research (Lead)
- IEEE S&P'22: Hardening Circuit Design IP Against Reverse-Engineering Attacks [[Paper]](https://eprint.iacr.org/2021/456.pdf)
- CCS'17: Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property [[Paper]](https://acmccs.github.io/papers/p1533-chhotarayA.pdf)

## Research (Support)
- CODASPY'21: Brittle Features of Device Authentication (Second author) [[Paper]](https://dl.acm.org/doi/abs/10.1145/3422337.3447842)

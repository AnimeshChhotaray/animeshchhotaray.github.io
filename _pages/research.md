---
layout: archive
title: "IC Supply Chain Security"
permalink: /paper-summaries/
author_profile: true
redirect_from:
  - /paper-summaries
  - /research
---

The modern multi-billion-dollar integrated-circuit supply chain is global and distributed as different entities come together to produce a packaged integrated circuit. Developers of these integrated circuits or IP authors as they are otherwise known, spend lots of time, money and effort to come up with an efficient design of an integrated circuit. Therefore, IC designs are considered as intellectual properties of IP authors, and security mechanisms are needed to prevent adversarial entities in the supply chain from stealing the circuit IPs. In my research, I use principles of modern cryptography to develop provably-secure defenses against IP theft.

<!-- A counterfeit electronic component is an electronic part that deviates from a legitimate part in terms of ownership, specification, functionality and performance. Production of counterfeit chips is a longstanding problem that remains on the rise. Economic loss due to counterfeiting has been reported as high as $169 billion. Considering the scale and impact of the counterfeit market, there is a need of designing techniques that prevent counterfeiting in every stage of the integrated-circuit supply chain. Researchers have been making significant efforts to provide solutions using cryptography. But, a lack of formal treatment in terms of modern cryptography leaves gaping holes in the existing solutions. My research is aimed at closing some of these holes (and finding new holes, if any) in a systematic and principled way.  -->

<!--In my CCS'17 paper ["Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property"](https://acmccs.github.io/papers/p1533-chhotarayA.pdf), my co-authors (Adib Nahiyan, Dr. Domenic Forte, Dr. Thomas Shrimpton) and I found weaknesses in the IEEE P1735 standard that leads to efficient recovery of  plaintext circuit-design IP by  exploiting error messages that electronic-design and automation tools output during synthesis of encrypted circuit-design IPs. This work resulted in [7 Common Vulnerabilities and Exposures (CVE) entries in the Vulnerability Notes Database](http://www.kb.cert.org/vuls/id/739007) and was featured in [The Register](https://www.theregister.co.uk/2017/11/07/ieee_p1735_chip_design_insecurity/), [threatpost](https://threatpost.com/us-cert-warns-of-crypto-bugs-in-ieee-standard/128784/), [The Hacker News](https://thehackernews.com/2017/11/ieee-p1735-ip-encryption.html), and other cybersecurity news publications. Note that the IEEE P1735 standard was aimed at protecting the circuit-design IP of IP authors from other adversarial IP authors in the design phase.

In my IEEE S&P'22 paper ["Hardening Circuit Design IP Against Reverse-Engineering Attacks"](https://eprint.iacr.org/2021/456.pdf), my co-author (Dr. Thomas Shrimpton) and I gave provable-security foundations for design-hiding (DH) schemes that are used by IP authors to protect their circuit-design IPs from  adversarial foundries. We gave the first DH scheme that provably hides combinational/stateless circuits against honest-but-curious adversaries that try to reverse-engineer the full functionality of the hidden circuit.-->

- IEEE S&P'22: Hardening Circuit Design IP Against Reverse-Engineering Attacks [[Paper]](https://eprint.iacr.org/2021/456.pdf): my co-author (Dr. Thomas Shrimpton) and I gave provable-security foundations for design-hiding (DH) schemes that are used by IP authors to protect their circuit-design IPs from  adversarial foundries. We gave the first DH scheme that provably hides combinational/stateless circuits against honest-but-curious adversaries that try to reverse-engineer the full functionality of the hidden circuit.

![Slide 1](https://animeshchhotaray.github.io/files/OaklandSlide1.jpeg)

![Slide 2](https://animeshchhotaray.github.io/files/OaklandSlide2.jpeg)

![Slide 3](https://animeshchhotaray.github.io/files/OaklandSlide3.jpeg)

- CCS'17: Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property [[Paper]](https://acmccs.github.io/papers/p1533-chhotarayA.pdf): my co-authors (Adib Nahiyan, Dr. Domenic Forte, Dr. Thomas Shrimpton) and I found weaknesses in the IEEE P1735 standard that leads to efficient recovery of  plaintext circuit-design IP by  exploiting error messages that electronic-design and automation tools output during synthesis of encrypted circuit-design IPs. This work resulted in [7 Common Vulnerabilities and Exposures (CVE) entries in the Vulnerability Notes Database](http://www.kb.cert.org/vuls/id/739007) and was featured in [The Register](https://www.theregister.co.uk/2017/11/07/ieee_p1735_chip_design_insecurity/), [threatpost](https://threatpost.com/us-cert-warns-of-crypto-bugs-in-ieee-standard/128784/), [The Hacker News](https://thehackernews.com/2017/11/ieee-p1735-ip-encryption.html), and other cybersecurity news publications. Note that the IEEE P1735 standard was aimed at protecting the circuit-design IP of IP authors from other adversarial IP authors in the design phase.

![Slide 1](https://animeshchhotaray.github.io/files/IEEE-P1735/Slide1.jpeg)

![Slide 2](https://animeshchhotaray.github.io/files/IEEE-P1735/Slide2.jpeg)

![Slide 3](https://animeshchhotaray.github.io/files/IEEE-P1735/Slide3.jpeg)

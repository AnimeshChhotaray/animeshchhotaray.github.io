---
layout: archive
title: "IC Supply Chain Security"
permalink: /research_IC/
author_profile: true
redirect_from:
  - /paper-summaries
  - /research
---

The modern multi-billion-dollar integrated-circuit supply chain is global and distributed, spanning design houses, foundries, and assembly facilities across many organizations and countries. Developing an efficient integrated-circuit design requires enormous investment of time, money, and engineering effort, making these designs valuable intellectual property. Yet the standards and practices meant to protect that IP throughout the supply chain are often assumed to be secure without rigorous scrutiny, and the benchmarks used to evaluate IP-hiding techniques are often assumed to be representative without being measured. This research applies principles of modern cryptography to uncover weaknesses in existing IP-protection standards, to measure how misleadingly easy commonly used obfuscation benchmarks actually are, and to build provably-secure, user-centric tools and defenses against IP theft and reverse-engineering.

<!-- A counterfeit electronic component is an electronic part that deviates from a legitimate part in terms of ownership, specification, functionality and performance. Production of counterfeit chips is a longstanding problem that remains on the rise. Economic loss due to counterfeiting has been reported as high as $169 billion. Considering the scale and impact of the counterfeit market, there is a need of designing techniques that prevent counterfeiting in every stage of the integrated-circuit supply chain. Researchers have been making significant efforts to provide solutions using cryptography. But, a lack of formal treatment in terms of modern cryptography leaves gaping holes in the existing solutions. My research is aimed at closing some of these holes (and finding new holes, if any) in a systematic and principled way.  -->

- **CHES'26: Bad Benchmarks and a Fourier-Analytic Framework for Characterizing the (Un)Hideability of Combinational-Logic Circuits**: This framework uses Fourier analysis to formally characterize whether a given combinational-logic circuit can be hidden at all, showing that certain circuit structures have mathematical properties that make them inherently resistant to obfuscation regardless of the hiding technique applied. This work also measured and exposed "bad benchmarks" — test circuits the research community had long used to evaluate hiding techniques that turn out to be misleadingly easy, meaning prior evaluations had overstated the strength of these defenses.

- **IEEE S&P'22: Hardening Circuit Design IP Against Reverse-Engineering Attacks [[Paper]](https://eprint.iacr.org/2021/456.pdf)**: This work gives provable-security foundations for design-hiding (DH) schemes that are used by IP authors to protect their circuit-design IPs from adversarial foundries, including the first DH scheme that provably hides combinational/stateless circuits against honest-but-curious adversaries that try to reverse-engineer the full functionality of the hidden circuit.

<!--
![Slide 1](https://animeshchhotaray.github.io/files/OaklandSlide1.jpeg)

![Slide 2](https://animeshchhotaray.github.io/files/OaklandSlide2.jpeg)

![Slide 3](https://animeshchhotaray.github.io/files/OaklandSlide3.jpeg)
-->

- **CCS'17: Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property [[Paper]](https://acmccs.github.io/papers/p1533-chhotarayA.pdf)**: This work uncovered weaknesses in the IEEE P1735 standard that lead to efficient recovery of plaintext circuit-design IP by exploiting error messages that electronic-design and automation tools output during synthesis of encrypted circuit-design IPs. This work resulted in [7 Common Vulnerabilities and Exposures (CVE) entries in the Vulnerability Notes Database](http://www.kb.cert.org/vuls/id/739007) and was featured in [The Register](https://www.theregister.co.uk/2017/11/07/ieee_p1735_chip_design_insecurity/), [threatpost](https://threatpost.com/us-cert-warns-of-crypto-bugs-in-ieee-standard/128784/), [The Hacker News](https://thehackernews.com/2017/11/ieee-p1735-ip-encryption.html), and other cybersecurity news publications. Note that the IEEE P1735 standard was aimed at protecting the circuit-design IP of IP authors from other adversarial IP authors in the design phase.

<!--
![Slide 1](https://animeshchhotaray.github.io/files/IEEE-P1735/Slide1.jpeg)

![Slide 2](https://animeshchhotaray.github.io/files/IEEE-P1735/Slide2.jpeg)

![Slide 3](https://animeshchhotaray.github.io/files/IEEE-P1735/Slide3.jpeg)
-->

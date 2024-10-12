---
permalink: /
title: "whoami (PhD @UF -> Research Scientist @GeorgiaTech)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- I am a PhD alum (advised by Dr. Thomas Shrimpton) of FICS Research, University of Florida (USA). I hold an MS in Computer Science from University of Florida, and a BTech in Computer Science from NIT Rourkela (India). After my BTech, I worked as an engineer for Samsung Research Institute, Noida for two years followed by a two year teaching stint at KIIT, Bhubaneswar (my hometown). At Samsung, my work involved understanding the working of various FM drivers (e.g., Marvell, CSR) and solving bugs along with working on code optimization and stabilization. At KIIT, I taught  undergraduate students Programming in C, Computer Security. -->

I am a cybersecurity researcher with a PhD (2023) and MS (2017) in Computer Science from the University of Florida. My research focus is on supply-chain security in different domains (integrated circuit, additive manufacturing aka 3D printing, cyber-physical systems). 
<!--After obtaining my Bachelors degree from NIT Rourkela (India), I worked as an engineer for Samsung Research Institute, Noida (India) for two years followed by a two year teaching stint at KIIT, Bhubaneswar (India). At Samsung, my work involved understanding the working of various FM drivers (e.g., Marvell, CSR) and solving bugs along with working on code optimization and stabilization. At KIIT, I taught  undergraduate students Programming in C, Computer Security. -->

<!-- Life outside work and research: I love sports (tennis, table tennis/ping pong and cricket), write poems and songs occasionally, and like cooking (of course, eating too).-->

## Research
- CCS'24: [Release the Hounds! Automated Inference and Empirical Security Evaluation of Field-Deployed PLCs using Active Network Data](https://www.sigsac.org/ccs/CCS2024/program/accepted-papers.html) (Second author). Featured in Georgia Tech (ECE) [news](https://ece.gatech.edu/news/2024/10/new-algorithm-identifies-increase-critical-infrastructure-security-vulnerabilities-0).
- IEEE S&P'22: Hardening Circuit Design IP Against Reverse-Engineering Attacks (First author) [[Paper]](https://eprint.iacr.org/2021/456.pdf)
- CODASPY'21: Brittle Features of Device Authentication (Second author) [[Paper]](https://dl.acm.org/doi/abs/10.1145/3422337.3447842)
- CCS'17: Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property (First author) [[Paper]](https://acmccs.github.io/papers/p1533-chhotarayA.pdf). Researach led to [7 CVEs](http://www.kb.cert.org/vuls/id/739007), and has also been featured in [The Register](https://www.theregister.co.uk/2017/11/07/ieee_p1735_chip_design_insecurity/), [threatpost](https://threatpost.com/us-cert-warns-of-crypto-bugs-in-ieee-standard/128784/), [The Hacker News](https://thehackernews.com/2017/11/ieee-p1735-ip-encryption.html), and other cybersecurity news publications.


## More about my research on IC Supply Chain Security
The modern multi-billion-dollar integrated-circuit supply chain is global and distributed as different entities come together to produce a packaged integrated circuit. Developers of these integrated circuits or IP authors as they are otherwise known, spend lots of time, money and effort to come up with an efficient design of an integrated circuit. Therefore, IC designs are considered as intellectual properties of IP authors, and security mechanisms are needed to prevent adversarial entities in the supply chain from stealing the circuit IPs. In my research, I use principles of modern cryptography to develop provably-secure defenses against IP theft.

<!-- A counterfeit electronic component is an electronic part that deviates from a legitimate part in terms of ownership, specification, functionality and performance. Production of counterfeit chips is a longstanding problem that remains on the rise. Economic loss due to counterfeiting has been reported as high as $169 billion. Considering the scale and impact of the counterfeit market, there is a need of designing techniques that prevent counterfeiting in every stage of the integrated-circuit supply chain. Researchers have been making significant efforts to provide solutions using cryptography. But, a lack of formal treatment in terms of modern cryptography leaves gaping holes in the existing solutions. My research is aimed at closing some of these holes (and finding new holes, if any) in a systematic and principled way.  -->

In my CCS'17 paper ["Standardizing Bad Cryptographic Practice - A teardown of the IEEE P1735 standard for protecting electronic-design intellectual property"](https://acmccs.github.io/papers/p1533-chhotarayA.pdf), my co-authors (Adib Nahiyan, Dr. Domenic Forte, Dr. Thomas Shrimpton) and I found weaknesses in the IEEE P1735 standard that leads to efficient recovery of  plaintext circuit-design IP by  exploiting error messages that electronic-design and automation tools output during synthesis of encrypted circuit-design IPs. This work resulted in [7 Common Vulnerabilities and Exposures (CVE) entries in the Vulnerability Notes Database](http://www.kb.cert.org/vuls/id/739007) and was featured in [The Register](https://www.theregister.co.uk/2017/11/07/ieee_p1735_chip_design_insecurity/), [threatpost](https://threatpost.com/us-cert-warns-of-crypto-bugs-in-ieee-standard/128784/), [The Hacker News](https://thehackernews.com/2017/11/ieee-p1735-ip-encryption.html), and other cybersecurity news publications. Note that the IEEE P1735 standard was aimed at protecting the circuit-design IP of IP authors from other adversarial IP authors in the design phase.

In my IEEE S&P'22 paper ["Hardening Circuit Design IP Against Reverse-Engineering Attacks"](https://eprint.iacr.org/2021/456.pdf), my co-author (Dr. Thomas Shrimpton) and I gave provable-security foundations for design-hiding (DH) schemes that are used by IP authors to protect their circuit-design IPs from  adversarial foundries. We gave the first DH scheme that provably hides combinational/stateless circuits against honest-but-curious adversaries that try to reverse-engineer the full functionality of the hidden circuit.

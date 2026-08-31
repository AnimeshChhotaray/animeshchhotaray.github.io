---
layout: archive
title: "Cyber-Physical Systems & Critical Infrastructure Security"
permalink: /research_CPS/
author_profile: true
redirect_from:
  - /research-cps
  - /critical-infrastructure
---

Critical infrastructure — the power grid, water treatment systems, manufacturing facilities, and maritime vessels — increasingly relies on networked, computerized control. These cyber-physical systems (CPS) were often built without security in mind, and when they are compromised, the consequences are physical: blackouts, halted production lines, or unsafe operating conditions. This research discovers vulnerabilities in these systems at scale, measures their real-world exposure, and develops techniques to make critical infrastructure more resilient to cyberattack.

- **HICSS'27: Analyzing the Cyber Resilience of Distribution Systems with Vulnerable Inverter-Based Resources** [[Paper](https://molzahn.github.io/pubs/ashebo_raymaker_talkington_asiamah_chhotaray_zonouz_molzahn-der_attacks.pdf)]: This work develops a cyber-physical attack framework in which an adversary manipulates compromised solar inverters to maximize voltage violations on a distribution feeder. Using mixed-integer optimization over a linearized power-flow model, validated against full AC power-flow simulation, the results show that compromising as little as 10–25% of strategically selected inverters can drive multiple buses into unsafe voltage conditions — highlighting the risk that rising distributed-solar penetration poses to grid stability.

<!--
- **Grid Trouble in Paradise: Uncovering Vulnerable Distributed Energy Resources and Their Grid-Level Risks** *(under review)*: This Internet-wide measurement study identifies tens of thousands of Internet-exposed distributed energy resources (DERs) — solar inverters, meters, and gateway controllers — many reachable without authentication. The study characterizes these exposures and connects them to concrete grid-level risk, motivating the attack-budget framework used in the companion HICSS'27 paper. https://eprint.iacr.org/2026/623 
-->

- **IMECE'26: CIE Methods for Modern Manufacturing** *(ASME International Mechanical Engineering Congress and Exposition, IMECE2026-192577)* [[Paper]()]: This paper applies Cyber-Informed Engineering (CIE) principles to manufacturing operations, outlining how security-by-design methods can be used to protect factories and industrial facilities from cyberattack.

- **ACM CCS'26: Batten the Hatches: Cybersecurity with Military Mariners** [[Paper]()]: This study examines the cybersecurity posture of military maritime systems, extending prior work on civilian mariners to a defense context and identifying practical gaps in how shipboard personnel understand and respond to cyber threats.

- **ACM CCS'25: One Video to Steal Them All: 3D-Printing IP Theft through Optical Side-Channels** [[Paper](https://arxiv.org/abs/2506.21897)]: This work demonstrates that the digital blueprint of a 3D-printed object can be reconstructed by an outside observer simply by recording the optical emissions produced by the printer head during operation, revealing a novel side-channel attack that requires no access to the printer's network or files. The findings motivated a follow-on AI-enabled digital-twin defense, now the basis of a provisional patent, for detecting tampering and IP theft in 3D-printing operations.

- **ACM CCS'25: A Sea of Cyber Threats: Maritime Cybersecurity from the Perspective of Mariners** [[Paper](https://arxiv.org/abs/2506.15842)]: This human-centered study surveys working mariners to understand the cybersecurity threats they encounter, their security awareness, and the practical barriers that prevent them from protecting shipboard systems — revealing gaps between engineering assumptions and real-world maritime operations.

- **ACM CCS'24: Release the Hounds! Automated Inference and Empirical Security Evaluation of Field-Deployed PLCs Using Active Network Data** [[Paper](https://faculty.cc.gatech.edu/~frankli/papers/PLCHound_CCS24.pdf)]: This work develops PLCHound, a technique for passively and safely fingerprinting Internet-connected Programmable Logic Controllers (PLCs) — the devices that control equipment at power substations, water treatment plants, and factories — without directly probing live infrastructure. PLCHound identified roughly 37x more exposed PLCs than existing scanning tools, and after affected organizations were notified, 34% of identified devices were taken offline within a month.

- **[IEEE P3528](https://standards.ieee.org/ieee/3528/11844/)**: Guide for Cyber Informed Engineering Curricula (IEEE Standards Working Group, in development): Contributes to the working group developing this international standard, which defines how educational institutions incorporate Cyber-Informed Engineering (CIE) principles into curricula worldwide.

- **Cyber Informed Engineering (CIE) Curriculum Guide** *(Idaho National Laboratory)* [[v2](https://www.osti.gov/biblio/3006953), [university adoption](https://www.osti.gov/biblio/2478666)]: This framework and resource guide, developed with Idaho National Laboratory and the Department of Energy, supports integrating security-by-design engineering principles into university engineering curricula nationwide.

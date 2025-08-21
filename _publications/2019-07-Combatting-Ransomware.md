---
title: "Combatting Ransomware Using Content Analysis and Complex File Events"
collection: publications
category: conferences
permalink: /publication/2019-07-Combatting-Ransomware
excerpt: 'A method to fight against ransomware encryption attacks using intelligent file processing.'
date: 2019-06-24
venue: '2019 10th IFIP International Conference on New Technologies, Mobility and Security (NTMS)'
paperurl: 'https://ieeexplore.ieee.org/document/8763851'
bibtexurl: files/MayL19.bib
citation: 'M. J. May and E. Laron, <u>Combating Ransomware using Content Analysis and Complex File Events</u>, in <i>2019 10th IFIP International Conference on New Technologies, Mobility and Security (NTMS)</i>, Canary Islands, Spain, 2019, pp. 1-5, doi: 10.1109/NTMS.2019.8763851.'
---

Crypto-ransomware are programs that encrypt files and demand payment for their release or decryption. A common tactic to combat ransomware is file monitoring for suspicious modifications and recovery from (automatically maintained) backups. We offer two techniques to improve the state of the art: the consideration of the file lifecycle and the use of content analysis. We consider the file lifecycle using complex events that allow us to better reflect the user's mental model (what the user thinks he is doing), leading to more intelligent file event processing. Content analysis using Apache Tika allows us to detect attacks by watching for suspicious content type changes. We implement both techniques in a tool (ARW) and prove its effectiveness against the $ucyLocker ransomware. Both techniques should be considered for integration into existing anti-ransomware tools to improve their effectiveness.

---
title: "WSEmail"
collection: publications
category: manuscripts
permalink: /publication/2019-WSEmail
excerpt: 'A revisiting of the WSEmail system after over a decade.  Includes more about applications and new performance metrics.'
date: 2020-01-21
venue: 'Service Oriented Computing and Applications '
bibtexurl: 'files/MayLG20.bib'
paperurl: 'https://link.springer.com/article/10.1007/s11761-019-00283-9'
citation: 'May, M.J., Lux, K.D. & Gunter, C.A. 2020. <u>WSEmail</u> in <i>Service Oriented Computing and Applications (SOCA)</i> <b>14M</b>, 5–17. https://doi.org/10.1007/s11761-019-00283-9'
---

Web services offer an opportunity to redesign a variety of older systems to exploit the advantages of a flexible, extensible, secure set of standards. In this work, we revisit WSEmail, a system proposed over 10 years ago to improve email by redesigning it as a family of web services. WSEmail offers an alternative vision of how instant messaging and email services could have evolved, offering security, extensibility, and openness in a distributed environment instead of the hardened walled gardens that today’s rich messaging systems have become. WSEmail’s architecture, especially its automatic plug-in download feature, allows for rich extensions without changing the base protocol or libraries. We demonstrate WSEmail’s flexibility using three business use cases: secure channel instant messaging, business workflows with routed forms, and on-demand attachments. Since increased flexibility often mitigates against security and performance, we designed WSEmail with security in mind and formally proved the security of one of its core protocols (on-demand attachments) using the TulaFale and ProVerif automated proof tools. We provide performance measurements for WSEmail functions in a prototype we implemented using .NET. Our experiments show a latency of about a quarter of a second per transaction under load.
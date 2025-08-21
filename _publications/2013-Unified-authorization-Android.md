---
title: "Towards Unified Authorization for Android"
collection: publications
category: conferences
permalink: /publication/2013-Unified-authorization-Android
excerpt: 'A model for better authorization of applications in Android.  Includes implementation and formal proof of correctness.'
date: 2013-02-27
venue: '5th International Conference on Engineering Secure Software and Systems'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-642-36563-8_4'
bibtexurl: files/MayB13.bib
citation: 'Michael J. May and Karthikeyan Bhargavan. 2013. <u>Towards unified authorization for android</u>. In <i>Proceedings of the 5th international conference on Engineering Secure Software and Systems (ESSoS 13)</i>. Springer-Verlag, Berlin, Heidelberg, 42–57. https://doi.org/10.1007/978-3-642-36563-8_4'
---

Android applications that manage sensitive data such as email and files downloaded from cloud storage services need to protect their data from malware installed on the phone. While prior security analyses have focused on protecting system data such as GPS locations from malware, not much attention has been given to the protection of application data. We show that many popular commercial applications incorrectly use Android authorization mechanisms leading to attacks that steal sensitive data. We argue that formal verification of application behaviors can reveal such errors and we present a formal model in ProVerif that accounts for a variety of Android authorization mechanisms and system services. We write models for four popular applications and analyze them with ProVerif to point out attacks. As a countermeasure, we propose Authzoid, a sample standalone application that lets applications define authorization policies and enforces them on their behalf.

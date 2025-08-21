---
title: "CEMDA: Detecting Android Complex File Events to Infer the User's Mental Model"
collection: publications
category: conferences
permalink: /publication/2022-CEMDA
excerpt: 'An extension of the theory of complex file events to the Android operating system.'
date: 2022-05-06
venue: '37th ACM/SIGAPP Symposium On Applied Computing (SAC 22)'
paperurl: 'https://dl.acm.org/doi/10.1145/3477314.3507009'
bibtexurl: files/MayCMS22.bib
citation: 'Michael J May, Yaakov Cohen, Hovav Menachem, and Yogev Swisa. <u>CEMDA: detecting android complex file events to infer the users mental model</u>. In <i>Proceedings of the 37th ACM/SIGAPP Symposium on Applied Computing (SAC 22)</i>. Association for Computing Machinery, New York, NY, USA, 2022. pp. 917–925. https://doi.org/10.1145/3477314.3507009'
---

People use smartphones to do many tasks: view email attachments, read social media posts, create and edit photographs, and forward files. The users perspective on actions performed when creating, viewing, and modifying files (her mental model) reflects the visible clicks and swipes performed. At the file system and OS, however, such actions are less clear. A single click can lead to a flurry of hundreds of file system reads and writes, system calls, and communication steps. While individual apps can use analytics to record in-app user actions, common patterns such as download-read-forward cross app boundaries and become difficult to discover. That lack leads to inefficiencies in on-device file management and backup.
To better enable apps and devices to discover the users mental model, we present CEMDA, an Android app that automatically detects the user's mental model by applying the theories of file lifecycle events and complex events. CEMDA detects 12 high level user stories in 4 categories of user actions (create, access, share, modify) while operating completely in user space and without OS modification. CEMDA successfully detects user actions in cross-app actions across popular messaging and productivity apps (e.g., WhatsApp, Adobe Reader) with 80%-100% success while consuming minimal battery and memory.
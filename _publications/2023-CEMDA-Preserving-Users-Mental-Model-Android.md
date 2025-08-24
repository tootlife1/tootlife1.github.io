---
title: "CEMDA: Preserving the User's Mental Model on Android Files Using Complex Events"
collection: publications
category: manuscripts
permalink: /publication/2023-CEMDA-Preserving-Users-Mental-Model-Android
excerpt: 'Applying the theory of file lifecycle analysis to apps in Android.  This work extends the foundational work on file lifecycle analysis from 2019 with many new rules and a novel rule-base engine for Android phones.'
date: 2023-02-10
venue: 'ACM SIGAPP Applied Computing Review'
paperurl: 'https://dl.acm.org/doi/10.1145/3584014.3584016'
bibtexurl: files/MayCMS23.bib
citation: "Michael J May, Yaakov Cohen, Hovav Menachem, and Yogev Swisa. 2023. <u>CEMDA: Preserving the User's Mental Model on Android Files Using Complex Events</u> in <i>SIGAPP Appl. Comput. Rev.</i> 22, 4 (December 2022), 24–36. https://doi.org/10.1145/3584014.3584016"
---

People use smartphones to do many tasks: view email attachments, read social media posts, create and edit photographs, and forward files. The user's perspective on actions performed when creating, viewing, and modifying files (her mental model) reflects the visible clicks and swipes performed. At the file system and OS, however, such actions are less clear. A single click can lead to a flurry of hundreds of file system reads and writes, system calls, and communication steps. While individual apps can use analytics to record in-app user actions, common patterns such as download-read-forward cross app boundaries and become difficult to discover. That lack leads to inefficiencies in on-device file management and backup.
To better enable apps and devices to discover the user's mental model, we present CEMDA, an Android app that automatically detects the user's mental model by applying the theories of file lifecycle events and complex events. CEMDA detects over 10 high level user stories in 4 categories of user actions (create, access, share, modify) while operating completely in user space and without OS modification. CEMDA successfully detects user actions in cross-app actions across popular messaging and productivity apps (e.g., WhatsApp, Adobe Reader) with 75%-100% success while consuming minimal battery and memory.
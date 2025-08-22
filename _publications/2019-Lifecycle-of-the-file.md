---
title: "On the Lifecycle of the File"
collection: publications
category: manuscripts
permalink: /publication/2019-Lifecycle-of-the-file
excerpt: 'A foundational exploration of files and their lifecycle with application to intelligent file processing.'
date: 2019-02-18
venue: 'ACM Transactions on Storage (TOS)'
bibtexurl: 'files/MayLZG19.bib'
paperurl: 'https://dl.acm.org/doi/10.1145/3295463'
citation: 'Michael J. May, Etamar Laron, Khalid Zoabi, and Havah Gerhardt. <u>On the Lifecycle of the File</u> in <i>ACM Trans. Storage</i> 15, 1, Article 1 (February 2019), 45 pages. https://doi.org/10.1145/3295463.'
---

Users and Operating Systems (OSs) have vastly different views of files. OSs use files to persist data and structured information. To accomplish this, OSs treat files as named collections of bytes managed in hierarchical file systems. Despite their critical role in computing, little attention is paid to the lifecycle of the file, the evolution of file contents, or the evolution of file metadata. In contrast, users have rich mental models of files: they group files into projects, send data repositories to others, work on documents over time, and stash them aside for future use. Current OSs and Revision Control Systems ignore such mental models, persisting a selective, manually designated history of revisions. Preserving the mental model allows applications to better match how users view their files, making file processing and archiving tools more effective. We propose two mechanisms that OSs can adopt to better preserve the mental model: File Lifecycle Events (FLEs) that record a file’s progression and Complex File Events (CFEs) that combine them into meaningful patterns. We present the Complex File Events Engine (CoFEE), which uses file system monitoring and an extensible rulebase (Drools) to detect FLEs and convert them into complex ones. CFEs are persisted in NoSQL stores for later querying.
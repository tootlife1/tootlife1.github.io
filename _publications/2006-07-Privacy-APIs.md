---
title: "Privacy APIs: Access Control Techniques to Analyze and Verify Legal Privacy Policies"
collection: publications
category: conferences
permalink: /publication/2006-07-Privacy-APIs
excerpt: 'An application of formal methods model checking to legal privacy policies.'
date: 2006-07-05
venue: '19th IEEE Computer Security Foundations Workshop (CSFW)'
slidesurl: #'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://repository.upenn.edu/handle/20.500.14332/6293'
bibtexurl: /files/MayGL06.bib
citation: 'M. J. May, C. A. Gunter and I. Lee, <u>Privacy APIs: access control techniques to analyze and verify legal privacy policies</u>, in <i>19th IEEE Computer Security Foundations Workshop (CSFW 2006)</i>, Venice, Italy, 2006, pp. 13 pp.-97, doi: 10.1109/CSFW.2006.24.'
---

There is a growing interest in establishing rules to regulate the privacy of citizens in the treatment of sensitive personal data such as medical and financial records. Such rules must be respected by software used in these sectors. The regulatory statements are somewhat informal and must be interpreted carefully in the software interface to private data. This paper describes techniques to formalize regulatory privacy rules and how to exploit this formalization to analyze the rules automatically. Our formalism, which we call privacy APIs, is an extension of access control matrix operations to include (1) operations for notification and logging and (2) constructs that ease the mapping between legal and formal language. We validate the expressive power of privacy APIs by encoding the 2000 and 2003 HIPAA consent rules in our system. This formalization is then encoded into Promela and we validate the usefulness of the formalism by using the SPIN model checker to verify properties that distinguish the two versions of HIPAA.

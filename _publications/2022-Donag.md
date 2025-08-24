---
title: "Donag: Generating Efficient Patches and Diffs for Compressed Archives"
collection: publications
category: manuscripts
permalink: /publication/2021-Donag
excerpt: 'A novel algorithm for differencing compressed archives based on file lifecycle analysis.  The algorithm produces diff files significantly smaller than existing differencing tools, enabling quick application of patches to compressed archives.'
date: 2022-09-21
venue: 'ACM Transactions on Storage'
bibtexurl: 'files/May22.bib'
paperurl: 'https://dl.acm.org/doi/10.1145/3507919'
citation: 'Michael J. May. 2022. <u>Donag: Generating Efficient Patches and Diffs for Compressed Archives</u> in <i>ACM Trans. Storage</i> 18, 3, Article 26 (August 2022), 41 pages. https://doi.org/10.1145/3507919.'
---

Differencing between compressed archives is a common task in file management and synchronization. Applications include source code distribution, application updates, and document synchronization. General purpose binary differencing tools can create and apply patches to compressed archives, but don’t consider the internal structure of the compressed archive or the file lifecycle. Therefore, they miss opportunities to save space based on the archive’s internal structure and metadata. To address the gap, we develop a content-aware, format independent theory for differencing on compressed archives and propose a canonical form and digest for compressed archives. Based on them, we present Donag, a content-aware differencing and patching algorithm that produces smaller patches than general purpose binary differencing tools on versioned archives by exploiting the compressed archives’ internal structure. Donag uses the VCDiff and BSDiff engines internally. We compare Donag’s patches to ones produced by bsdiff, xdelta3, and Delta++ on three classes of compressed archives: open-source code repositories, large and small applications, and office productivity documents (DOCX, XLSX, PPTX). Donag’s patches are typically 10% to 89% smaller than those produced by bsdiff, xdelta3, and Delta++, with reasonable memory overhead and throughput on commodity hardware. In the worst case, Donag’s patches are negligibly larger.
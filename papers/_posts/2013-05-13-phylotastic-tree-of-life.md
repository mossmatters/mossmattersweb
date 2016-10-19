---
layout: paper
title: "Phylotastic! Making Tree-of-Life Knowledge Accessible, Re-usable and Convenient"
year: "2013"
shortref: "Stoltzfus <i>et al.</i> 2013 <i>BMC Bioinf</i>"
nickname: 
journal: "BMC Bioinformatics"
volume: 14
issue: 1
pages: 158
authors: "Stoltzfus A, Lapp H, Matasci N, Deus H, Sidlauskas B, Zmasek CM, Vaidya G, Pontelli E, Cranston K, Vos R, Webb CO, Harmon LJ, Pirrung M, O'Meara B, Pennell MW, Mirarab S, Rosenberg MS, Balhoff JP, <b><u>Bik HM</u></b>, Heath T, Midford P, Brown JW, McTavish EJ, Sukumaran J, Westneat M, Alfaro ME, Steele A"
image: /assets/images/papers/default-paper.svg
pdf: /assets/pdfs/Stoltzfus-etal-2013-Phylotastic.pdf
pdflink:
github: 
<!-- pmid: 15644440
pmcid: PMC545518
f1000: http://f1000.com/prime/1030269
figshare:  -->
doi: 10.1186/1471-2105-14-158
category: paper
published: true
peerreview: true
review: false
tags: 
---
{% include JB/setup %}

# Abstract

<u>Background:</u> Scientists rarely reuse expert knowledge of phylogeny, in spite of years ofeffort to assemble a great “Tree of Life” (ToL). A notableexception involves the use of Phylomatic, which provides tools togenerate custom phylogenies from a large, pre-computed, expert phylogeny ofplant taxa. This suggests great potential for a more generalized systemthat, starting with a query consisting of a list of any known species, wouldrectify non-standard names, identify expert phylogenies containing theimplicated taxa, prune away unneeded parts, and supply branch lengths andannotations, resulting in a custom phylogeny suited to the user’sneeds. Such a system could become a sustainable community resource ifimplemented as a distributed system of loosely coupled parts that interactthrough clearly defined interfaces.

<u>Results:</u> With the aim of building such a “phylotastic” system,the NESCent Hackathons, Interoperability, Phylogenies (HIP) workinggroup recruited 2 dozen scientist-programmers to a weeklong programminghackathon in June 2012. During the hackathon (and a three-month follow-upperiod), 5 teams produced designs, implementations, documentation,presentations, and tests including: (1) a generalized scheme for integratingcomponents; (2) proof-of-concept pruners and controllers; (3) a meta-API fortaxonomic name resolution services; (4) a system for storing, finding, andretrieving phylogenies using semantic web technologies for data exchange,storage, and querying; (5) an innovative new service, DateLife.org,which synthesizes pre-computed, time-calibrated phylogenies to assign agesto nodes; and (6) demonstration projects. These outcomes are accessible viaa public code repository (GitHub.com), a website(http://www.phylotastic.org), and a server image.

<u>Conclusions:</u> Approximately 9 person-months of effort (centered on a software developmenthackathon) resulted in the design and implementation of proof-of-conceptsoftware for 4 core phylotastic components, 3 controllers, and 3 end-userdemonstration tools. While these products have substantial limitations, theysuggest considerable potential for a distributed system that makesphylogenetic knowledge readily accessible in computable form. Widespread useof phylotastic systems will create an electronic marketplace for sharingphylogenetic knowledge that will spur innovation in other areas of the ToLenterprise, such as annotation of sources and methods and third-partymethods of quality assessment.
---
layout: project
title: "Phinch"
tagline: "A data visualiztion framework for -Omic data"
handle: data-viz
image: /assets/themes/lab/images/banner/phinch.png
category: project
tags: [Phinch, software, data visualization, microbial ecology]
---
{% include JB/setup %}

## Phinch - [http://phinch.org]

<img src="/assets/images/projects/phinch-gallery.png" alt="phinch" class="inline" width="500">

Phinch is an interactive, browser-based visualization framework that facilitates the rapid exploration of biological patterns in high-throughput -Omic datasets. This framework takes advantage of standard file formats from computational pipelines in order to bridge the gap between biological software (e.g. microbial ecology pipelines such as QIIME) and existing data visualization capabilities (harnessing the flexibility and scalability of technologies such as HTML5). This project is a collaboration between the Bik Lab and Pitch Interactive (a data visualization studio based in Oakland, CA); development of the current prototype framework was funded by a grant from the Alfred P. Sloan Foundation. Phinch is open source software - the [underlying code is available on GitHub] and [detailed software documentation can be found on the accompanying GitHub wiki] (e.g. supported file formats and features of visualization tools)

Phinch is optimized for use in the Google Chrome browser. It currently supports downstream analyses of [BIOM v1.0 files] (Biological Observation Matrix files, a JSON-formatted file type typically used to represent marker gene OTUs or metagenomic data). All sample metadata and taxonomy/ontology information MUST be embedded in the BIOM file before being uploaded. 


<u>Reference:</u> Bik HM, Pitch Interactive (2014) [Phinch: An interactive, exploratory data visualization framework for –Omic datasets], <em>bioRxiv</em>, doi:10.1101/009944 (preprint)

[http://phinch.org]:http://phinch.org

[underlying code is available on GitHub]: https://github.com/PitchInteractiveInc/Phinch
[detailed software documentation can be found on the accompanying GitHub wiki]: https://github.com/PitchInteractiveInc/Phinch/wiki

[BIOM v1.0 files]: http://biom-format.org/

[Phinch: An interactive, exploratory data visualization framework for –Omic datasets]: http://dx.doi.org/10.1101/009944

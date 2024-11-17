---
layout: post
title: New Target Capture Service
categories:
 - blog
author_handle: madbullo
homepage: false
---

Are you in need of targeted DNA sequencing using [Angiosperms353](https://arborbiosci.com/products/targeted-ngs/mybaits-predesigned-kits/mybaits-expert-predesigned-panels/mybaits-expert-plant-angiosperms-353/), GoFLAG408, or other probes? Check out our new service, now accepting samples for runs beginning in early 2025!

This service is made possible by several innovative updates to our library workflow by PhD Candidate [Madison Bullock]({{ site.baseurl }}{% link team/_posts/2021-09-01-madison-bullock.md %}), who has done a fantstic job building on our [earlier work to reduce per-sample costs in target capture](http://127.0.0.1:4000/papers/paper/Hale_HybSeq_lowcost.html). 

![a](/assets/images/blog/HybSeqServiceFlyer.png){:class="img-responsive"}{:class="img-responsive"}

## Major Cost Savings for HybSeq

Our major workflow improvement to drastically reduce costs is miniaturization of the Illumina library preparation – we have successful targeted sequencing runs with libraries prepared at 1/10 volume using a [precise liquid handling robot](https://www.sptlabtech.com/products/mosquito/mosquito-hv-genomics). The miniaturization drops the consumable costs for library prep to about $5/sample. When we add in massive multiplexing during sequencing (up to 480 samples per lane of NovaSeq6000 SP), we can keep total consumable costs under $15/sample. The additional upcharge is going to a fund to pay the stipend and tuition supporting a PhD Candidate (Madison) to run the samples.  

Our $30/sample price point includes: 

- Concentration/dilution of initial DNA as needed – ideal submission is at least 100 ng of DNA in at least 30 µL.
- [NEBNext Ultra II DNA Library preparation](https://www.neb.com/en-us/products/e7645-nebnext-ultra-ii-dna-library-prep-kit-for-illumina) with an insert size goal of 500 bp
- Library concentrations determined using PicoGreen and a plate reader
- Library size distribution (TapeStation) for a subset of 15 samples per plate
- Target enrichment with Angiosperms353 (or other probes, see below), multiplexing 24 samples per reaction
- Sequencing on NovaSeq6000 using an SP flow cell, 2x250 reads. 

We multiplex either 4 plates (384 samples) or 5 plates (460 samples) per lane, and with this setup we average 1-2 million paired reads per sample. For reference, [we have previously demonstrated](https://bsapubs.onlinelibrary.wiley.com/doi/full/10.1002/aps3.11419) that 200K reads on target is sufficient for recovering over 300 genes with Angiosperms353. We typically see about 25% of reads on target with Angiosperms353, but this varies by taxon.

## Probe Sets 
We currently have probes for the following:

- Angiosperms353 ([Johnson, Pokorny, Dodsworth et al., 2019](https://academic.oup.com/sysbio/article/68/4/594/5237557)), targeting 353 nuclear coding genes for flowering plants. 
- GoFLAG408 ([Breinholt et al., 2021](https://bsapubs.onlinelibrary.wiley.com/doi/10.1002/aps3.11406)), targeted 408 exons at ~250 nuclear genes for gymnosperms, ferns, lycophytes, and bryophytes.
- MossToL809 ([Medina et al., 2019](https://onlinelibrary.wiley.com/doi/10.1111/jse.12516)), targeting 809 nuclear genes for moss class Bryopsida. A subset of these loci were used in the ordinal phylogeny of mosses [Liu, Johnson, et al., 2019](https://www.nature.com/articles/s41467-019-09454-w).
- Compositae1061 ([Mandel et al., 2014](https://bsapubs.onlinelibrary.wiley.com/doi/10.3732/apps.1300085)) targeting over one thousand loci for the Asteraceae.

If you have other probes or wish to use one of the [expert panels available from Arbor Biosciences](https://arborbiosci.com/products/targeted-ngs/mybaits-predesigned-kits/mybaits-expert-predesigned-panels/), contact us to determine the best strategy. We are also able to combine probe sets using the "best of both worlds" approach ([Hendricks et al., 2021](https://bsapubs.onlinelibrary.wiley.com/doi/10.1002/aps3.11438))

## Expected Timeline

There are two major drawbacks of us versus a more experienced industry provider: 

1. It is most cost-efficient to run the NovaSeq only when we have a full run (960 samples) 

2. The libraries are being prepared by just one grad student working ~20 hr/wk. Madison’s adjusted the work flow such that it is feasible to work through 2 plates (192 samples) per week. 

Our plan is to have a full sequencing run (960 samples) every 2.5 months in 2025.

## Other Services
DNA extraction and Bioinformatics support are available for an addiional charge.

## How to Order
For inquiries about our workflow or to get a quote, use the email in the flyer above. 

When you are ready to send samples, we will need at least 100 ng of DNA in at least 30 µL of elution buffer (TE or water). We will send you a sample sheet to keep track of your submission, and we would also need to know whether you would like us to use the [Fragmentase](https://www.neb.com/en-us/products/e6177-nebnext-ultra-ii-fs-dna-library-prep-with-sample-purification-beads) version of the NEB protocol (enzymatic shearing DNA to ~ 500 bp, better for high-molecular weight DNA) or the [non-Fragmentase version](https://www.neb.com/en-us/products/e7103-nebnext-ultra-ii-dna-library-prep-with-sample-purification-beads) (better for older herbarium specimens). We can mix and match depending on your samples.

Samples can be mailed to us at Texas Tech University using the address above. We can accept samples in either tubes or well-sealed plates. Dry ice is not typically neccessary, but an ice pack or two can be helpful especially if shipping in the summer.







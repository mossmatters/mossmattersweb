---
layout: project
title: "FDA Angiosperms353 Metabarcoding"
author_handle: mossmatters
image: /assets/images/projects/Hybpiper_venn.png
category: research
homepage: false
published: true
---

# New Funding from FDA-CFSAN

In October 2022, we began new collaboration between the Johnson Lab at Texas Tech University and the US Food and Drug Administration Center for Food Safety and Nutrition (FDA-CFSAN). Our proposal "Improving detection of plant contaminants in mixed samples with targeted sequencing of 353 nuclear protein coding genes" is aimed at extending Angiosperms353 and HybPiper for use in mixed samples, such as potentially adulterated nutritional supplements. The project funds a [post-doctoral researcher]({% post_url posts/2022-10-04-PostdocFDABAA %}), sequencing costs and travel for two years. The abstract of this Broad Agency Agreement (BAA) is below.

---

The ability to identify unknown plant materials via their DNA is of regulatory interest to detect adulterated products on the market. Unfortunately, the use of DNA for identification of plants has lagged applications in other organisms, often due to lack of appropriate DNA markers variable enough to distinguish closely related species. Targeted sequencing of conserved regions has [emerged as a cost-effective way to sequence hundreds of loci](https://bsapubs.onlinelibrary.wiley.com/doi/full/10.1002/aps3.11337) in a wide range of organisms. [Angiosperms353 are a set of loci](https://academic.oup.com/sysbio/article/68/4/594/5237557) recently shown to be present in single-copy in most flowering plants, [and are variable within species](https://bsapubs.onlinelibrary.wiley.com/doi/full/10.1002/aps3.11419). Thus, there is an emerging opportunity to use the Angiosperms353 loci to identify plants and allow for the detection of contaminants in mixed plant tissues. 

However, there are two major barriers to the use of Angiosperms353 as an identification tool: computational tools to analyze mixed samples, and a comprehensive DNA sequence database of relevant species. While some software is available [to analyze single genes in mixed samples (e.g. QIIME2)](https://qiime2.org/) and [other software (e.g. HybPiper) can analyze hundreds of loci from single samples](https://github.com/mossmatters/HybPiper), there is currently no software available for the analysis of hundreds of genes in mixed samples. Further, [while some databases of Angiosperms353 loci are in development](https://treeoflife.kew.org/), their focus is not on botanical products and related species. 

Our project has two aims:

**Aim 1: Comprehensive Database**. Extend an existing database of Angiosperms353 sequences to include plants commonly used in foods and dietary supplements, potential contaminant species, and close relatives of these species.

**Aim 2: Proposed Workflow** Develop a comprehensive bioinformatics workflow to positively identify plant species represented in a mixed sample using targeted DNA sequencing of 353 nuclear protein coding genes.

The Comprehensive Database will be used to verify the precision and specificity of the Proposed Workflow. Sensitivity will be tested using mock adulterated samples containing DNA from botanicals of interest and common potential contaminants. This proposal will result in two deliverables: the Comprehensive Database of DNA sequences, which will be released into public archives; and the Bioinformatics Workflow for extracting sequences from mixed samples, which will be developed open-source and made available for free. Upon successful development of the Proposed Workflow, downstream data analysis of DNA sequences could be used in future work to identify specific tests to detect adulterants for regulatory purposes. 

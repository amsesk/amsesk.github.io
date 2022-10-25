---
layout: page
title: Research
permalink: /research/
---

## Ecology and evolution of obligate Burkholderia-related endohyphal bacteria (BRE)

Fungi are members of complex natural systems, within which their interactions with other living components of these systems (i.e., symbioses) can play pivotal roles in global patterns of nutrient cycling (e.g., mycorrhizae). The stable, symbiotic colonization of fungal cells by bacteria (i.e., endosymbiotic bacteria) is becoming increasingly recognized in nature, although the implications and histories of these systems remain poorly understood. Our work here generates genome-scale data for pairs of symbiotic partners, the current paucity of which corresponds with the relative novelty of this type of symbiosis to science. With increased sampling in genomic contexts, we can better understand the entangled evolutionary trajectories along which partners coevolve, how novel pairs of partners arise and stabilize over deep time scales, and the functional implications of harboring endosymbiotic bacteria with respect to the host.

#### Selected papers

*Coming soon*

## Genome-scale phylogenetics of enigmatic early-diverging fungi

Most fungi are uncultured, meaning that they have not, and possibly cannot, be isolated in pure laboratory cultures. This simple reality severely complicates biological research in these areas of the fungal tree of life, obscuring their forms, functions, and evolutionary histories. My dissertation research uses single-cell genomics (SCG) to circumvent this central obstacle, sequencing the genomes of uncultured fungi collected as individual cells directly from nature. Genome-scale data in hand, we can resolve blurry areas of the tree of life and characterize the life histories of these dark matter fungi in a genetic context.

#### Selected papers

[Amses et al. 2022. *Proc Natl Acad Sci USA.*](https://www.pnas.org/doi/10.1073/pnas.2116841119)

[Davis et al. 2019. *Mol Phylogenet Evol.*](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6886740/) 


## Development and implementation of novel algorithms and software for single cell genomics of cryptic microbes


Whole-genome sequencing of uncultured eukaryotic genomes is complicated by difficulties in acquiring sufficient amounts of tissue. Single-cell genomics (SCG) by multiple displacement amplification provides a technical workaround, yielding whole-genome libraries which can be assembled de novo. Downsides of multiple displace- ment  amplification  include  coverage  biases  and  exacerbation  of  contamination.  These  factors  affect  assembly continuity and fidelity, complicating discrimination of genomes from contamination and noise by available tools. Uncultured eukaryotes and their relatives are often underrepresented in large sequence data repositories, further impairing identification and separation.

In our 2020 publication, we  compare  the  ability  of  filtering  approaches  to  remove  contamination  and  resolve  eukaryotic  draft genomes from SCG metagenomes, finding significant variation in outcomes. To address these inconsistencies, we introduced a consensus approach that is codified in the SCGid software package. SCGid parallelly filters assemblies using different approaches, yielding three intermediate drafts from which consensus is drawn. Using genuine and mock SCG metagenomes, we show that our approach corrects for variation among draft genomes predicted by indi- vidual approaches and outperforms them in recapitulating published drafts in a fast and repeatable way, providing a useful alternative to available methods and manual curation.
Availability and implementation: 

The SCGid package is implemented in python and R. Source code is available at [http://www.github.com/amsesk/SCGid](http://www.github.com/amsesk/SCGid) under the GNU GPL 3.0 license.

#### Selected papers

[Amses et al. 2020. *Bioinform*.](https://academic.oup.com/bioinformatics/article/36/7/1994/5640497)
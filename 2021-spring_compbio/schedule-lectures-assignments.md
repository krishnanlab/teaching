# CMSE 410/890: Bioinformatics and Computational Biology

| Links to all pages | [Home](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/README.md) |
| :-: | :-: |
| [**Schedule, Lectures, and Assignments**](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/schedule-lectures-assignments.md) | [**Website and Communication**](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/website-communication.md) |
| [**Course Activities**](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/course-activities.md) | [**Grading**](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/grading.md) |
| [**Presence, Conduct, Honesty, and Accommodations**](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/policies.md) | [**Learning Online**](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/learning-online.md) |


## Schedule, Lectures, and Assignments

### Calendar
This calendar contains the class schedule and the links to the lecture slides and reading materials. Download the detailed schedule as a [PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/CMSE410-890_Spring-2021_Schedule.pdf).

| Date | Module | Topic | Notes |
|:-:|:-|:-|:-|
| Day_-03 Mon, Jan 11 | Refreshers | Statistics and Probability | _Note:_ Review day |
| Day_-02 Wed, Jan 13 | Refreshers | Concepts in Computing | _Note:_ Review day |
| Day_-01 Fri, Jan 15 | Refreshers | [TBD: Other topics] | _Note:_ Review day |
| Day_00 Mon, Jan 18 | MLK day; No class | MLK day; No class | _Note:_ MLK day; No class |
| Day_01 Wed, Jan 20 | Introductions | Course Overview | _Note:_ Online class begins</br></br>\[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_02 Fri, Jan 22 | Introductions | Intro to Bioinfo & CompBio | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_03 Mon, Jan 25 | Sequence Alignment | Dynamic programming; Substitution matrices | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_04 Wed, Jan 27 | Sequence Alignment | Fast local alignment |  |
| Day_05 Fri, Jan 29 | Sequence Alignment | Paper discussion | 1. Basic local alignment search tool \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Altschul1990_BLAST.pdf)]</br>2. Steps used by the BLAST algorithm \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Mount2007_steps-used-by-blast.pdf)] |
| Day_06 Mon, Feb 01 | Genome Assembly and Annotation | Assembly with de Bruijin graphs | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_07 Wed, Feb 03 | Genome Assembly and Annotation | Gene prediction with hidden Markov models |  |
| Day_08 Fri, Feb 05 | Genome Assembly and Annotation | Paper discussion | Velvet: Algorithms for de novo short read assembly using de Bruijn graphs \[[Journal](http://genome.cshlp.org/content/18/5/821)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Zerbino2008_velvet-assembler.pdf)] |
| Day_09 Mon, Feb 08 | Comparative Genomics; Phylogenetics | Whole-genome alignment; Suffix trees | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_10 Wed, Feb 10 | Comparative Genomics; Phylogenetics | Molecular evolution; Tree construction |  |
| Day_11 Fri, Feb 12 | Comparative Genomics; Phylogenetics | Paper discussion | _Four MUMmer papers:_</br>1. MUMmer1: Alignment of whole genomes \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC148804/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Delcher1999_MUMmer1.pdf)]</br>2. MUMmer2: Fast algorithms for large-scale genome alignment and comparison \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC117189/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Delcher2002_MUMmer2.pdf)]</br>3. MUMmer3: Versatile and open software for comparing large genomes \[[Journal](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2004-5-2-r12)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Kurtz2004_MUMmer3.pdf)]</br>4. MUMmer4: A fast and versatile genome alignment system \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005944)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Mar%C3%A7ais2018_MUMmer4.pdf)] |
| Day_12 Mon, Feb 15 | Quantitative Genetics | GWAS; Statistical inference; Multiple testing | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_13 Wed, Feb 17 | Quantitative Genetics | Regularized linear regression; Polygenic risk score |  |
| Day_14 Fri, Feb 19 | Quantitative Genetics | Paper discussion | 1. Genome-Wide Association Studies \[[Journal](https://doi.org/10.1371/journal.pcbi.1002822)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Bush-Moore2012_GWAS.PDF)]</br>2. Mining Genome-Wide Genetic Markers \[[Journal](https://doi.org/10.1371/journal.pcbi.1002828)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Zhang2012_mining-genomewide-genetic-markers.PDF)]</br>3. How does multiple testing correction work? \[[Journal](https://www.nature.com/articles/nbt1209-1135)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Noble2009_primer-multiple-testing-correction.pdf)]</br>4. Statistical significance for genomewide studies \[[Journal](https://doi.org/10.1073/pnas.1530509100)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Storey-Tibshirani2003_statistical-significance-genomewide-studies.pdf)] |
| Day_15 Mon, Feb 22 | Regulatory Genomics | ChIP-seq; Expectation maximization | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_16 Wed, Feb 24 | Regulatory Genomics | EM; Gibbs sampling |  |
| Day_17 Fri, Feb 26 | Regulatory Genomics | Paper discussion | 1. What are DNA sequnence motifs? \[[Journal](https://www.nature.com/articles/nbt0406-423)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Dhaeseleer2006_what-are-dna-motifs.pdf)]</br>2. How does DNA sequence motif discovery work? \[[Journal](https://www.nature.com/articles/nbt0806-959)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Dhaeseleer2006_how-does-motif-discovery-work.pdf)]</br>3. What is the Expectation Maximization algorithm? \[[Journal](https://www.nature.com/articles/nbt1406)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Do-Batzoglou2008_what-is-EM.pdf)]</br>4. Practical Strategies for Discovering Regulatory DNA Sequence Motifs \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0020036)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/MacIsaac-Fraenkel2006_strategies-for-discovering-motifs.pdf)] |
| Day_18 Mon, Mar 01 | CompBio Primers | Organizing, managing, and kick-starting a project | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_19 Wed, Mar 03 | Break day; No class | Break day; No class | _Note:_ Mid-semester feedback due on Th, Mar 04 |
| Day_20 Fri, Mar 05 | CompBio Primers | Getting help and presenting data & results | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_21 Mon, Mar 08 | Mid-course Project Update | Project co-work |  |
| Day_22 Wed, Mar 10 | Mid-course Project Update | Recording presentations |  |
| Day_23 Fri, Mar 12 | Mid-course Project Update | Discussion of presentation reviews |  |
| Day_24 Mon, Mar 15 | Functional Genomics | Distance measures; Clustering | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_25 Wed, Mar 17 | Functional Genomics | Differential expression; Functional enrichment |  |
| Day_26 Fri, Mar 19 | Functional Genomics | Paper discussion | A module map showing conditional activity of expression modules in cancer \[[Journal](https://www.nature.com/articles/ng1434)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Segal2004_cancer-module-map.pdf)] |
| Day_27 Mon, Mar 22 | Single-cell Genomics | Dimensionality reduction | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day-28 Wed, Mar 24 | Single-cell Genomics | Supervised machine learning |  |
| Day_29 Fri, Mar 26 | Single-cell Genomics | Paper discussion | The dynamics and regulators of cell fate decisions are revealed by pseudotemporal ordering of single cells \[[Journal](https://www.nature.com/articles/nbt.2859)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Trapnell2014_scrnaseq-pseudotime-monocle.pdf)] |
| Day_30 Mon, Mar 29 | Protein Structure Prediction and Dynamics | Contact prediction; Maximum entropy modeling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_31 Wed, Mar 31 | Protein Structure Prediction and Dynamics | Molecular dynamics |  |
| Day_32 Fri, Apr 02 | Protein Structure Prediction and Dynamics | Paper discussion | Evolutionarily conserved networks of residues mediate allosteric communication in proteins \[[Journal](https://doi.org/10.1038/nsb881)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Suel2003_networks-of-residues.pdf)] |
| Day_33 Mon, Apr 05 | Biological Networks | Representaiton and topological properties | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_34 Wed, Apr 07 | Biological Networks | Network reconstruction; Label propagation |  |
| Day_35 Fri, Apr 09 | Biological Networks | Paper discussion | Genomic analysis of regulatory network dynamics reveals large topological changes \[[Journal](https://www.nature.com/articles/nature02782)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Luscombe2004_topological-network-dynamics.pdf)] |
| Day_36 Mon, Apr 12 | Modeling Cellular Pathways | Dynamical modeling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_37 Wed, Apr 14 | Modeling Cellular Pathways | State space; Bifurcation analysis |  |
| Day_38 Fri, Apr 16 | Modeling Cellular Pathways | Paper discussion | Construction of a genetic toggle switch in E. coli \[[Journal](https://www.nature.com/articles/35002131)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Gardner2000-Ecoli-genetic-toggle-switch.pdf)] |
| Day_39 Mon, Apr 19 | Whole-cell Models; Digital Evolution | Genome-scale metabolic models; Constraint-based modeling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)] |
| Day_40 Wed, Apr 21 | Whole-cell Models; Digital Evolution | Artificial life | _Note:_ Last lecture</br></br>\[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Lectures/)]</br></br>_Papers:_</br>1. Network-based prediction of human tissue-specific metabolism \[[Journal](https://www.nature.com/articles/nbt.1487)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Shlomi2008_tissue-specific-metabolic-network.pdf)]</br>2. Integration of expression data in genome-scale metabolic network reconstructions (Mini supplementary reading to help with the main paper) \[[Journal](https://www.frontiersin.org/articles/10.3389/fphys.2012.00299/full)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Papers/Blazier2012_integrating-expression-with-metabolic-network.pdf)]</br> |
| Day_41 Fri, Apr 23 | Break day; No class | Break day; No class | _Note:_ Break day; No class |
| Day_42 Thr, Apr 29 | Lightning talks | Student presentations | _Note:_ Diff. day/time: Thr, 12:45 – 2:45p |


#### Project milestones
| Milestone | Due date |
|:--------- | :---------- |
| Reserach profile | Fri, Jan 22 |
| Project topic | Fri, Jan 29 |
| Project pre-proposal | Fri, Feb 5 |
| Project proposal | Fri, Feb 19 |
| Proposal reviews | Fri, Feb 26 |
| Mid-term project presentation recordings | Wed, Mar 10 |
| Mid-course Project presentation reviews | Fri, Mar 12 |
| Mid-course project report | Fri, Mar 19 |
| Final project report | Wed, Apr 21 |
| Final project poster presentations | _Note:_ Diff. day/time \| Thr, Apr 29, 12:45 – 2:45p |


#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]

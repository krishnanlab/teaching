# [CMSE 410/890: Bioinformatics and Computational Biology](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio)

>Home, Schedule, Lectures, and Discussion notes  
>[Website and Communication](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/website-communication.md)  
>[Course Activities and Grading](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md)  
>[Philosophy, Presence, Conduct, Honesty, and Accommodations](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/policies.md)  


# Home of CompBio2022

[Description](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#description) | [Instructor](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#instructor) | [Schedule](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#schedule) | [Class Calendar](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#class-calendar) | [Project Milestones](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#project-milestones) | [Student Hours](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#student-hours)

## Description
Welcome to the Spring 2022 edition of **Bioinformatics and Computational Biology**, an introduction to the inner-workings of methods in bioinformatics and computational biology: analytical techniques, algorithms, and statistical/machine-learning approaches developed to address key questions in biology and medicine.

In this course, students will also learn how to formulate problems for quantitative inquiry, design computational projects, think critically about data & methods, do reproducible research, and communicate findings.

* **Syllabus:** The PDF of the course syllabus is [here](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/CompBio2022_Syllabus.pdf).
* **Website:** This website contains up-to-date information about everything related to this class.
* **Slack:** The [class Slack workspace](https://compbio2022.slack.com/) will be the space for all live announcements and discussions. If you're enrolled, an invitation should be in your MSU email. If not, email Arjun ASAP.

### Enrollment
Open to both undergraduate and graduate students. Counts toward the CMSE minor, graduate certificates, and dual PhD. Please email Heather Johnson at john1451@msu.edu for an override.

### Prerequisites
Basically, it would be assumed that you:
- know how to code in one of the mainstream languages like Python or R,
- have an understanding of basic statistics and probability, and
- have studied basic genetics, molecular biology, and cellular biology.

**MSU courses that you can take to satisfy these prerequisites:** CMSE 201 or CMSE 301-304 or equivalent with programming experience and two semesters of introductory biology (LB 144 and 145 OR BS 161 and 162 OR BS 181H and 182H, or equivalent). Statistics at the level of STT 231 is strongly recommended.

#### Recommended Materials
[This document](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Additional-learning-resources.md) contains links to a bunch of excellent resources for brushing-up your Unix, Python/R, Statistics, and Biology.

#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#home-of-compbio2022) ]

## Instructor
Name | Arjun Krishnan
:------------ | :------------
Pronouns | He/him/his
Affiliation | Dept. Computational Mathematics, Science, and Engineering</br>Dept. Biochemistry and Molecular Biology
Office | 2507H Engineering Building
Contact | Email: arjun@msu.edu</br>Twitter: [@compbiologist](https://twitter.com/compbiologist)</br>Website: https://thekrishnanlab.org

#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#home-of-compbio2022) ]

## Schedule, Calendar, and Student Hours

Dates | Jan 10 – May 01, 2022
:------------ | :------------
Weekly | Mon, Wed, and Fri</br>09:10 am - 10:00 am
Location | In-perons: 1220 Engineering building</br>Zoom: check the [course Slack workspace](https://compbio2022.slack.com/) for details

### Note on all schedules
All aspects of our course's schedule will be maintained in a living shared google sheet document (link available on Slack). This doc contains the i) Full course calendar, ii) Paper presentation schedule, iii) Student hour appointments, iv) Midterm presentation schedule, and v) Final presentation schedule.

#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#home-of-compbio2022) ]

## Class Calendar
The calendar below contains the class schedule and the links to the lecture slides and reading materials.

| Date | Module | Topic | Notes |
|:-:|:-|:-|:-|
| Day_01 Mon, Jan 10 | Course Overview | Course Overview – Part 1 | _Note:_ Online class begins</br></br>\[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Introductions_Course-overview.pdf)] |
| Day_02 Wed, Jan 12 | Course Overview | Course Overview – Part 2 | _Note:_ Review day |
| Day_03 Fri, Jan 14 | Refreshers | Probability and statistics | _Note:_ Review day |
| Day_04 Mon, Jan 17 | No class | No class | _Note:_ No class |
| Day_05 Wed, Jan 19 | Refreshers | Building models based on data | _Note:_ Review day |
| Day_06 Fri, Jan 21 | Intro to Bioinfo & CompBio | Topical Overview | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Introductions_Intro-to-Bioinfo-and-Compbio.pdf)] |
| Day_07 Mon, Jan 24 | Sequence Alignment | Dynamic programming | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Sequence-alignment-and-search_DP-local-global-alignment.pdf)] |
| Day_08 Wed, Jan 26 | Sequence Alignment | Substitution matrices | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Sequence-alignment-and-search_Substitution-matrix-BLAST.pdf)] |
| Day_09 Fri, Jan 28 | Sequence Alignment | Fast local alignment; Paper discussion | Having a BLAST with bioinformatics (and avoiding BLASTphemy) \[[Journal](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2001-2-10-reviews2002)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Pertsemlidis2001_having-a-BLAST.pdf)]</br></br>Additional resources:</br>1. BLAST Wikipedia page \[[link](https://en.wikipedia.org/wiki/BLAST)]</br>2. BLAST Handbook \[[link](https://www.ncbi.nlm.nih.gov/books/NBK153387/)]</br>3. BLAST Practical details \[[link](https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=BlastHelp)]</br></br>\[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Sequence-alignment-and-search_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1SkIQo38DYiXYdK7XQ8nrAQvoh4iXRGqCpMmWxk83Cyo/edit?usp=sharing)] |
| Day_10 Mon, Jan 31 | Genome Assembly and Annotation | Assembly with de Bruijin graphs | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Genome-assembly-and-annotation_OLC-de-Bruijin-graphs.pdf)] |
| Day_11 Wed, Feb 02 | Genome Assembly and Annotation | Gene prediction with hidden Markov models | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Genome-assembly-and-annotation_Hidden-markov-models.pdf)] |
| Day_12 Fri, Feb 04 | Genome Assembly and Annotation | Paper discussion | Velvet: Algorithms for de novo short read assembly using de Bruijn graphs \[[Journal](http://genome.cshlp.org/content/18/5/821)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Zerbino2008_velvet-assembler.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Genome-assembly-and-annotation_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/18PRNV7UCWOEsMZI23EqcSHY5o2LQuy_xsmWp0rXiE1o/edit?usp=sharing)] |
| Day_13 Mon, Feb 07 | Comparative Genomics; Phylogenetics | Whole-genome alignment; Suffix trees | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Comparative-genomics-and-phylogenetics_Whole-genome-alignment.pdf)] |
| Day_14 Wed, Feb 09 | Comparative Genomics; Phylogenetics | Molecular evolution; Tree construction | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Comparative-genomics-and-phylogenetics_Phylogenetic-tree-building.pdf)] |
| Day_15 Fri, Feb 11 | Comparative Genomics; Phylogenetics | Paper discussion | _Four MUMmer papers:_</br>1. MUMmer1: Alignment of whole genomes \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC148804/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Delcher1999_MUMmer1.pdf)]</br>2. MUMmer2: Fast algorithms for large-scale genome alignment and comparison \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC117189/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Delcher2002_MUMmer2.pdf)]</br>3. MUMmer3: Versatile and open software for comparing large genomes \[[Journal](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2004-5-2-r12)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Kurtz2004_MUMmer3.pdf)]</br>4. MUMmer4: A fast and versatile genome alignment system \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005944)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Mar%C3%A7ais2018_MUMmer4.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Comparative-genomics-and-phylogenetics_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1sBBmN0gX7gplc5ZsJNHrUORTyFxlBVECFOqcg7Rtc4o/edit?usp=sharing)] |
| Day_16 Mon, Feb 14 | Quantitative Genetics | GWAS; Statistical inference; Multiple testing | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Quantitative-genetics_GWAS-Hypothesis-testing.pdf)] |
| Day_17 Wed, Feb 16 | Quantitative Genetics | Regularized linear regression; Polygenic risk score |  |
| Day_18 Fri, Feb 18 | Quantitative Genetics | Paper discussion | 1. Genome-Wide Association Studies \[[Journal](https://doi.org/10.1371/journal.pcbi.1002822)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Bush-Moore2012_GWAS.PDF)]</br>2. Mining Genome-Wide Genetic Markers \[[Journal](https://doi.org/10.1371/journal.pcbi.1002828)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Zhang2012_mining-genomewide-genetic-markers.PDF)]</br>3. How does multiple testing correction work? \[[Journal](https://www.nature.com/articles/nbt1209-1135)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Noble2009_primer-multiple-testing-correction.pdf)]</br>4. Statistical significance for genomewide studies \[[Journal](https://doi.org/10.1073/pnas.1530509100)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Storey-Tibshirani2003_statistical-significance-genomewide-studies.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Quantitative-genetics_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1VA-nFUGferK78eYLkYRPP0uWKGImJnJTSEYVJBoUsfU/edit?usp=sharing)] |
| Day_19 Mon, Feb 21 | Regulatory Genomics | DNA binding sites; Position weight matrices; ChIP-seq | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Regulatory-genomics_TF-binding-motifs-PWMs.pdf)] |
| Day_20 Wed, Feb 23 | Regulatory Genomics | Expectation-Maximization; Gibbs sampling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Regulatory-genomics_Expectation-Maximixation.pdf)] |
| Day_21 Fri, Feb 25 | Regulatory Genomics | Paper discussion | 1. What are DNA sequence motifs? \[[Journal](https://www.nature.com/articles/nbt0406-423)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Dhaeseleer2006_what-are-dna-motifs.pdf)]</br>2. How does DNA sequence motif discovery work? \[[Journal](https://www.nature.com/articles/nbt0806-959)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Dhaeseleer2006_how-does-motif-discovery-work.pdf)]</br>3. What is the Expectation Maximization algorithm? \[[Journal](https://www.nature.com/articles/nbt1406)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Do-Batzoglou2008_what-is-EM.pdf)]</br>4. Practical Strategies for Discovering Regulatory DNA Sequence Motifs \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0020036)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/MacIsaac-Fraenkel2006_strategies-for-discovering-motifs.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Regulatory-genomics_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1HNOlv3TwuETv3lZAQv6BiRgqhqr12_WqM7GqRCJ9RSI/edit?usp=sharing)] |
| Day_22 Mon, Feb 28 | CompBio Primers | Organizing and managing a project | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/CompBio-primers_Organizing-and-managing-a-project.pdf)] |
| Day_23 Wed, Mar 02 | CompBio Primers | Kickstarting a project | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/CompBio-primers_Kickstarting-a-project.pdf)] |
| Day_24 Fri, Mar 04 | CompBio Primers | Presenting data and results | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/CompBio-primers_Presenting-data-and-results.pdf)] |
| Day_25 Mon, Mar 07 | No Class | No Class | _Note:_ Spring Break |
| Day_26 Wed, Mar 09 | No Class | No Class | _Note:_ Spring Break |
| Day_27 Fri, Mar 11 | No Class | No Class | _Note:_ Spring Break |
| Day_28 Mon, Mar 14 | Functional Genomics | Similarity measures; Clustering | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Functional-genomics_Similarity-measures-Clustering.pdf)] |
| Day_29 Wed, Mar 16 | Functional Genomics | Differential expression; Functional enrichment |  |
| Day_30 Fri, Mar 18 | Functional Genomics | Paper discussion | A module map showing conditional activity of expression modules in cancer \[[Journal](https://www.nature.com/articles/ng1434)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Segal2004_cancer-module-map.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Functional-genomics_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1pc7r9PhcTCm18d5CiCrIdIT7ehbWEP0NC0Jolr34fEU/edit?usp=sharing)] |
| Day_31 Mon, Mar 21 | Single-cell Genomics | Dimensionality reduction | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Single-cell-genomics_Intro-Dimensionality-reduction.pdf)] |
| Day_32 Wed, Mar 23 | Single-cell Genomics | Supervised machine learning |  |
| Day_33 Fri, Mar 25 | Single-cell Genomics | Paper discussion | The dynamics and regulators of cell fate decisions are revealed by pseudotemporal ordering of single cells \[[Journal](https://www.nature.com/articles/nbt.2859)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Trapnell2014_scrnaseq-pseudotime-monocle.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Single-cell-genomics_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/13HVajy6xRcISmBIfWysMjDruHHJ-NYU2M2vcPLdtYsI/edit?usp=sharing)] |
| Day_34 Mon, Mar 28 | Protein Structure Prediction and Dynamics | Contact prediction; Maximum entropy modeling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Protein-structure-and-dynamics_Coevolution.pdf)] |
| Day_35 Wed, Mar 30 | Protein Structure Prediction and Dynamics | Molecular dynamics | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Protein-structure-and-dynamics_Molecular-dynamics.pdf)] |
| Day_36 Fri, Apr 01 | Protein Structure Prediction and Dynamics | Paper discussion | Evolutionarily conserved networks of residues mediate allosteric communication in proteins \[[Journal](https://doi.org/10.1038/nsb881)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Suel2003_networks-of-residues.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Protein-structure-and-dynamics_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1qsl471UnVGQXEEtacW5MNQZev2P3x1fYunoEOpRekQU/edit?usp=sharing)] |
| Day_37 Mon, Apr 04 | Biological Networks | Topology, Motif, Rewiring | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Biological-networks_Topology-Motifs-Rewiring.pdf)] |
| Day_38 Wed, Apr 06 | Biological Networks | Reconstruction, Propagation | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Biological-networks_Reconstruction-Propagation.pdf)] |
| Day_39 Fri, Apr 08 | Biological Networks | Paper discussion | Genomic analysis of regulatory network dynamics reveals large topological changes \[[Journal](https://www.nature.com/articles/nature02782)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Luscombe2004_topological-network-dynamics.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Biological-networks_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1YdyLlPn0OFtD4b_uBJFUYnBXHIWjZ1Gf7ykP9f3QMbM/edit?usp=sharing)] |
| Day_40 Mon, Apr 11 | Modeling Cellular Pathways | Dynamical modeling, Simple motifs, Bifurcations | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Modeling-cellular-pathways_Dynamical-systems-Simple-motifs.pdf)] |
| Day_41 Wed, Apr 13 | Modeling Cellular Pathways | State space; Cell cycle models | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Modeling-cellular-pathways_State-space-Cell-cycle-model.pdf)] |
| Day_42 Fri, Apr 15 | Modeling Cellular Pathways | Paper discussion | Construction of a genetic toggle switch in E. coli \[[Journal](https://www.nature.com/articles/35002131)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Gardner2000-Ecoli-genetic-toggle-switch.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/Modeling-cellular-pathways_Discussion-notes.md)]</br></br>\[[Paper discussion slides](https://docs.google.com/presentation/d/1dZ9k_0Oei2WdDZusMDWNIPfHaifHtiMbEcdkA40ieV8/edit?usp=sharing)] |
| Day_43 Mon, Apr 18 | Whole-cell Models; Digital Evolution | Genome-scale metabolic models | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/Whole-cell-models-Digital-evolution_Flux-balance-analysis.pdf)]  |
| Day_44 Wed, Apr 20 | Whole-cell Models; Digital Evolution | Constraint-based modeling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/)] |
| Day_45 Fri, Apr 22 | Whole-cell Models; Digital Evolution | Artificial life (Lecture); Paper discussion (metabolic models) | _Note:_ Last lecture</br></br>\[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Lectures/)]</br></br>_Papers:_</br>1. Network-based prediction of human tissue-specific metabolism \[[Journal](https://www.nature.com/articles/nbt.1487)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Shlomi2008_tissue-specific-metabolic-network.pdf)]</br>2. Integration of expression data in genome-scale metabolic network reconstructions (Mini supplementary reading to help with the main paper) \[[Journal](https://www.frontiersin.org/articles/10.3389/fphys.2012.00299/full)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Blazier2012_integrating-expression-with-metabolic-network.pdf)]</br></br>[[Paper discussion notes](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/)]</br></br>\[[Paper discussion slides](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Discussion-notes/)] |
| Day_46 Mon, Apr 25 | Final Project Submission | Work on project and report |  |
| Day_47 Wed, Apr 27 | Final Project Submission | Work on project and report |  |
| Day_48 Fri, Apr 29 | Final Project Submission | Work on project and report |  |
| Day_49 Tue, May 03 | Lightning talks | Student presentations | _Note:_ Diff. day/time: Tue, May 03, 12:45 – 2:45p |

#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#home-of-compbio2022) ]

### Project Milestones
| Milestone | Due date | Links/Notes |
|:--------- | :---------- | :---------- |
| 1. Reserach profile | Fri, Jan 21 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#1-research-profile)] |
| 2. Project topic | ~~Fri, Feb 04~~</br>_Cancelled; Directly submit pre-proposal on Feb 11_ | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#2-project-topics)]</br>\[[Submission link](https://forms.gle/1KfauCXS5TaBYrDx6)] |
| 3. Project pre-proposal | Fri, Feb 11 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#3-project-pre-proposal)]</br>\[[Submission link](https://forms.gle/iomkqgweRNjDt7Cd8)] |
| 4. Project proposal | Fri, Feb 18 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#4-project-proposal)]</br>\[[Submission link](https://forms.gle/AWqew1ayN2NWZCuf6)] |
| 5. Proposal reviews | Fri, Feb 25 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#5-proposal-reviews)]</br>\[[Submission link](https://forms.gle/qmPurB7QDMXDsn95A)] |
| 6. Mid-term project presentation recordings | Fri, Mar 18 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#6-mid-course-project-presentations)]</br>\[[Submit link in the class schedule google doc]] |
| 7. Mid-course Project presentation reviews | Fri, Mar 25 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#7-mid-course-project-presentation-reviews)]</br>\[[Submission link](https://forms.gle/HB74nTqyYt7gvEib7)] |
| 8. Final project report | Fri, Apr 29 | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#9-final-project-report)]</br>\[[Submission link](https://forms.gle/)] |
| 9. Final project poster presentations | _Note:_ Diff. day/time \| Tue, May 03, 12:45 – 2:45p | \[[More info](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/course-activities-grading.md#10-final-project-poster-presentations--thr-apr-29-1245--245p)]</br>\[[Submission link](https://forms.gle/)] |

#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#home-of-compbio2022) ]

### Student Hours
**Thursdays 5–6pm**

I will block these time from my schedule and be present for you to talk to me one-on-one. Couple of things to note:
1. While I'm happy to chat with you over zoom, many times, just sending me a message on Slack with your questions/concerns might work as well. So, if you have specific Qs in mind, just shoot me a message and let's see if we can resolve it then and there.
2. If you would indeed like to meet over zoom, please try to meet me during this time. But, don't worry if you can't make it during this window for some reason. Again, just send me a message on Slack and we'll find a time that works for both of us.

#### \[ [Top](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/README.md#home-of-compbio2022) ]

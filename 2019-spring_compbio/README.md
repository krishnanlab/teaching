# CMSE 491/890: Bioinformatics and Computational Biology

* [Description](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#description)
* [Instructor Contact Information](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#instructor-contact-information)
* [Course Outline and Materials](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#course-outline-and-materials)
* [Schedule, Location, Calendar, and Office Hours](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#schedule-location-calendar-and-office-hours)
* [Website and Communication](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#website-and-communication)
* [Course Activities](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#course-activities)
* [Grading Information](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#grading-information)
* [Attendance, Conduct, Honesty, and Accommodations](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#attendance-conduct-honesty-accomodations)


## Description
This course is an introduction to contemporary topics in bioinformatics and computational biology, dealing with combining large-scale data and modern analytical techniques to gain biological/biomedical insights. In each topic, centered around a recent paper, we will discuss the major biological & biomedical questions, explore the relevant molecular/genomics/biomedical datasets, and understand the underlying statistical, probabilistic, & machine-learning approaches.

Students will learn how to formulate problems for quantitative inquiry, design computational projects, understand and think critically about data & methods, communicate research findings, perform reproducible research, and practice open science. Students will apply all these by carrying out a project, presenting their project in class, and submit a report at the end of the course.

**Note**  
Open to both undergraduate and graduate students. Counts toward the CMSE minor, graduate certificates, and dual PhD. Please email Heather Johnson at john1451@msu.edu for an override.

**Prerequisites**  
CMSE 201 or CMSE 301-304 or equivalent with programming experience and two semesters of introductory biology (LB 144 and 145 OR BS 161 and 162 OR BS 181H and 182H, or equivalent).
Statistics at the level of STT 231 is strongly recommended.

Basically, it would be assumed that you:
- know how to code in one of the mainstream languages like Python or R,
- have an understanding of basic statistics and probability, and
- have studied basic genetics, molecular biology, and cellular biology.

## Instructor Contact Information
Arjun Krishnan | ...
:------------ | :------------
Affiliation | Dept. Computational Mathematics, Science, and Engineering</br>Dept. Biochemistry and Molecular Biology
Office | 2507H Engineering Building
Contact | Email: arjun@msu.edu</br>Twitter: [@compbiologist](https://twitter.com/compbiologist)</br>Website: https://thekrishnanlab.org

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-890-bioinformatics-and-computational-biology) ]

## Course Outline and Materials
### Major Topics
1. Genome assembly & annotation
    * Assembly with de Bruijin graphs; Gene prediction with Hidden Markov models
2. Sequence alignment; Pattern finding
    * Local/global alignment with dynamic programming; Substitution matrices; BLAST
3. Comparative genomics; Phylogenomics
    * Whole genome alignment; Suffix trees; Molecular evolution; Tree construction
4. Genetic variation; Quantitative genetics
    * GWAS, Regularized linear regression; Statistical inference, Multiple testing
5. Regulatory genomics
    * Gibbs sampling; Expectation-Maximization
6. Functional genomics
    * Differential expression; Functional enrichment analysis; Clustering; Intro to ML
7. Single-cell genomics
    * Missing value imputaion; Dimensionality reduction; Trajectory inference; Spatial reconstruction
8. Molecular dynamics; Protein structure prediction
    * Molecular simulation; Maximum entropy modeling
9. Modeling cellular pathways; Digital evolution
    * Dynamical simulation, State Space, Bifurcation; Linear programming; Artificial life
10. Biological networks
    * Measuring associations; Network inference; Graph theory, Label propagation

Each topic is covered over two "Lecture" classes and a "Paper discussion" class.

### Special Topics
Along with these, we are going to cover the following *special topics* as 1-class lecures:
* Cancer genomics
* Genome engineering
* Personal genomics

### Primers
And, we will also have practical and conceptual primers:
* DataSci Primers: Data wrangling, exploratory data analysis, & visualization in R/Python; R/Jupyter notebooks; Version control w/ Git.
* ML Primers: Machine learning; Deep learning; Applications in biology & medicine.

### Recommended Materials
[This document](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Additional-learning-resources.md) contains links to a bunch of excellent resources for brushing-up your Unix, Python/R, Statistics, and Biology.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-890-bioinformatics-and-computational-biology) ]

## Schedule, Location, Calendar, and Office Hours
S/L | Info
:------------ | :------------
Schedule | Mon, Wed, and Fri</br>11:00 am - 12:10 pm
Location | 351 Natural Sciences Bldg

### Calendar
This calendar contains the class schedule and the links to the lecture slides and reading materials. Download the detailed schedule as a [PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/CMSE-491-890_Spring-2019_Schedule.pdf).

| ID | Date | Module | Topic | Learning Materials |
|:---------|-------------:|:-------------------------|:------------------------|:------------------------|
| W01M | Jan 07 | Introduction & Overview | Course overview | Lecture 1 \[[PDF](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio/Lectures/Lecture1.pdf)]</br>[Incoming survey](https://bit.ly/ss19-compbio_incoming-survey) |
| W01W | Jan 09 | Introduction & Overview | Getting started in bioinformatics & computational biology – Part 1 | Lecture 2 & 3 \[[PDF](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio/Lectures/Lecture2-3.pdf)] |
| W01F | Jan 11 | Introduction & Overview | Getting started in bioinformatics & computational biology – Part 2 |  |
| W02M | Jan 14 | Genome assembly & annotation | de Bruijin graphs; Suffix trees | Lecture 4 \[[PDF](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio/Lectures/Lecture4.pdf)] |
| W02W | Jan 16 | Genome assembly & annotation | Hidden Markov models | Lecture 5 \[[PDF](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio/Lectures/Lecture5.pdf)]  | 
| W02F | Jan 18 | Genome assembly & annotation | Paper discussion | Velvet: Algorithms for de novo short read assembly using de Bruijn graphs \[[Journal](http://genome.cshlp.org/content/18/5/821)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Zerbino2008_velvet-assembler.pdf)]</br>Student presentation \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Presentations/Velvet_Justin.pdf)] |
| W03M | Jan 21 | No Class |  |  |
| W03W | Jan 23 | Sequence alignment & pattern finding | Dynamic programming | Lectures 6-7 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture6-7.pdf)] |
| W03F | Jan 25 | Sequence alignment & pattern finding | Substitution matrices; BLAST; Paper discussion | Basic local alignment search tool \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Altschul1990_BLAST.pdf)]</br>Steps used by the BLAST algorithm \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Mount2007_steps-used-by-blast.pdf)]</br>Student presentation \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Presentations/BLAST_Zoe-Hakim.pdf)] |
| W04M | Jan 28 | Comparative genomics; Phylogenomics | Whole-genome alignment; Suffix trees | Lectures 8-9 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture8-9.pdf)] |
| W04W | Jan 30 | Comparative genomics; Phylogenomics | Molecular evolution; Tree construction | See link above |
| W04F | Feb 01 | Comparative genomics; Phylogenomics | Paper discussion | Whole-genome alignment:</br>- MUMmer1: Alignment of whole genomes \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC148804/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Delcher1999_MUMmer1.pdf)]</br>- MUMmer2: Fast algorithms for large-scale genome alignment and comparison \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC117189/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Delcher2002_MUMmer2.pdf)]</br>- MUMmer3: Versatile and open software for comparing large genomes \[[Journal](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2004-5-2-r12)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Kurtz2004_MUMmer3.pdf)]</br>- MUMmer4: A fast and versatile genome alignment system \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005944)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Marc%CC%A7ais2018_MUMmer4.pdf)] |
| W05M | Feb 04 | Genetic variation & quantitative genetics | GWAS, Statistical inference, Multiple testing | Lectures 10-11 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture10-11.pdf)] |
| W05W | Feb 06 | Genetic variation & quantitative genetics | Regularized linear regression | See link above |
| W05F | Feb 08 | Genetic variation & quantitative genetics | Paper discussion |  Genome-wide association studies and multiple hypothesis correction:</br>- Mining Genome-Wide Genetic Markers \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002828)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Zhang2012_mining-genomewide-genetic-markers.PDF)]</br>- Genome-Wide Association Studies \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002822)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Bush-Moore2012_GWAS.PDF)]</br>- How does multiple testing correction work? \[[Journal](https://www.nature.com/articles/nbt1209-1135)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Noble2009_primer-multiple-testing-correction.pdf)]</br>- Statistical significance for genomewide studies \[[Journal](http://www.pnas.org/content/100/16/9440.full)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Storey-Tibshirani2003_statistical-significance-genomewide-studies.pdf)] |
| W06M | Feb 11 | Regulatory genomics | Finding regulatory motifs; Expectation-Maximization | Lectures 12-13 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture12-13.pdf)]  |
| W06W | Feb 13 | Regulatory genomics | Gibbs sampling |  |
| W06F | Feb 15 | Regulatory genomics | Paper discussion | - What are DNA sequnence motifs? \[[Journal](https://www.nature.com/articles/nbt0406-423)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Dhaeseleer2006_what-are-dna-motifs.pdf)]</br>- How does DNA sequence motif discovery work? \[[Journal](https://www.nature.com/articles/nbt0806-959)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Dhaeseleer2006_how-does-motif-discovery-work.pdf)]</br>- What is the Expectation Maximization algorithm? \[[Journal](https://www.nature.com/articles/nbt1406)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Do-Batzoglou2008_what-is-EM.pdf)]</br>- Practical Strategies for Discovering Regulatory DNA Sequence Motifs \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0020036)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/MacIsaac-Fraenkel2006_strategies-for-discovering-motifs.pdf)] |
| W07M | Feb 18 | Functional genomics | Clustering; Intro to machine learning | Lectures 14-15 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture14-15.pdf)] |
| W07W | Feb 20 | Functional genomics | Differential expression; Functional enrichment analysis | |
| W07F | Feb 22 | Functional genomics | Paper discussion | A module map showing conditional activity of expression modules in cancer \[[Journal(https://www.nature.com/articles/ng1434)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Segal2004_cancer-module-map.pdf)] |
| W08M | Feb 25 | DataSci Primers | Data wrangling & visualization in R/Python – Part 1 | Note change of location:</br>R Camp: WH B110G</br>Python Camp: WH B110F |
| W08W | Feb 27 | DataSci Primers | Data wrangling & visualization in R/Python – Part 2 | Note change of location:</br>R Camp: WH B110G</br>Python Camp: WH B110F |
| W08F | Mar 01 | DataSci Primers | Exploratory data analysis | Note change of location:</br>R Camp: WH B110G</br>Python Camp: WH B110F |
| W09M | Mar 04 | No class (Spring break) |  |  |
| W09W | Mar 06 | No class (Spring break) |  |  |
| W09F | Mar 08 | No class (Spring break) |  |  |
| W10M | Mar 11 | Mid-course project presentations | Lightning talks |  |
| W10W | Mar 13 | Mid-course project presentations |  |  |
| W10F | Mar 15 | Mid-course project presentations |  |  |
| W11M | Mar 18 | ML Primers | Machine learning – Supervised/Unsupervised learning; Model validation & selection |  |
| W11W | Mar 20 | ML Primers | Machine learning – Evaluation metrics; ML algorithms | |
| W11F | Mar 22 | ML Primers | ML/DL Applications | Lectures 18 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture16-18.pdf)] |
| W12M | Mar 25 | Single-cell genomics | Missing value imputaion; Dimensionality reduction | Lectures 19-20 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture19-20.pdf)] |
| W12W | Mar 27 | Single-cell genomics | Trajectory inference; Spatial reconstruction | See above. |
| W12F | Mar 29 | Single-cell genomics | Paper discussion | The dynamics and regulators of cell fate decisions are revealed by pseudotemporal ordering of single cells \[[Journal](https://www.nature.com/articles/nbt.2859)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Trapnell2014_scrnaseq-pseudotime-monocle.pdf)] |
| W13M | Apr 01 | Molecular dynamics; Protein structure prediction | Molecular simulation | Lectures 21-22 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture21-22.pdf)] |
| W13W | Apr 03 | Molecular dynamics; Protein structure prediction | Maximum entropy modeling | See above. |
| W13F | Apr 05 | Molecular dynamics; Protein structure prediction | Paper discussion | - Predicting protein structures with a multiplayer online game \[[Journal](https://www.nature.com/articles/nature09304)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Cooper2010_Foldit.pdf)]</br>- [GROMACS tutorial](http://md.chem.rug.nl/~mdcourse/index.html) |
| W14M | Apr 08 | Modeling cellular pathways; Digital evolution | Dynamical simulation, State Space, Bifurcation | Lecture 23 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture23.pdf)] |
| W14W | Apr 10 | Modeling cellular pathways; Digital evolution | Metabolic reconstruction; Contraint-based modeling | Lecture 24 \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Lectures/Lecture24.pdf) |
| W14F | Apr 12 | Modeling cellular pathways; Digital evolution | Paper discussion | - Construction of a genetic toggle switch in E. coli \[[Journal](https://www.nature.com/articles/35002131)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Gardner2000-Ecoli-genetic-toggle-switch.pdf)] |
| W15M | Apr 15 | Biological networks | Measuring associations; Network inference |  |
| W15W | Apr 17 | Biological networks | Graph theory, Label propagation |  |
| W15F | Apr 19 | Biological networks | Paper discussion |  |
| W16M | Apr 22 | Cancer genomics | Overview |  |
| W16W | Apr 24 | Genome engineering | Overview |  |
| W16F | Apr 26 | Personal genomics | Overview |  |
| W17M | Apr 29 | Final project presentations | One of these days: Poster presentations |  |
| W17W | May 01 | Final project presentations | One of these days: Poster presentations |  |
| W17F | May 03 | Final project presentations | One of these days: Poster presentations |  |

#### Project deadlines
Item | Due date
:--- | -------:
Project profile | W Jan 16
Project topic | F Feb 01
Project pre-proposal | M Fri 11
Project proposal | W Feb 20
Proposal reviews | F Mar 01
Mid-term project proposal presentations | M Mar 11</br>W Mar 13</br>F Mar 15
Review response | Th Mar 14</br>Sa Mar 16</br>M Mar 18
Mid-course project report | F Mar 29
Final project report | M Apr 29
Final project presentations | W May 1 or F May 3

### Office Hours
Tuesdays 5–7pm

I will block this time from my schedule and be present in my office.

Couple of things to note:
1. While I'm happy to chat with you in person, many times, just sending me a message on Slack with your questions/concerns might work as well. So, if you have specific Qs in mind, just shoot me a message and let's see if we can resolve it then and there.
2. If you would indeed like to meet in person, please try to meet me during this time. But, don't worry if you can't make it during this window for some reason. Again, just send me a message on Slack and we'll find a time that works for both of us.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-890-bioinformatics-and-computational-biology) ]

## Website and Communication

### Course website
This [GitHub repo](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio) will serve as the course website.  

### Communication
The primary mode of communication in this course (including major announcements), will be the [course Slack account](https://cmse-compbio-ss19.slack.com). All of you should have invitations to join this account in your MSU email.  

**Emails**  
Although the bulk of the communication will take place via Slack, at times (rarely), we will send out important course information via email. This email is sent to your MSU email address (the one that ends in “@msu.edu”). You are responsible for all information sent out to your University email account, and for checking this account on a regular basis.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-890-bioinformatics-and-computational-biology) ]

## Course Activities

### Assignments
For each topic, you will be given an assignment after the topic's "lecture" class that you are required to work on. Links to the assignment will be posted on this page next to the topic on the [Calendar](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio#calendar) and specific instructions will be posted on Slack.

Along with the assignment, you are required to turn-in a 1-page report of that week's paper containing a critical and thorough analysis of a specific section/figure with thefollowing four sections:
1. _Data_
    - What data did they use to perform the analysis presented in the figure?
    - Where did each piece of data come from?
2. _Methods_
    - What techniques and algorithms did they use?
    - Does the paper have a detailed description of how to perform this analysis, enough for someone to repeat that analysis?
    - Does the paper have source code to reproduce the presented results?
3. _Evaluation_
    - What are the measures/metrics plotted for each figure panel?
    - How is the success of each analysis evaluated?
4. _Conclusions_
    - Are the conclusions you draw from the figure in agreement with those drawn by the authors?

This report is due _before_ the topic's "Paper discussion" class. Points will be deducted for reports shorter or longer than 1-page. Wrong papers will be graded as zero.

### Class Participation
In general:
- Do the pre-class assignments and additional readings.
- Show up to class.
- Work in groups during in-class discussion sessions.
- No one will have the perfect background: **Ask questions** about computational or biological concepts.
- Correct me when I am wrong.

#### Paper discussion
You will also take turns to present the assigned paper during each topic's "Paper discussion" class. Make sure you sign-up.
- Two students together present each paper.
- The presentation should focus on the computational/analytical parts, not necessarily on detailed biological background & conclusions.
    1. What is the problem the authors are trying to solve? [description of the problem along with why it is important]
    2. What are their claims about the _then_ current practices and their limitations? [existing approaches to solve the problem & their pros-and-cons]
    3. What’s their approach? What’s new in it and what is their rationale for it being potentially successful? [description of the *new ideas*, their *merits* in comparison to existing ones, and *rationale*]
    4. What are the major contributions and limitations of this paper?
    5. What are some open questions and next steps (for addressing the limitations)?
- The two students will also make a note of all the points discussed in the class during the presentation, write-up them up by working with me, and post the discussion on [PubPeer](https://pubpeer.com/).

### Scribing
Each topic's "Lecture" class will have a dedicated scribe who will take notes on the lecture, work with Arjun to refine the notes, and circulate a final version to the rest of the class.
- We will use [stackedit](https://stackedit.io) + Google Drive to create notes and then publish them on GitHub.
- Scribe should submit their draft of their notes within 3 days after lecture. I will read those notes and give comments/suggestions.
- The final scribe notes that incorporates all the comments should be submitted within 6 days after lecture.

### Semester Project and Presentation
A major goal of this course is to prepare you for performing original research in computational biology, and for effectively presenting your ideas and research. The semester project will serve as the most practical way to do exactly that.

Projects can take any one of the following flavors:
- Design and implement a new computational method for a task in biology
- Improve an existing method
- Perform an evaluation of several existing methods
- Develop a fully-reproducible documentation and codebase for an existing analysis in a paper

The outcomes of this semester-long project should include:
1. Well-documented code to:
    - download and process the data
    - perform the computational analysis and generate all the results
    - visualize the results as various plots
2. Detailed final report containing the following sections:
    - Abstract
    - Introduction
    - Data and Methods
    - Results and Discussion
    - Limitations and Future Directions
    - References
    - Glossary
3. A poster that describes your project - motivation, exact problem, approach, results, discussion & conclusions, limitations & future direcrtions, acknowledgements.

There are several [project deadlines](https://github.com/krishnanlab/teaching/tree/master/2019-spring_compbio#project-deadlines) throughout the course that will help you stay on track, allowing you to complete a substantial project.

1. Describe your previous research, areas of research interest in bioinformatics / computational-biology, type of project that best fits your interests. Post this description in a profile that lets your classmates know you. Project profile due **W Jan 16**.

2. Discuss with Arjun (and any other PI) and read recent papers. Briefly describe project ideas. Project topic due **F Feb 01**.

3. Prepare a two-page pre-proposal (Page1: text; Page2: figures & references). Project pre-proposal due **M Fri 11**.

4. Write full proposal. Project proposal due **M Feb 25**.
    - Length: 5-pages (incl. figures & ref; sections listed below)
    - Sections:
        - *Background, goals, & significance* (what is the problem you are hoping to address; what is the current approach & its limitations; what will you do & why is it likely to succeed; if successful, what is the broader impact)
        - *Datasets* (what datasets will you use; where are they from; what exactly do they contain; how are they formatted)
        - *Computational methods/approach* (what are the analytical methods; what are the specific software implementations you'll use; include your flowchart here)
        - *Evaluations* (how will you evaluate the results that you get; think in terms of how to test if a) your approach is working correctly without errors and b) your results make quantitative/biological sense and are meaningful)
        - *Potential challenges & alternative approaches* (what are some assumptions you are making that can fail; what are some potential limitations of your dataset or approach that might prevent you from achieving your aforementioned goals; what will you do as alternatives if you hit those limitations)
        - *Specific milestones* (what is the list of specific results/outcomes you will work on getting)

5. Review proposals. Discuss proposal with Arjun. Reviews due **F Mar 01**.

6. Mid-course project presentations on **M Mar 11**, **W Mar 13**, and **F Mar 15**.
    - In addition to the usual things – background, problem, approach, etc. – I would like you to also present the following:
        - Clear flowchart of approach.
        - Thorough exploration of data (tables & plots to showcase your datasets)
        - Method/software usage & I/O format.
        - Preliminary analysis with simple baselines, samples datasets, and toy examples (discuss with me to determine what this means for your project; doing this over slack is fine).

7. Address peer evaluations, revise aims, scope, list of final goals & deliverables. Meet with Arjun. Response is due 3 days after mid-course presentation: **Th Mar 14**, **Sa Mar 16**, or **M Mar 18**.

8. Continue making substantial progress on proposed milestones. Write the first-draft of final report. Meet Arjun to discuss all results and get feedback on the draft. Mid-course project report due **F Mar 29**.

9. Complete milestones, finalize results, figures, write-up in conference publication format. As part of the report, comment on your overall project experience. Final project report due **F Apr 26**.

10. Final project presentations will take place on **M Apr 29**.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-bioinformatics-and-computational-biology) ]

## Grading Information
Activity | Percentage
:----- | ---------:
Assignments | ~35%
Class participation | ~15%
Scribing | ~10%
Project | ~40%

### Grading Scale
Point | Percentage
----: | ---------:
4.0 | ≥ 90%
3.5 | ≥ 85%
3.0 | ≥ 80%
2.5 | ≥ 75%
2.0 | ≥ 70%
1.5 | ≥ 65%
1.0 | ≥ 60%
0.0 | < 60%

**Note:** Grades will not be curved. Your grade is based on your own effort and progress, not based on competition with your classmates.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-bioinformatics-and-computational-biology) ]

## Attendance, Conduct, Honesty, and Accommodations

### Class Attendance
This class is heavily based on material presented and worked on in class, and it is critical that you attend and participate fully every week! Therefore, class attendance is absolutely required. An unexcused absence will result in zero points for the day. Arriving late or leaving early without prior arrangement with the instructor of your session counts as an unexcused absence. Note that if you have a legitimate reason to miss class (such as job, graduate school, or medical school interviews), you must arrange this ahead of time to be excused from class. Three unexcused absences will result in the reduction of your grade by one step (e.g., from 4.0 to 3.5), with additional absences reducing your grade further at the discretion of the course instructor.

### Code of Conduct
All conduct should serve the singular goal of sustain a friendly, supportive, and fun environment where we can do our best work and have a great time doing it.
* Do work that you’re proud of, from the smallest piece of code to the entire project.
* Be supportive of your classmates; respect each others' strengths, weaknesses, differences, and beliefs.
* Communicate openly & respectfully with everyone in the class.
* Ask for help; at the same time, respect and appreciate others' time and effort.

Respectful and responsible behavior is expected at all times, which includes not interrupting other students, turning your cell phone off, refraining from non-course-related use of electronic devices, and not using offensive or demeaning language in our discussions. Flagrant or repeated violations of this expectation may result in ejection from the classroom, grade-related penalties, and/or involvement of the university Ombudsperson.

I am unequivocally dedicated to providing a harassment-free experience for everyone, regardless of gender, gender identity and expression, age, sexual orientation, disability, physical appearance, body size, race, or religion (or lack thereof). We will not tolerate harassment of colleagues in any form. Behaviors that could be considered discriminatory or harassing, or unwanted sexual attention, will not be tolerated and will be immediately reported to the appropriate MSU office (which may include the MSU Police Department).

### Academic honesty
Intellectual integrity is the foundation of the scientific enterprise. In all instances, you must do your own work and give proper credit to all sources that you use in your papers and oral presentations – any instance of submitting another person's work, ideas, or wording as your own counts as plagiarism. This includes failing to cite any direct quotations in your essays, research paper, class debate, or written presentation. The MSU College of Natural Science adheres to the policies of academic honesty as specified in the General Student Regulations 1.0, Protection of Scholarship and Grades, and in the all-University statement on Integrity of Scholarship and Grades, which are included in Spartan Life: Student Handbook and Resource Guide. Students who plagiarize will receive a 0.0 in the course. In addition, University policy requires that any cheating offense, regardless of the magnitude of the infraction or punishment decided upon by the professor, be reported immediately to the dean of the student's college.

It is important to note that **plagiarism in the context of this course includes, but is not limited to**, directly copying another student's solutions to in-class or homework problems; copying materials from online sources, textbooks, or other reference materials without citing those references in your source code or documentation, or having somebody else do your pre-class work, in-class work, or homework on your behalf. Any work that is done in collaboration with other students should state this explicitly, and have their names as well as yours listed clearly.

More broadly, we ask that students adhere to the Spartan Code of Honor academic pledge, as written by the Associated Students of Michigan State University (ASMSU): "As a Spartan, I will strive to uphold values of the highest ethical standard. I will practice honesty in my work, foster honesty in my peers, and take pride in knowing that honor is worth more than grades. I will carry these values beyond my time as a student at Michigan State University, continuing the endeavor to build personal integrity in all that I do."

### Accomodations
If you have a university-documented learning difficulty or require other accommodations, please provide me with your VISA as soon as possible and speak with me about how I can assist you in your learning.  If you do not have a VISA but have been documented with a learning difficulty or other problems for which you may still require accommodation, please contact MSU’s Resource Center for People with Disabilities (355-9642) in order to acquire current documentation.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/README.md#cmse-491-bioinformatics-and-computational-biology) ]

# CMSE 410/890: Bioinformatics and Computational Biology

* [Description](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#description)
* [Instructor Contact Information](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#instructor-contact-information)
* [Course Outline and Materials](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#course-outline-and-materials)
* [Schedule, Location, Calendar, and Office Hours](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#schedule-location-calendar-and-office-hours)
* [Website and Communication](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#website-and-communication)
* [Course Activities](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#course-activities)
* [Grading Information](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#grading-information)
* [Attendance, Conduct, Honesty, and Accommodations](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#attendance-conduct-honesty-accomodations)
* [Going Online](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#going-online)


## Description
This course is an introduction to the inner-workings of methods in bioinformatics and computational biology: analytical techniques, algorithms, and statistical/machine-learning approaches developed to address key questions in biology and medicine.

In this course, students will also learn how to formulate problems for quantitative inquiry, design computational projects, think critically about data & methods, do reproducible research, and communicate findings.

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

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]


## Course Outline and Materials
### Major Topics

#### Biological topics
1. Genome assembly & annotation
2. Sequence alignment & pattern finding
3. Comparative genomics; Phylogenomics
4. Genetic variation & quantitative genetics
5. Regulatory genomics
6. Functional genomics
7. Single-cell genomics
8. Molecular dynamics; Structure prediction
9. Modeling cellular pathways
10. Whole-cell models; Digital evolution
11. Biological networks

#### Computaitonal / Analytical topics
* de Bruijin graphs; Hidden Markov models
* Dynamic programming; Substitution matrices; Fast Local Alignment
* Suffix trees; Tree construction
* Regularized linear regression; Statistical inference, Multiple testing
* Gibbs sampling; Expectation-Maximization
* Two-sample tests; One-sided Fisher's exact test; Intro to unsupervised and supervised learning
* Missing value imputation; Dimensionality reduction; Trajectory inference
* Molecular simulation; Maximum entropy modeling
* Dynamical simulation, State Space, Bifurcation; Discrete/Boolean modeling
* Wiring diagrams; Constraint-based modeling; Artificial life and other whole-cell models
* Measuring associations; Network inference; Graph theory, Label propagation

### Primers
Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts:
* Organizing and managing a CompBio project
* Kickstarting and getting help in a CompBio project
* Presenting data and results in a CompBio project

### Recommended Materials
[This document](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Additional-learning-resources.md) contains links to a bunch of excellent resources for brushing-up your Unix, Python/R, Statistics, and Biology.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]


## Schedule, Location, Calendar, and Office Hours
S/L | Info
:------------ | :------------
Schedule | Mon, Wed, and Fri</br>11:00 am - 12:10 pm
Location | 351 Natural Sciences Bldg

### Calendar
This calendar contains the class schedule and the links to the lecture slides and reading materials. Download the detailed schedule as a [PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/CMSE410-890_Spring-2020_Schedule.pdf).

| Day | Date | Module | Topic | Learning Materials |
|:---------|-------------:|:-------------------------|:------------------------|:------------------------|
| Day 01 | Mon, Jan 06 | Introduction, Overview, and Refreshers | Course overview | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day01_lecture.pdf)] |
| Day 02 | Wed, Jan 08 | Introduction, Overview, and Refreshers | Refresher 1: Concepts in statistics & probability |  |
| Day 03 | Fri, Jan 10 | Introduction, Overview, and Refreshers | Refresher 2: Concepts in model building + Intro to Bioinformatics & Computational Biology | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day03_lecture.pdf)] |
| Day 04 | Mon, Jan 13 | Genome assembly & annotation | Assembly with de Bruijin graphs | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day04_lecture.pdf)] |
| Day 05 | Wed, Jan 15 | Genome assembly & annotation | Gene prediction with Hidden Markov models | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day05_lecture.pdf)] |
| Day 06 | Fri, Jan 17 | Genome assembly & annotation | Paper discussion; HMM continued | Velvet: Algorithms for de novo short read assembly using de Bruijn graphs \[[Journal](http://genome.cshlp.org/content/18/5/821)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Zerbino2008_velvet-assembler.pdf)] |
|  | Mon, Jan 20 | No class | Need an extra hour (or two 30-minute slots) to compensate |  |
| Day 07 | Wed, Jan 22 | Sequence alignment & pattern finding | Dynamic programming; Substitution matrices | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day07-08_lecture.pdf)] |
| Day 08 | Fri, Jan 24 | Sequence alignment & pattern finding | Paper discussion; Basic Local Alignment Search Tool | Basic local alignment search tool \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Altschul1990_BLAST.pdf)]</br>Steps used by the BLAST algorithm \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Mount2007_steps-used-by-blast.pdf)] |
| Day 09 | Mon, Jan 27 | Comparative genomics; Phylogenomics | Whole genome alignment; Suffix trees | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day09_lecture.pdf)] |
| Day 10 | Wed, Jan 29 | Comparative genomics; Phylogenomics | Molecular evolution; Tree construction | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day10_lecture.pdf)]  |
| Day 11 | Fri, Jan 31 | Comparative genomics; Phylogenomics | Paper discussion | Whole-genome alignment:</br>- MUMmer1: Alignment of whole genomes \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC148804/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Delcher1999_MUMmer1.pdf)]</br>- MUMmer2: Fast algorithms for large-scale genome alignment and comparison \[[Journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC117189/)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Delcher2002_MUMmer2.pdf)]</br>- MUMmer3: Versatile and open software for comparing large genomes \[[Journal](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2004-5-2-r12)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Kurtz2004_MUMmer3.pdf)]</br>- MUMmer4: A fast and versatile genome alignment system \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005944)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Mar%C3%A7ais2018_MUMmer4.pdf)] |
| Day 12 | Mon, Feb 03 | Genetic variation & quantitative genetics | GWAS, Regularized linear regression | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day12_lecture.pdf)] |
| Day 13 | Wed, Feb 05 | Genetic variation & quantitative genetics | Statistical inference, Multiple testing | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day13_lecture.pdf)] |
| Day 14 | Fri, Feb 07 | Genetic variation & quantitative genetics | Polygenic risk score; Paper discussion |  |
| Day 15 | Mon, Feb 10 | Regulatory genomics | ChIP-seq & Expectation-Maximization | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day15_lecture.pdf)] |
| Day 16 | Wed, Feb 12 | Regulatory genomics | Expectation-Maximization & Gibbs Sampling | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day16_lecture.pdf)] |
| Day 17 | Fri, Feb 14 | Regulatory genomics | Paper discussion | - What are DNA sequnence motifs? \[[Journal](https://www.nature.com/articles/nbt0406-423)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Dhaeseleer2006_what-are-dna-motifs.pdf)]</br>- How does DNA sequence motif discovery work? \[[Journal](https://www.nature.com/articles/nbt0806-959)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Dhaeseleer2006_how-does-motif-discovery-work.pdf)]</br>- What is the Expectation Maximization algorithm? \[[Journal](https://www.nature.com/articles/nbt1406)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Do-Batzoglou2008_what-is-EM.pdf)]</br>- Practical Strategies for Discovering Regulatory DNA Sequence Motifs \[[Journal](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.0020036)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/MacIsaac-Fraenkel2006_strategies-for-discovering-motifs.pdf)] |
| Day 18 | Mon, Feb 17 | Functional genomics | Distance measures; Clustering | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day18_lecture.pdf)] |
| Day 19 | Wed, Feb 19 | Functional genomics | Differential expression; Functional enrichment analysis |  |
| Day 20 | Fri, Feb 21 | Functional genomics | Paper discussion | A module map showing conditional activity of expression modules in cancer \[[Journal](https://www.nature.com/articles/ng1434)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2019-spring_compbio/Papers/Segal2004_cancer-module-map.pdf)] |
| Day 21 | Mon, Feb 24 | Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts | Organizing and managing a CompBio project | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day21_lecture.pdf)] |
| Day 22 | Wed, Feb 26 | Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts | Kickstarting and getting help in a CompBio project | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day22_lecture.pdf)] |
| Day 23 | Fri, Feb 28 | Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts | Kickstarting and getting help in a CompBio project | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day23_lecture.pdf)] |
|  | Mon, Mar 02 | No class | Spring break |  |
|  | Wed, Mar 04 | No class | Spring break |  |
|  | Fri, Mar 06 | No class | Spring break |  |
| Day 24 | Mon, Mar 09 | Bioinformatics & Computational Biology Co-work Sessions | **Diff. time:** 10a–12:15p + **Diff. location:** Holmes Hall, Classroom W5 |  |
| Day 25 | Wed, Mar 11 | Bioinformatics & Computational Biology Co-work Sessions | **Diff. time:** 10a–12:15p + **Diff. location:** Holmes Hall, Classroom W5 |  |
| Day 26 | Fri, Mar 13 | Bioinformatics & Computational Biology Co-work Sessions | **Diff. time:** 10a–12:15p + **Diff. location:** Holmes Hall, Classroom W5 |  |
| Day 27 | Mon, Mar 16 | Mid-course project presentations | Lightning talks |  |
| Day 28 | Wed, Mar 18 | Mid-course project presentations | Lightning talks |  |
| Day 29 | Fri, Mar 20 | Mid-course project presentations | Lightning talks |  |
| Day 30 | Mon, Mar 23 | Single-cell genomics | Missing value imputation; Dimensionality reduction |  |
| Day 31 | Wed, Mar 25 | Single-cell genomics | Trajectory inference; Spatial reconstruction |  |
| Day 32 | Fri, Mar 27 | Single-cell genomics | Paper discussion |  |
| Day 33 | Mon, Mar 30 | Molecular dynamics; Structure prediction | Molecular simulation |  |
| Day 34 | Wed, Apr 01 | Molecular dynamics; Structure prediction | Maximum entropy modeling |  |
| Day 35 | Fri, Apr 03 | Molecular dynamics; Structure prediction | Paper discussion |  |
| Day 36 | Mon, Apr 06 | Modeling cellular pathways | Dynamical simulation, State Space, Bifurcation |  |
| Day 37 | Wed, Apr 08 | Modeling cellular pathways | Discrete/Boolean modeling |  |
| Day 38 | Fri, Apr 10 | Modeling cellular pathways | Paper discussion |  |
| Day 39 | Mon, Apr 13 | Whole-cell models; Digital evolution | Genome-scale metabolic models; Constraint-based modeling |  |
| Day 40 | Wed, Apr 15 | Whole-cell models; Digital evolution | Artificial life and other whole-cell models |  |
| Day 41 | Fri, Apr 17 | Whole-cell models; Digital evolution | Paper discussion |  |
| Day 42 | Mon, Apr 20 | Biological networks | Measuring associations; Network inference |  |
| Day 43 | Wed, Apr 22 | Biological networks | Graph theory, Label propagation |  |
| Day 44 | Fri, Apr 24 | Biological networks | Paper discussion |  |
| Day 45 | Thu, Apr 30 | Final project poster presentations | Poster presentations; **Diff. time:** 12:45pm - 2:45pm |  |

#### Project deadlines
| Task | Due date |
|:-----|---------:|
| Project profile | Wed, Jan 15 |
| Project topic | Fri, Jan 31 |
| Project pre-proposal | Fri, Feb 07 |
| Project proposal | Wed, Feb 19 |
| Proposal reviews | Fri, Feb 28 |
| Mid-term project presentations | Mon, Mar 16; Wed, Mar 18; Fri, Mar 20 |
| Mid-course project report | Fri, Mar 27 |
| Final project report | Fri, Apr 26 |
| Final project poster presentations | Thu, Apr 30 |

### Office Hours
Tue and Wed: 5–6p.

I will block these time from my schedule and be present in my office.

Couple of things to note:
1. While I'm happy to chat with you in person, many times, just sending me a message on Slack with your questions/concerns might work as well. So, if you have specific Qs in mind, just shoot me a message and let's see if we can resolve it then and there.
2. If you would indeed like to meet in person, please try to meet me during this time. But, don't worry if you can't make it during this window for some reason. Again, just send me a message on Slack and we'll find a time that works for both of us.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]


## Website and Communication

### Course website
This [GitHub repo](https://github.com/krishnanlab/teaching/tree/master/2020-spring_compbio) will serve as the course website.  

### Communication
The primary mode of communication in this course (including major announcements), will be the [course Slack account](https://compbio2020.slack.com). All of you should have invitations to join this account in your MSU email.  

**Emails**  
Although the bulk of the communication will take place via Slack, at times (rarely), we will send out important course information via email. This email is sent to your MSU email address (the one that ends in “@msu.edu”). You are responsible for all information sent out to your University email account, and for checking this account on a regular basis.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]


## Course Activities

### Assignments
For each topic, you will be given an assignment after the topic's first "Lecture" class on Monday that you are required to work on and submit before beginning of the "paper discussion" class on Friday the same week. Links to the assignment will be posted on this page next to the topic on the [Calendar](https://github.com/krishnanlab/teaching/tree/master/2020-spring_compbio#calendar) and specific instructions will be posted on Slack.

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

There are several [project deadlines](https://github.com/krishnanlab/teaching/tree/master/2020-spring_compbio#project-deadlines) throughout the course that will help you stay on track, enabling you to complete a substantial project.

1. Describe your previous research, areas of research interest in bioinformatics / computational-biology, type of project that best fits your interests. Post this description in a profile that lets your classmates know you. Project profile due **Wed, Jan 15**.

2. Discuss with Arjun (and any other PI) and read recent papers. Briefly describe project ideas. Project topic due **Fri, Jan 31**.

3. Prepare a two-page pre-proposal (Page1: text; Page2: figures & references). Project pre-proposal due **Fri, Feb 07**.

4. Write full proposal. Project proposal due **Wed, Feb 19**.
    - Length: 5-pages (incl. figures & ref; sections listed below)
    - Sections:
        - *Background, goals, & significance* (what is the problem you are hoping to address; what is the current approach & its limitations; what will you do & why is it likely to succeed; if successful, what is the broader impact)
        - *Datasets* (what datasets will you use; where are they from; what exactly do they contain; how are they formatted)
        - *Computational methods/approach* (what are the analytical methods; what are the specific software implementations you'll use; include your flowchart here)
        - *Evaluation plan* (how will you evaluate the results that you get; think in terms of how to test if a) your approach is working correctly without errors and b) your results make quantitative/biological sense and are meaningful)
        - *Potential challenges & alternative approaches* (what are some assumptions you are making that can fail; what are some potential limitations of your dataset or approach that might prevent you from achieving your aforementioned goals; what will you do as alternatives if you hit those limitations)
        - *Specific milestones* (what is the list of specific results/outcomes you will work on getting)

5. Review proposals. Discuss proposal with Arjun. Reviews due **Fri, Feb 28**.

6. Mid-course project presentations on **Mon, Mar 16**, **Wed, Mar 18**, and **Fri, Mar 20**.
    - Address peer evaluations, revise aims, scope, and list of final goals & deliverables. Meet with Arjun about reviews, revised plan, and progress.
    - In addition to the usual things – background, problem, approach, etc. – I would like you to also present the following:
        - Clear flowchart of approach.
            - Raw data → Preprocessing & quality control → Preliminary/exploratory analysis → Analysis/Model-building steps → Expected outcomes.
        - Thorough exploration and sanity checks of data.
            - Tables & plots to showcase various aspects of your datasets/problem.
        - Method/software.
            - Usage & I/O format for each.
        - Preliminary analysis
            - With simple baselines, samples datasets, and toy examples.

7. Continue making substantial progress on proposed milestones. Write mid-course project report. Mid-course project report due **Fri, Mar 27**.

8. Complete milestones, finalize results, figures, write-up in conference publication format. As part of the report, comment on your overall project experience. Final project report due **Fri, Apr 26**.

9. Final project presentations will take place on **Thu, Apr 30** 12:45pm – 2:45pm in 351 Natural Sciences Bldg.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]


## Grading Information
Activity | Percentage
:----- | ---------:
Assignments | ~35%
Class participation | ~15%
Project | ~50%

### Grading scale
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

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]


## Attendance, Conduct, Honesty, and Accommodations

### Class Attendance & Presence
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

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]

## Going Online
Folks, hope all of you are doing ok in these surely difficult circumstances. I hope you are taking all the precautions to keep you and everyone around you safe and unaffected:
* If you think you came in contact with anyone sick, please self-quarantine for a couple of weeks.
* Try to maintain 2-3m distance from your neighbors. Avoid handshakes/hugs.
* Use hand-sanitizers and wipe surfaces with disinfectant wipes when outside.
* Wash hands frequently and thoroughly with soap, each time for 20+s. Do not touch your face (eyes, nose, mouth) or food until you do so.
* Eat and drink healthy – keep your immune system strong!
* All this is also to avoid being carriers and re-infecting others, especially people more vulnerable than you.

Since we are going completely online for the rest of our semester including the finals, I am making a bunch of adjustments to deliver this class as effectively possible and I will work on helping you master the remaining course material as best I (and you) can in these circumstances. There is a lot in here but read through these carefully.

At the outset:
* The class timeline, including deadlines, remain intact.
* The only change is that we’re going to do everything – my lecture discussions, your Friday paper presentations, office hours, and midterm/final project presentations – via Zoom and Slack.

More on how this is going to happen is detailed below.

### 1. Important Links
#### Permanent Zoom Meeting ID
Simple link: bit.ly/compbio2020_zoom  
Same as https://msu.zoom.us/j/686840537

#### All Schedules
The google sheet shared on Slack contains the schedule/assignments for:
- Paper presentations
- Midterm/Final project presentations
- Office hours (appointments)

### 2. Zoom Best Practices
* If you haven’t done so already, please register your MSU Zoom account http://msu.zoom.us/
* Please use a headphone (if you can) so that we can avoid audio feedback.
* All your microphones will be muted and video will be turned off by default.
* Use the chat feature to ask questions or provide comments. I will make sure I look and respond to them.
* You can "raise your hand” on Zoom when you wish to talk and I will unmute you.

### 3. Midterm Presentations – March 16, 18, 20
We are going to use the Zoom meeting room.
* Check the “Mid-term Project Presentations” sheet in the google sheet with the schedule for the details on who is presenting when.
* Please log-in in a timely manner because we are on a tight schedule.
    * Each of you gets 6 min to talk and another 3 min for Q&A.
* By default, everyone will be on mute except the speaker.
* When it is your turn to present, I will unmute you and you can share your screen to present.
* The rest of us will listen and post questions/comments on chat. The speaker will look through the chat and answer questions one by one.
* Remember: presenting remotely over Zoom sitting all by yourself is pretty odd and lonely. So, it is up to the rest of us to encourage each other by engaging with the speaker as much as possible via questions/comments.

### 4. Lectures
We are going to use the Zoom meeting room.
* By default, everyone will be on mute except me.
* I will share my screen with the lecture slides.
* I will also share the lecture slides beforehand on the class website so that you can follow along better.
* It is more important now (online) than before (in-person) to stop me and ask questions and/or provide your thoughts. If you’re confused about something I’m presenting, it is extremely likely that others are also confused about that. So, you will be helping a lot of people by stopping me to ask questions and clarify things.
* As and when you think of them, post your questions/comments on chat. I will look through the chat window and answer questions as they come.
* As usual, I will pause several times to ask questions. When I do so, I will expect many of you to chime-in via chat to give me brief answers. Based on what I see, I may umute and ask specific individuals to elaborate.
* I will keep my input volume high to ensure that what I’m saying is clear. If I’m at a high volume, you can always turn down your audio; it’s harder for you to turn it up enough if I speak too softly.
* Finally, since it is hard to pay attention to online/zoom lectures on a computer screen, I will also record my lectures as I present them via zoom and share them with you at the end of the day. But, I’m not going to do any slick editing. So, you’ll be subject to the entire zoom session as-is.

### 5. Student Paper Presentations on Fridays
We are going to use the Zoom meeting room and the style will be similar to how you did your mid-term presentations.
* Check the “Paper Presentations” sheet in the google sheet with the schedule.
* By default, everyone will be on mute except the speaker.
* When it is your turn to present, I will unmute you and you can share your screen to present.
* The rest of us will listen and post questions/comments on chat. The speaker will look through the chat and answer questions one by one.
* Remember: presenting remotely over Zoom sitting all by yourself is pretty odd and lonely. So, it is up to the rest of us to encourage each other by engaging with the speaker as much as possible via questions/comments.

### 6. Class Participation
I hope you understand that I’m looking for ways to ensure you’re present and paying attention.
* Please log-in in a timely manner. I would like to see you listed as one of the participants.
* During each lecture, I would like to receive from *each of you*, via chat, at least:
    * One question to clarify something I’m saying, and
    * One answer to a question I’m posing.
* Remember that presenting remotely over Zoom sitting all by yourself is pretty odd, lonely, and lacking in nonverbal feedback (nodding heads, puzzled looks, drowsy eyes, etc.). So, when someone is presenting, as listeners, it is our responsibility to encourage the speaker by engaging with the them as much as possible via questions/comments/answers.
* Finally, I am cognizant of the fact that you are at home/residence and each of you will have a unique circumstance in terms of convenience of working environment, other family-members/roommates, childcare/pet-care needs, spotty internet, etc. All of us will fully accommodate any of this.

### 7. Office Hours
We are going to use Slack video calls to do all our office hours.
* I have added an extra hour during the week. So, now we’ll hold virtual office hours from 5–6 pm on Tuesdays, Wednesdays, and Thursdays.
* Go to the “Office hours” sheet in the google sheet with the schedule and put your name down on the day/time of your choice. Naturally, this will be on a first-come-first-serve basis. I will give you a call at the chosen time.
* We will use this same sheet every week. At the end of each week, I will clear this table and it'll be ready for the next week.

### 8. Final Presentations – April 30
Some preliminary thoughts here. This will be solidified soon.
* Use Zoom to record a 5 min video of your poster presentation and submit by the due date.
* Assigned reviewers will view the video and give scores. A detailed rubric will be provided ahead of time.
* All of us will then meet via Zoom during the Finals hour on April 30 to discuss all the projects. During this time, three others who are not assigned reviewers will ask questions they have prepared.

### 9. Class Timeline
I wish to keep the class timeline, including deadlines, intact but I want to qualify this wish:
* My point is that we should strive to keep the structure the class as much as possible and prevent the class from straying far from what it was intended to be and what you signed-up for.
* I am also aware that, during these difficult circumstances, we all need a simultaneous dose of structure and flexibility.
* So, as always, I am very happy to work with you on a case-by-case basis to figure out different assignments and due dates based on your specific circumstances/needs.

#### Finally, all the physical distancing we are doing to mitigate the spread of infection can lead to a lot of stress. The isolation is not great for mental health and the confinement is not great for physical health. To help you a little in mitigating these effects, here are some additional things we will do as a class.

### 10. Virtual Meetings with Your Learning Group
Take advantage of the in-class learning groups you are part of. I am asking you to meet remotely with your learning group once every week – perhaps on Thursday or before class on Friday – over a video call. You can coordinate the time works for all of you and how you will do the video call. When you meet online, you can:
* Go over the lecture slides for that week and ask/answer questions.
* Discuss the assignment due on Friday.
* Bring unresolved questions to the Friday online class and ask me those Qs.
* Or, just say HI and continue to do your work in the company of your peers.

### 11. Scrum
I have created a #scrum channel in our class Slack. Let's use this channel to do a daily scrum to help each other keep their work – *any school/professional work*, not just what's related to this class – on-track. Include studying, preparation, reading, etc.
* At the beginning of each day you're working, post brief but specific answers to the following three Qs in this channel:
    1. What did you do yesterday? [“Yesterday, I …“]
    2. What will you do today? [“Today, I'm going to …“]
    3. Are there any impediments in your way?
* Note that scrum is not for:
    * Problem-solving or issue resolution.
    * Status updates or evaluating progress.
    * Checking on anyone.
* All issues raised here should be discussed further elsewhere, perhaps one-on-one or in group channels and with the relevant people.

### 12. Health & Workout
I have created a #health-workout channel on our class Slack. Let's use this channel to share our ideas and post our daily plans/goals for keeping up our mental and physical health.
* You can post something at the beginning of the day to motivate yourself and others, and to get help from others to hold you accountable.
* Doesn't have to 100 pushups. Like it is for me, even stretching for 10 min and drinking 1.5L of water is a worthy goal!!

### 13. Fun
I have created a #fun channel on our class Slack. Let's use this channel to share your ideas/plans for engaging in a hobby or just disengaging with a Netflix show.
* Keep them coming as when you find/take-on something new – yoga, online multiplayer games, new TV series, anything!

### 14. Frequently Asked Questions
**Q. Can I connect to zoom by dialing a phone number?**  
A. Yes, here are additional details.
```
One tap mobile
+16468769923,,686840537# US (New York)
+13126266799,,686840537# US (Chicago)

Dial by your location
        +1 646 876 9923 US (New York)
        +1 312 626 6799 US (Chicago)
        +1 669 900 6833 US (San Jose)
        +1 253 215 8782 US
        +1 301 715 8592 US
        +1 346 248 7799 US (Houston)
Meeting ID: 686 840 537
Find your local number: https://msu.zoom.us/u/afiLUb9F3
```

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#cmse-410-890-bioinformatics-and-computational-biology) ]

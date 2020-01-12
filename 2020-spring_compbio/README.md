# CMSE 410/890: Bioinformatics and Computational Biology

* [Description](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#description)
* [Instructor Contact Information](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#instructor-contact-information)
* [Course Outline and Materials](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#course-outline-and-materials)
* [Schedule, Location, Calendar, and Office Hours](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#schedule-location-calendar-and-office-hours)
* [Website and Communication](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#website-and-communication)
* [Course Activities](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#course-activities)
* [Grading Information](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#grading-information)
* [Attendance, Conduct, Honesty, and Accommodations](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/README.md#attendance-conduct-honesty-accomodations)


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
| Day 01 | Mon, Jan 06 | Introduction, Overview, and Refreshers | Course overview + Getting started in computational biology | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day01_lecture.pdf)] |
| Day 02 | Wed, Jan 08 | Introduction, Overview, and Refreshers | Refresher 1: Concepts in statistics & probability |  |
| Day 03 | Fri, Jan 10 | Introduction, Overview, and Refreshers | Refresher 2: Concepts in model building + Intro to Bioinformatics & Computational Biology | \[[Lecture](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Lectures/Day03_lecture.pdf)] |
| Day 04 | Mon, Jan 13 | Genome assembly & annotation | Assembly with de Bruijin graphs |  |
| Day 05 | Wed, Jan 15 | Genome assembly & annotation | Gene prediction with Hidden Markov models |  |
| Day 06 | Fri, Jan 17 | Genome assembly & annotation | Paper discussion; HMM continued | Velvet: Algorithms for de novo short read assembly using de Bruijn graphs \[[Journal](http://genome.cshlp.org/content/18/5/821)] \[[PDF](https://github.com/krishnanlab/teaching/blob/master/2020-spring_compbio/Papers/Zerbino2008_velvet-assembler.pdf)] |
|  | Mon, Jan 20 | No class | Need an extra hour (or two 30-minute slots) to compensate |  |
| Day 07 | Wed, Jan 22 | Sequence alignment & pattern finding | Dynamic programming; Substitution matrices |  |
| Day 08 | Fri, Jan 24 | Sequence alignment & pattern finding | Paper discussion; Basic Local Alignment Search Tool |  |
| Day 09 | Mon, Jan 27 | Comparative genomics; Phylogenomics | Whole genome alignment; Suffix trees |  |
| Day 10 | Wed, Jan 29 | Comparative genomics; Phylogenomics | Molecular evolution; Tree construction |  |
| Day 11 | Fri, Jan 31 | Comparative genomics; Phylogenomics | Paper discussion |  |
| Day 12 | Mon, Feb 03 | Genetic variation & quantitative genetics | GWAS, Regularized linear regression |  |
| Day 13 | Wed, Feb 05 | Genetic variation & quantitative genetics | Polygenic risk score; Statistical inference, Multiple testing |  |
| Day 14 | Fri, Feb 07 | Genetic variation & quantitative genetics | Paper discussion |  |
| Day 15 | Mon, Feb 10 | Regulatory genomics | Gibbs sampling |  |
| Day 16 | Wed, Feb 12 | Regulatory genomics | Expectation-Maximization |  |
| Day 17 | Fri, Feb 14 | Regulatory genomics | Paper discussion |  |
| Day 18 | Mon, Feb 17 | Functional genomics | Differential expression; Functional enrichment analysis |  |
| Day 19 | Wed, Feb 19 | Functional genomics | Intro to unsupervised and supervised learning |  |
| Day 20 | Fri, Feb 21 | Functional genomics | Paper discussion |  |
| Day 21 | Mon, Feb 24 | Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts | Organizing and managing a CompBio project |  |
| Day 22 | Wed, Feb 26 | Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts | Kickstarting and getting help in a CompBio project |  |
| Day 23 | Fri, Feb 28 | Conducting a Bioinfo / CompBio Project: A Practical Primer in 3-parts | Kickstarting and getting help in a CompBio project |  |
|  | Mon, Mar 02 | No class | Spring break |  |
|  | Wed, Mar 04 | No class | Spring break |  |
|  | Fri, Mar 06 | No class | Spring break |  |
| Day 24 | Mon, Mar 09 | Bioinformatics & Computational Biology Co-work Sessions | **Diff. time:** 10a–12:15p + **Diff. location:** TBD |  |
| Day 25 | Wed, Mar 11 | Bioinformatics & Computational Biology Co-work Sessions | **Diff. time:** 10a–12:15p + **Diff. location:** TBD |  |
| Day 26 | Fri, Mar 13 | Bioinformatics & Computational Biology Co-work Sessions | **Diff. time:** 10a–12:15p + **Diff. location:** TBD |  |
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
TBD

I will block this time from my schedule and be present in my office.

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
        - Thorough exploration of data (tables & plots to showcase your datasets)
        - Method/software usage & I/O format.
        - Preliminary analysis with simple baselines, samples datasets, and toy examples (discuss with me to determine what this means for your project; doing this over slack is fine).

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

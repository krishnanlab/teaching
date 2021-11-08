# [Gaps, Missteps, and Errors in Data Analysis](https://github.com/krishnanlab/teaching/edit/master/2021-fall_statgaps)
CMSE 890-310 | BMB 961-301

>[Home, Schedule](https://github.com/krishnanlab/teaching/edit/master/2021-fall_statgaps/README.md)  
>[Website and Communication](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/website-communication.md)  
>[Course Activities and Grading](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/course-activities-grading.md)  
>[Presence, Conduct, Honesty, and Accommodations](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/policies.md)  
>Frequently Asked Questions


# Frequently Asked Questions

## Why was this course developed?
As many parts of biological and biomedical research are becoming data-intensive, the typical graduate training in this area involves courses in coding and statistics. In these courses, students learn the array of summary statistics and hypothesis tests available and the functions in R or Python to wrangle data, make plots, calculate various statistics, and perform different tests. However, students face a significant challenge when trying to apply these learnings to novel research questions and new complex datasets.

This is because such an application requires them to know:  
1. What the practical definitions of various concepts and their relationships are,  
2. When and why they are applied in certain situations and not others,  
3. What is a robust sequence of actions to take when applying them to data,  
4. How to judiciously interpret the results, and, finally,  
5. How to clearly and transparently communicate the findings.  

Currently, most students learn these ideas only by piecing together a mental model of the “acceptable/standard/best practices” in their field based on bits information from their mentors, peers, and – often – published papers.

Towards addressing this challenge, I developed this short course focused on discussing common misunderstandings and typical errors in the practice of statistical data analysis, and providing a mental toolkit for critically thinking about statistical methods and results. The course builds on introductory statistics and coding, and includes several hands-on exercises.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## Will this course teach me concepts in statistics?
There are already plenty of existing courses at MSU that teach introductory, intermediate, and advanced statistics.
* You can go to [Course Descriptions](https://reg.msu.edu/Courses/Search.aspx) and search using "statistics" under Keyword Search to get the full list. Statistics at the level of STT 231 is strongly recommended before taking this course.
* You can find recommended free online resources [here](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/preparatory-materials.md).

Teaching statistics will be left to these courses and it will be assumed that you have taken one of these courses (or something equivalent) to learn (≥ introductory) statistics in a traditional manner (which is important without a doubt!).

This is a non-traditional course that is aimed at discussing what happens – issues that crop-up and nuances that become germane – when the ideas from the traditional courses are applied to actual research, messy data, and real-world problems.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## Why is coding (in languages like R or Python) a pre-requisite for this course?
The goal of this course is to create opportunities for developing a strong intuition behind many concepts in statistical data analysis, which will take precendence to, motivate, and solidify the related formulae and terminologies. Now, short of starting with a question and mathematically *deriving* the concepts/formulae, whenever possible, this *StatGaps* course takes the approach of using programming to implement statistical ideas on real/simulated data and observe the results to build an intuition behind various concepts.

If you would like introductory courses in programming (in R or Python) and in how to do statistical analysis in R or Python, please ckeckout CMSE 201-202 or CMSE 890 301-304.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## What are some specific coding skills I would need for this class?
In this class, you will be writing code to read-in datasets, wrangle them into a convenient format, calling some common statistical functions from standard packages/libraries, implementing some simulations/tests (which will involve random number generation and writing for/while loops), and making plots (scatterplot, histograms, boxplots, etc.).
This means knowing the following depending on your language of choice:  
- **R**: tidyverse (readr, dplyr, ggplot2), calculating summary statistics (e.g. mean/median, std-deviation/variance, correlation), generating random numbers (e.g. `runif`, `rnorm`), and writing `for` & `while` loops.
- **Python**: pandas (data wrangling), seaborne (data visualization), numpy for calculating summary statistics (e.g. mean/median, std-deviation/variance, correlation) and generating random numbers, and writing `for` & `while` loops.

You can find a few recommended free online resources for learning these skills [here](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/preparatory-materials.md).

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## Can this course be taken remotely?
Yes! This class will be streamed live via a Zoom link. Details will be available via the class Slack account.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## I'm a postdoc and I would like to just attend the class to learn for myself - no need for credits or anything. Is that possible?
Yes! To provide some context: this short course is part of an extensive [Bioinformatics education program](https://cmse.msu.edu/academics/bioinformatics-program/) we run out of [CMSE](https://cmse.msu.edu). Postdocs (or any MSU-affiliates who are not registered students) can audit any of these Bioinformatics modules for a small fee. With this StatGaps course, however, since I’m still experimenting with it, especially in terms of taking it to a large scale, I’m open to having postdocs, research/staff scientists, and faculty-members *audit this course for free*. The only things I ask in return is your active engagement with the class and its materials along with providing constructive feedback.  

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## Are there going to be exams?
No! Just assignments.

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


## Will this short course be converted into a regular semester-long course in the future?
May be. There is a lot of benefit for keeping an essential course like this short and crisp. If you are interested in chatting about this and/or helping with developing this course further, do get in touch!

\[ [Top](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/frequently-asked-questions.md#frequently-asked-questions) ]


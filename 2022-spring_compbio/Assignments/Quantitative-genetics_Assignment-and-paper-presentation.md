# Quantitative genetics | Assignment + Paper presentation

This week, the assignment and the student presentations are based on different materials related to genome-wide association studies (GWAS). So, please read carefully.

Links to PDFs are, as usual, available on the [class calendar](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/schedule-lectures-assignments.md#class-calendar).


## Students doing the assignment (aka not presenting)
The assignment this week has **two parts** and you need to submit 2 documents – one PDF and one R/Python notebook – suing [this form](https://forms.gle/26xudYXKPXV9D7TJ6) **before class on Friday, Feb 19**.

### Part 1: Read two short primers on  and answer some Excercise questions at the end of these primers.

1. Read this short article [**Genome-Wide Association Studies**](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002822) and answer the four questions in Section 9 “Exercises”.  
NOTE: Though the answers to these Qs are available in a supplemental text attached to the article, I trust you to not look at it and, instead, answer these questions by yourself.

2. Read this article [**Mining Genome-Wide Genetic Markers**](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002828) and answer the four questions in Section 7 “Exercises”.  
NOTE: [Just like above] Although the answers to these Qs are available in a supplemental text attached to the article, I trust you to not look at it and, instead, answer these questions by yourself.

You're welcome to write by hand and take a picture. Or, you may use a tablet to do this. Either way, keep your entire response to 2 pages and upload a PDF of those pages.

### Part 2: Write code to run a permutation test and calculate a p-value.
Write R or Python code to similate data and calculate a p-value for the particular SNP slown in the image below based on the pseudocode on the left![pvalue pseudocode](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Assignments/calculating-pvalue.png)

Specifically:
1. Simulate SNP and phenotype data for the particular SNP shown on the right. You can base it on the frequencies of the three different alleles (`CC`, `CT`, and `TT`) in the two populations (control and case, each with 5,000 individuals).
2. Then write code to implement the pseudocode on the left to calculate an empirical p-value for this SNP.

This primer will be helpful to read: [**How does multiple testing correction work?**](https://www.nature.com/articles/nbt1209-1135).

Write your code as an R or Python notebook and submit that file (`*.Rmd` or `*.ipynb`) in the form.


## Presenters
The student presentation will be based on a _different_ paper that describes a nice method to correct for multiple hypothesis testing:
[**Statistical significance for genome-wide studies**](http://www.pnas.org/content/100/16/9440.full)

In your presentation, please make sure you answer the following Qs:
* What is the FPR (false positive rate) & the FDR (false discovery rate)? Explain and express both in terms of the quantities defined in Table 1.
* What is the difference between the P value and the Q value?
* What are \pi_0 and \lamda? How is it estimated given a value of \lamda?
* Why not choose values of \lamda close to 0 or 1? Why is \lamda = 0.5 a generally sensible choice?
* What is the full procedure proposed here for calculating Q values from P values?

In addition to the presentation, complete [this form](https://forms.gle/4svexZXa6NvhwSDT9) this form individually to help me understand the roles each of you played in preparing and making the presentation. Submit this form by **11:59pm Friday, Feb 19**.  
_Note: Every member of the group needs to individually complete the form._

### Notes on preparing the presentation:
* Use other resources beyond the paper to illustrate the problem, including illustrations, etc. Provide citations for the source materials on the slide.
    * For instance, this week, you can use the following primer to understand multiple testing correction works in general: [How does multiple testing correction work?](https://www.nature.com/articles/nbt1209-1135)
* Avoid directly using dense figures directly from papers/other-sources. Instead, split complex multi-part figures in the paper into several slides; Capture/zoom-into parts of figure & annotate with boxes/arrows.
* Avoid large blocks of text. Convert methods to flowcharts & annotate flowcharts.; You’re welcome to draw neatly on paper & photograph it.
* Be prepared to define phrases/terminology on your slide.; Google it, read-up; No problem if any idea/concept is still unclear even after reading. Just bring it up in class & we can discuss.

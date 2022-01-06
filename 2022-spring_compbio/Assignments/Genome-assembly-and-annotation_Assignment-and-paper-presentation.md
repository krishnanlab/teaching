# Genome assembly & annotation | Assignment + Paper presentation

Here are the notes on the second assignment + paper presentation, based on the paper that describes Velvet, one of the first algorithms to use a de Bruijn graph approach to assemble genomes. Links to the paper are available on the [class calendar](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/schedule-lectures-assignments.md#class-calendar).


## Students doing the assignment (aka not presenting)
Your assignment is to answer the questions in [this form](https://forms.gle/yZ5WM4hnx8kK4Bu56) and submit before class on **Friday, Feb 05**.


## Presenters (no need to do/submit the assignment above)
In your presentation, make sure to cover the following five things:
1. What are some specific ways in which the de Bruijn graph used in Velvet differs from the de Bruijn graph we discussed in class (in the lecture slides) in terms of how they are constructed?
2. How does Tour Bus algorithm work to remove bubbles?
3. How does Breadcrumb work to resolve repeats?
4. How is the output assembly of the Velvet algorithm evaluated?
    - In other words, how do the authors measure how good the final genome assembly is? Specifically, how are the simulation experiments done (as presented in Figures 3 & 6) and what are the exact measures that are used to compare the performance of Velvet with other assembly algorithms (as summarized in Table 3).
5. What are Velvet's limitations and how should it be improved? You can find these out by looking-up 2–3 recent papers that cite the Velvet paper and reading just the parts that talk about Velvet.
    - Use [Google Scholar](https://scholar.google.com/) to search for the Velvet paper and click "Cited by" to see newer papers that referenced it.
    - Make sure to include references to these newer papers in your presentation.

### Notes on preparing the presentation:
* Use other resources beyond the paper to illustrate the problem, including illustrations, etc. Provide citations for the source materials on the slide.
* Avoid directly using dense figures directly from papers/other-sources. Instead, split complex multi-part figures in the paper into several slides; Capture/zoom-into parts of figure & annotate with boxes/arrows.
* Avoid large blocks of text. Convert methods to flowcharts & annotate flowcharts.; You’re welcome to draw neatly on paper & photograph it.
* Be prepared to define phrases/terminology on your slide.; Google it, read-up; No problem if any idea/concept is still unclear even after reading. Just bring it up in class & we can discuss.

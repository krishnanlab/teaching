# Genome assembly & annotation | Paper discussion

Your second paper discussion is on the paper that describes _Velvet_, one of the first algorithms to use a de Bruijn graph approach to assemble genomes.

## Paper and resources
The PDF of this article (`Zerbino2008_velvet-assembler.pdf`) is available in the [Paper directory](https://github.com/krishnanlab/teaching/blob/4bfcb0985c5792f52ee9cf60bcbc6643667618c9/2022-spring_compbio/Papers/) (along with PDF of all papers assigned in this class).

## Discussion content and structure
Your paper discussion should cover the following parts and be led by one member from each learning group mentioned beside the title. Use this **[shared google slide document](https://docs.google.com/presentation/d/18PRNV7UCWOEsMZI23EqcSHY5o2LQuy_xsmWp0rXiE1o/edit?usp=sharing)** to prepare your presentation. You will be using these slides on Friday, Feb 04 for the discussion. 

### Part 1 | _Group 1_
1. What are some specific ways in which the de Bruijn graph used in Velvet differs from the de Bruijn graph we discussed in class (in the lecture slides) in terms of how they are constructed?
> Explain based on `Figure 1` and related text.

### Part 2 | _Group 2_
2. At a high level, explain how the _Tour Bus_ algorithm works to remove bubbles and how the _Breadcrumb_ algorithm works to resolve repeats?
> Explain based on `Figure 2` and `Figure 5`, and related text in the paper.

### Part 3 | _Group 3_
3. How is the output assembly of the Velvet algorithm evaluated?
> In other words, how do the authors measure how good the final genome assembly is? Specifically, how are the simulation experiments done (as presented in `Figures 3` & `Figure 6`) and what are the exact measures that are used to compare the performance of Velvet with other assembly algorithms (as summarized in `Table 3`).

### Part 4 | _Group 4_
4. What are Velvet's limitations and how can it be improved?
> After reading the Velvet paper and thinking about limitations, you can find out more pointers by looking-up 2–3 recent papers that cite the Velvet paper and reading just the parts that talk about Velvet.
>    - Use [Google Scholar](https://scholar.google.com/) to search for the Velvet paper and click "Cited by" to see newer papers that referenced it.
>    - Make sure to include references to these newer papers in your presentation.


## Notes on preparing the presentation
* Use other resources beyond the paper to illustrate the problem, including illustrations, etc. Provide citations for the source materials on the slide.
* Avoid directly using dense figures directly from papers/other-sources. Instead, split complex multi-part figures in the paper into several slides; Capture/zoom-into parts of figure & annotate with boxes/arrows.
* Avoid large blocks of text. Convert methods to flowcharts & annotate flowcharts.; You’re welcome to draw neatly on paper & photograph it.
* Be prepared to define phrases/terminology on your slide.; Google it, read-up; No problem if any idea/concept is still unclear even after reading. Just bring it up in class & we can discuss.

# Sequence alignment & search | Paper discussion

Your first paper discussion is on an influential algorithm in bioinformatics for sequence comparison called Basic local alignment search tool, or BLAST.
> Click [this link](https://blast.ncbi.nlm.nih.gov/Blast.cgi) and explore the webserver!

## Paper and resources
Unfortunately, the [1990 paper](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/Altschul1990_BLAST.pdf) that first described this method is quite dense. So, for the paper discussion, I’m asking you to instead read ([Pertsemlidis 2001](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2001-2-10-reviews2002)), an article that reviews the principles, workings, applications and potential pitfalls of the BLAST algorithm in an accessible way.

The PDF of this article (`Pertsemlidis2022_Having-a-BLAST.pdf`) along with PDF of all papers assigned in this class are available in the [Paper directory](https://github.com/krishnanlab/teaching/blob/4bfcb0985c5792f52ee9cf60bcbc6643667618c9/2022-spring_compbio/Papers/).

Three other resources that will be useful for looking up terminology are:
1. BLAST Glossary https://en.wikipedia.org/wiki/BLAST
2. BLAST Handbook: https://www.ncbi.nlm.nih.gov/books/NBK153387/
3. BLAST Practical details https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=BlastHelp

## Discussion content and structure
Your paper discussion should cover the following parts and be lead by one member from each learning group mentioned beside the title. Use this [shared google slide document](https://docs.google.com/presentation/d/1SkIQo38DYiXYdK7XQ8nrAQvoh4iXRGqCpMmWxk83Cyo/edit?usp=sharing) to prepare your presentation. You will be using these slides on Friday for the discussion. 

### Part 1 | _Group 1_
1. How does BLAST work?
> Explain based on `Figure 3` and the text in section `What BLAST does and how it does it` up to just before `Caveat emptor`] in _Pertsemlidis 2001_; no need to cover `Box 2`.

### Part 2 | _Group 2_
2. What does the output from the BLAST search look like and what are the rules to consider when using sequence similarity to infer homology?
> Explain using `Figure 4` and the related text under the subsection `Caveat emptor` in _Pertsemlidis 2001_.

### Part 3 | _Group 3_
3. On the 'Protein BLAST' [webserver](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastp&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome), under the section “Algorithm parameters”:
    - What do the “General Parameters” do?
    - What do the “Scoring Parameters” do?
    - What do the “Filtering & Masking” parameters do?

### Part 4 | _Group 4_
4. What is **_one_** example of contributions of BLAST in **_each_** of the following categories:
    - Approach (thinking-about/framing the local-alignment problem)
    - Algorithmic techniques (any of the cool algorithmic/data-structure ideas)
    - Computational ideas (any storage/search/retrieval tricks)

There are a bunch of statistical measures that are related to BLAST such as Bit score, E-value, and P-value. I will cover these in class on Friday before the paper discussion.

## Notes on preparing the presentation
* Use other resources beyond the paper to illustrate the problem, including illustrations, etc. Provide citations for the source materials on the slide.
* Avoid directly using dense figures directly from papers/other-sources. Instead, split complex multi-part figures in the paper into several slides; Capture/zoom-into parts of figure & annotate with boxes/arrows.
* Avoid large blocks of text. Convert methods to flowcharts & annotate flowcharts.; You’re welcome to draw neatly on paper & photograph it.
* Be prepared to define phrases/terminology on your slide.; Google it, read-up; No problem if any idea/concept is still unclear even after reading. Just bring it up in class & we can discuss.

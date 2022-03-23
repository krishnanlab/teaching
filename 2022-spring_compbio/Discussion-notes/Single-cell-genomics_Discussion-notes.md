# Single cell genomics | Paper discussion

This next paper discussion is an adaptation of a technique called pseudotime ordering to figure out the different developmental stages that cells in a tissue might be based on their single-cell gene expression profiles.


## Papers and resources
The PDF of this article (`Trapnell2014_scrnaseq-pseudotime-monocle.pdf`) is available in the [Paper directory](https://github.com/krishnanlab/teaching/blob/master/2022-spring_compbio/Papers/).


## Discussion content and structure
Your paper discussion should cover the following parts, led by one member from each learning group mentioned beside the title. Use this **[shared google slide document](https://docs.google.com/presentation/d/13HVajy6xRcISmBIfWysMjDruHHJ-NYU2M2vcPLdtYsI/edit?usp=sharing)** to prepare your presentation. You will be using these slides on Friday, Mar 25 for the discussion.

### Two important notes
* Absolutely no need to repeat anything I have covered in the lectures. Your discussion should build off of what I've covered. You're welcome to say things like 'Arjun covered this in class' and then talk about the additional things from this paper.
* The sections are, of course, described in text but your slides should not be walls of text or bullet points. Include summarized, sparse bullet points to cover all the ideas and, for each idea, use images/figures/illustrations from other resources on the internet to talk about those points. Make sure to include a citation on the slide for all the external resources that you end up using.


### Part 1 | _Group 1_
What is the problem of pseudotime inference trajectory with single cell gene expression data?

### Part 2 | _Group 2_
What is Independent Component Analysis (ICA), how is it different from PCA, and how is it used in Monocle?

### Part 3 | _Group 3_
What is the minimum spanning tree (MST) and how is it used in Monocle?

### Part 4 | _Group 4_
After finding the MST, how does Monocle determine an ordering of all the cells along a ‘pseudotime’ axis based on the MST? Intuitively, how does Monocle deal with branches?

## Notes on preparing the presentation
* Use other resources beyond the paper to illustrate the problem, including illustrations, etc. Provide citations for the source materials on the slide.
* Avoid directly using dense figures directly from papers/other-sources. Instead, split complex multi-part figures in the paper into several slides; Capture/zoom-into parts of figure & annotate with boxes/arrows.
* Avoid large blocks of text. Convert methods to flowcharts & annotate flowcharts.; You’re welcome to draw neatly on paper & photograph it.
* Be prepared to define phrases/terminology on your slide.; Google it, read-up; No problem if any idea/concept is still unclear even after reading. Just bring it up in class & we can discuss.

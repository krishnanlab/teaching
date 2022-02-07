# Comparative genomics & phylogenetics | Paper discussion

Developing usable software goes hand-in-hand with developing novel computational methods. Doing this well requires a mixture of skills across biology, experimental technology, methods/algorithms, and hardware/software engineering. If pulling-off a method+software combo like this once is hard, keeping at it – improving on all these aspects and releasing newer versions across decades – is ever harder.

To give you all a taste of what doing something like looks like, I would like you to consider the method+software called MUMmer designed for rapidly aligning large DNA sequences including whole genomes to other genomes. From the time it was releases in 1999, MUMmer remains a widely-used software system. Check out the website for the latest version: https://mummer4.github.io/. This week, I thought it’ll be interesting for all of us to do something different from the previous discussions by looking across the four MUMer papers and thinking about all the ways in which MUMer has changed over time.


## Papers and resources
On the [class calendar](https://github.com/krishnanlab/teaching/tree/master/2022-spring_compbio#class-calendar), you'll see links to the four papers corresponding to the four versions of MUMmer. As usual, the PDFs are available in the [Paper directory](https://github.com/krishnanlab/teaching/blob/4bfcb0985c5792f52ee9cf60bcbc6643667618c9/2022-spring_compbio/Papers/).

Read the four papers and parse them in terms of the following aspects to fill up such a table:
![MUMmer assignment template](https://github.com/krishnanlab/teaching/blob/master/2021-spring_compbio/Assignments/mummer-blank-table.png)

### Notes on what I’m looking for in each aspect:
* _Biological / conceptual_: Biological scenarios & molecular details that are incorporated into the method for the first time in a particular version. These could be assumptions on things like GC-content, repeats, gaps, etc., or they could new findings during this time-period we’re tracing (1999-2018).
* _Technological / experimental_: Improvements/changes due to newer (biological) technologies for sequencing longer & less error-prone reads (that are then assembled into ‘better’ genomic sequences); faster & cheaper technology to sequence increasingly larger number of genomes with high coverage.
* _Algorithmic / methodological_: Newer algorithms, computational tricks, novel data structures, numerical approximations, better workflows, etc.
* _Hardware / software_: Better hardware-software features such as multithreading/parallelizations, running on clusters/GPUs, memory/space requirements, newer features/functions in the software, newer/more parameters available for the user, etc.


## Discussion content and structure
Your paper discussion should cover the following parts and be led by one member from each learning group mentioned beside the title. Use this **[shared google slide document](https://docs.google.com/presentation/d/1sBBmN0gX7gplc5ZsJNHrUORTyFxlBVECFOqcg7Rtc4o/edit?usp=sharing)** to prepare your presentation. You will be using these slides on Friday, Feb 11 for the discussion. 

Each group takes one MUMer paper (MUMmer v1 to v4) and should plan to present the key advances in that version compared to the previous on in terms of each of the four aspects: i) Biology/conceptual, ii) Technological/experimental, iii) Algorithmic/methodological, and iv) Hardware/software. See the notes above for more details.

### Part 1 | _Group 1_
1. What are the key advances in MUMer v1 compared to previous whole-genome aligners? Present the advances across all four aspects.

### Part 2 | _Group 2_
2. What are the key advances in MUMer v2 compared to MUMer v1? Present the advances across all four aspects.

### Part 3 | _Group 3_
3. What are the key advances in MUMer v3 compared to MUMer v3? Present the advances across all four aspects.

### Part 4 | _Group 4_
4. What are the key advances in MUMer v4 compared to MUMer v4? Present the advances across all four aspects.


## Notes on preparing the presentation
* Use other resources beyond the paper to illustrate the problem, including illustrations, etc. Provide citations for the source materials on the slide.
* Avoid directly using dense figures directly from papers/other-sources. Instead, split complex multi-part figures in the paper into several slides; Capture/zoom-into parts of figure & annotate with boxes/arrows.
* Avoid large blocks of text. Convert methods to flowcharts & annotate flowcharts.; You’re welcome to draw neatly on paper & photograph it.
* Be prepared to define phrases/terminology on your slide.; Google it, read-up; No problem if any idea/concept is still unclear even after reading. Just bring it up in class & we can discuss.

# Assignment 02
>Due before class Monday, Nov 15

## Notes  
1. Download and work with the [R notebook Assignment_02.Rmd](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/Assignments/Assignment_02.Rmd) OR the [Jupyter notebook Assignment_02.ipynb](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/Assignments/Assignment_02.ipynb).
2. Submit the R or Jupyter Notebook back to me via Slack with your comments/annotations on the code and the results, along with your interpretation of the results and answers the questions at the end of each part.
3. This assignment should not take more than 40–50 min max. If you run into trouble, please do not hesitate to ask me or others in the class on Slack.

The assignment contains **three** parts.

## Part 1: Calculating p-values using a permutation test
1. Your tasks for this part are to complete the exercise mentioned in class:
   - Add comments/annotations on the code and the results, along with your interpretation of the results.
   - Answers a couple of questions at the end.

## Part 2: Effect of effect_size, variance, and sample_size on p-values
1. Like we discussed in class, apart from the null hypothesis (which need not always be equivalent to random chance), the p-value of a statistical test depends on effect size, variance with each group, and sample size.
2. To explore how these factors influence the p-value, I have written the below to simulate data for two groups multiple times (just like the exercise we did in class), each time varying the `effect_size`, `std_deviation`, and `sample_size`, and calculating the p-value using a T-test.
3. Your tasks are the following:
   - Carefully examine and annotate the code by writing detailed comments at each step.
   - Examine the figure that is being produced and write a short paragraph about you observations on how these three quantities influence the p-value.

## Part 3: P-hacking
1. P-hacking is the practice of collecting or selecting data or statistical analyses until nonsignificant results become significant.
2. You tasks:
   - Carefully examine and annotate the code by writing detailed comments at each step.
   - Describe your thoughts on what this coding exercise has to do with p-hacking.

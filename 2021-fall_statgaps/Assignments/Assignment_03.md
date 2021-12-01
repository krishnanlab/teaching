# Assignment 03
>Due before class Wednesday, Nov 17

## Notes  
1. Download and work with the [R notebook Assignment_03.Rmd](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/Assignments/Assignment_03.Rmd) OR the [Jupyter notebook Assignment_03.ipynb](https://github.com/krishnanlab/teaching/blob/master/2021-fall_statgaps/Assignments/Assignment_03.ipynb).
2. In your R or Jupyter Notebook, add your comments/annotations on the code and the results, along with your interpretation of the results and answers the questions at the end of each part. Export your notebook as a PDF and submit it via the [google form](https://bit.ly/statgaps2021_submit).
3. This assignment should not take more than 40 min. If you run into trouble, please do not hesitate to ask me or others in the class on Slack.

The assignment contains **two** parts.

## Part 1 – Calculating power and generating a power curve for detecting unfair coins
This part deals with implementing an experiment to identify if a coin is biased or not, and additionally calculating the power of this experimental design for a specific set of parameters such as a given alpha, effect size, and sample size.
1. Flip the given coin `num_flips` times
2. Record the number of heads
3. Compare to the null distribution
4. Get a `p_value`
5. Reject or accept the null based on comparison to `alpha`

## Part 2 – Generating a multiple power curves for detecting unfair coins
Here you will be generating multiple power curves to establish the relationship between power, effect size, and sample size. You will notice that much of the code above will be reused to generate the curve like the one above but for various sample sizes.

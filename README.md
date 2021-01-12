# Udacity---A-B-Testing-Case-Study
**Walkthrough Udacity A/B Testing case study - Data Analysis Nanodegree**
### Analysis Background:
a data set provided for two landing pages - an old page and a new page - aiming two run A/B testing to check which one has better perfromance

### Metric used:
the conversion rate was the only metric used in order to evaluate the A/B testing.

### Intorduction
This is A/B test is to examine the potential effect of applying a new page design. The chosen metric was the conversion rate. The test has run over a period of time and the details of the transactions were recorded in a csv file> we shall consider three different approached towards reaching a conclusion. namely, a probability approach, A/B testing apporach and finally with a regression approach.

### Hypothesis Test:

$$H_0: p_{new} - p_{old} \leq 0  $$
$$H_1: p_{new} - p_{old} > 0 $$

where p_new represents the proportion of converted users under the new_page design
where p_old represents the proportion of converted users under the old_page design

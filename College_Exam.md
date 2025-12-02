# Ordered Study List - Final Detailed Version Done

1. **Types of data**

   * Qualitative vs quantitative
   * Measurement scales: nominal, ordinal, interval, ratio
   * Discrete vs continuous

2. **Population vs sample**

   * Sampling frame
   * Statistic vs parameter
   * Census vs sample

3. **Descriptive vs inferential statistics**

   * Variability
   * Frequency and cumulative frequency distributions
   * Role of sampling in inference

4. **Summary statistics**

   * Mean, median, mode
   * Variance, standard deviation

5. **Other central tendency measures**

   * Geometric mean
   * Harmonic mean
   * Trimmed mean

6. **Moving average** (time-series smoothing, trend analysis)

7. **Visualisations**

   * Stem-and-leaf plot (small datasets)
   * Histogram
   * Dotplot
   * Bar chart
   * Boxplot
   * QQ-plot
   * Scale-to-plot quick map: categorical → bar; numerical → histogram

8. **Information theory basics**

   * Shannon entropy and uncertainty

9. **Sampling design basics**

   * Scheme/plan
   * Sampling error vs bias
   * With vs without replacement

10. **Probability sampling methods**

* Simple Random Sampling (SRS)
* Stratified sampling (proportionate & disproportionate allocation)
* Systematic sampling
* Cluster sampling
* PPS (probability proportional to size) sampling
* Multistage sampling
* Multiphase sampling
* SRS operational steps: define population, construct frame, draw sample, contact units

11. **Non-probability sampling methods**

* Purposive/judgemental sampling
* Convenience sampling
* Quota sampling
* Area (judgement) sampling
* Snowball sampling

12. **Survey & data collection systems**

* Survey instruments
* Questionnaire design: steps, open vs closed questions, wording, sequencing, piloting

13. **Sampling distribution concepts**

14. **Law of Large Numbers (LLN)**

* Concept and sample-mean convergence
* Intuition: coin-flip example, more data → more accuracy

15. **Central Limit Theorem (CLT)**

* Conditions, role of sample size
* Normal approximation of sample mean
* Emphasis: regardless of population shape, sample means → normal for large n

16. **Study types and experimental design**

* Experimental vs observational
* Randomized controlled trials, crossover, replication, local control
* Cohort, case-control, cross-sectional
* Fisher’s principles: randomization, replication, local control

17. **Hypothesis testing basics**

* Null vs alternative (H0/H1)
* Test statistic, p-value, significance level (α)
* Type I and Type II errors, statistical power
* Outcome matrix: decisions vs reality (error placement)
* Workflow: state H0/H1, set α, compute statistic, get p-value, conclude
* Writing nulls with equality ( = , ≥ , ≤ ), common α = 0.05
* Plain rule: “If p is low, H0 must go”

18. **Test statistics**

* z and t statistics as standardized distances from null values
* Interpreting p-values: small vs large, correct guidance

19. **Courtroom analogy for hypothesis testing**

* H0 = presumption of innocence
* H1 = charge
* Evidence = sample data
* α = beyond reasonable doubt

20. **Practical data workflow**

* Data cleaning
* Handling missing values
* Computing summary stats
* Reproducible notebooks/code

21. **Applied analysis (IPO dataset assignment)**

* Select field (Listing Gain / Current Gains / Total)
* Produce: histograms, dotplots, QQ-plots, time-series with moving average, stem-and-leaf if useful
* Simulate repeated samples for n = 5, 30, 100 → show CLT via sample-mean histograms
* Plot sample mean vs sample size → demonstrate LLN
* Compute mean, median, mode, geometric mean, harmonic mean, trimmed mean, moving average
* Document seed, sample sizes, labeled graphs, and conclusions in a PDF report

22. **Random sampling vs random assignment**

* Roles, differences, and why both matter

23. **Sampling frame quality and coverage**

* Exhaustive, up-to-date lists
* Coverage bias examples (classic polling failures)

24. **Nonresponse/contact bias**

* Response rates, comparing respondents vs nonrespondents

25. **Sample size planning**

* Factors: variability, effect size, confidence level, margin of error, cost
* Diminishing returns with very large n

26. **Confidence intervals and margin of error**

* Interpretation in surveys and polls

27. **Sampling error taxonomy**

* Random vs systematic
* Impacts on generalization and inference

28. **Critical evaluation of polls**

* Self-selection bias in online/media polls
* Cautious interpretation guidelines

29. **Key term consolidation**

* Census, element, exhaustive list
* Random sampling error vs systematic sampling error
* Confidence interval

30. **Variables/features/measures terminology**

* Columns in data table as variables
* Measurement alignment

31. **Sampling as gateway to inference**

* Subset → inferential procedures → hypothesis testing

32. **Fisher’s principles revisited**

* Linking randomness in experiments to LLN and CLT

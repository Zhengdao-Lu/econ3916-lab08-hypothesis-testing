# econ3916-lab08-hypothesis-testing
# Hypothesis Testing — Is Job Training Worth It?

## Objective

I examined whether the LaLonde NSW job-training program increased participants’ 1978 earnings.

## Methodology

- I loaded data for 445 people: 185 trainees and 260 controls.
- I conducted a one-sample t-test and a two-sample Welch’s t-test.
- I wrote a `welch_t()` function and checked its results against SciPy for the full sample and five subgroups.
- I calculated Cohen’s d to measure the size of the earnings difference.
- I conducted a power analysis.
- I tested five overlapping demographic subgroups.
- I applied Bonferroni and Benjamini–Hochberg corrections.
- I simulated p-value distributions when the null hypothesis was true and when it was false.

## Key Findings

Trainees earned $1,794.34 more than controls in 1978. The difference was statistically significant, with Welch’s t = 2.6741 and p = 0.0079. Cohen’s d was 0.2727, indicating a small effect. Before correcting for multiple comparisons, two of the five subgroup effects were significant. After the Bonferroni correction, one subgroup effect remained significant.

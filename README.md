# KARMIN_sample_size
Details of sample size calculations based on data reported for the KARMIN study (https://doi.org/10.1016/j.eclinm.2023.101958).

# Assumptions

The ShinyCRT web application was used to determine the minimum sample size for the primary outcome based on following reported information:

* The study design presented in the paper: 3 treatment sequences, 6 wards assigned to each treatment sequence.
* Each ward was a cluster
* Primary outcome: reported incidence per 100 patients under the soap-based arm (reference): 1.65. Treated as a binary outcome (1.65%)
* The expected reduction in the primary outcome before the trial commenced: 30% reduction to 1.115 (1.115%)
* Intraclass correlation coefficient: 0.0001
* A two-sided statisical significance level = 0.025 to account for two planned comparisons (soap vs. detergent, soap vs. probiotic)
* A two-period decay correlation function with a cluster autocorrelation coefficient = 0.8. This assumption allows the correlation to chagne by measurement period
* For each planned comparison, a custom design matrix was used with 0 = reference arm, 1 = non-reference arm in the planned comparison, NA =  remaining non-reference arm not in the planned comparison

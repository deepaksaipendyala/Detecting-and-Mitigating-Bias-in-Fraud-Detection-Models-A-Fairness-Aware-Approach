# Background

In our project, we employ the Bank Account Fraud suite (BAF), the first publicly-available and
extensive collection of tabular datasets that implements added measures to ensure the privacy of
applicants. Although the data set contains an extensive amount of valuable data for machine learning
testing, the challenges of the model are class imbalance, the prevalence of bias, and maintaining
the privacy of its applicants. The issue of class imbalance arises from the fact that the observations
labeled as not fraudulent greatly outweigh those labeled as fraudulent, since each month, the rate
of applicants labeled as fraud fluctuates between 0.85% and 1.5% (Jesus et al. 4-5). Furthermore,
since class imbalance yields bias through group-size disparity, we plan to use fairness metrics to
mitigate the effect of such bias. Since the BAF suite contains sensitive background information of
its applicants, the dataset contains various measures to ensure their privacy. First, the dataset omits
attributes that can yield the identity of applicants, specifically age and income. To further preserve
the privacy of its applicants, the BAF suite is perturbed using Laplacian noise for privacy and using
CTGAN to create synthetic data. Filtering and transformations ensured the integrity of the data while
preserving the original behaviors.

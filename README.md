# Detecting and Mitigating Bias in Fraud Detection Models

## Overview
This project focuses on developing a **hybrid fraud detection model** to ensure fairness and accuracy in identifying fraudulent bank account applications. By addressing issues such as class imbalance and bias in datasets, the model achieves equitable outcomes across demographic groups while maintaining high predictive performance.

## Key Features
- **Bias Mitigation Techniques**:
  - **Pre-processing**: Reweighing and Synthetic Minority Oversampling (SMOTENC).
  - **In-processing**: Adversarial debiasing using the AIF360 library.
  - **Post-processing**: Threshold optimization to align predictions with fairness metrics.
- **Evaluation Metrics**:
  - **Fairness**: Demographic Parity Difference (DPD) and Equalized Odds Difference (EOD).
  - **Performance**: Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
- **Ensembled Bias Mitigation Architecture**:
  Combines pre-processing, in-processing, and post-processing methods to ensure comprehensive bias reduction.

## Methodologies
1. **Exploratory Data Analysis (EDA)**:
   - Analyzed six datasets from the Bank Account Fraud (BAF) suite.
   - Addressed class imbalance, identified correlations, and selected predictive features.
2. **Data Processing**:
   - Balanced datasets using SMOTENC and reweighing.
   - Addressed missing values using imputation techniques.
   - Standardized numerical features and encoded categorical variables.
3. **Model Training**:
   - Implemented nine machine learning models, including Logistic Regression, Random Forest, and Neural Networks.
   - Tuned hyperparameters using grid search and random search.
4. **Bias Mitigation**:
   - Applied fairness constraints and optimization at different stages of the pipeline.

## Results
The project demonstrated:
- Significant reduction in bias metrics (DPD and EOD) across models and datasets.
- High predictive performance with robust classification metrics.
- Improved fairness without compromising accuracy, showcasing the effectiveness of the ensembled bias mitigation architecture.

## Future Work
- Integration of **Large Language Models (LLMs)** and **Generative Adversarial Networks (GANs)** for advanced bias mitigation.
- Expansion to new sensitive attributes (e.g., age, geography, socioeconomic status).
- Continuous monitoring and retraining mechanisms to adapt to dynamic data environments.

## Resources
- **Dataset**: [Bank Account Fraud Dataset (Kaggle)](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022/data)
- **Code Repository**: [GitHub Link](https://github.ncsu.edu/dpendya/engr-ALDA-Fall2024-P22)

## Contributors
- **Deepak Sai Pendyala** (dpendya@ncsu.edu)
- **Uddharsh Vasili** (uvasili@ncsu.edu)
- **Akhilsai Chittipolu** (achitti@ncsu.edu)
- **Ryan Gallagher** (rtgalla2@ncsu.edu)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to clone, contribute, or provide feedback to enhance the model and its applications.

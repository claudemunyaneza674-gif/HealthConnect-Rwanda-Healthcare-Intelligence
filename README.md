# HealthConnect Rwanda: Healthcare Intelligence System

## Project Overview

This project was developed as part of the AnalystLab Africa Experience Lab — Week 6 assignment. It explores how machine learning and data analytics can support healthcare intelligence through predictive modeling, patient segmentation, billing anomaly detection, and model interpretation.

The project uses educational datasets associated with the fictional HealthConnect Rwanda healthcare scenario.

## Objectives

- Prepare and integrate healthcare-related datasets.
- Develop classification models for insurance claim status, patient satisfaction, and an exploratory high-risk screening proxy.
- Explore billing amount prediction using regression.
- Apply clustering to identify patterns among patients and healthcare facilities.
- Detect unusual billing records using anomaly detection.
- Examine model performance, feature importance, limitations, and responsible AI considerations.

## Methods and Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab
- Machine learning: classification, regression, clustering, and anomaly detection

## Repository Contents

- `HealthConnect_Week6.ipynb` — project notebook and analysis workflow.
- `HealthConnect_Executive_Summary.docx` — executive summary.
- `HealthConnect_Final_Presentation.pptx` — presentation of the project.
- `deployment_architecture.png` — proposed deployment architecture.
- `limitations_and_ethics.txt` — project limitations and ethical considerations.
- `week6_progress_review.txt` — progress review.

## Key Findings and Limitations

The project demonstrates an end-to-end educational healthcare analytics workflow. Initial experiments produced classification, regression, clustering, and anomaly-detection outputs.

However, the results require careful interpretation. Some models show limited predictive performance, the high-risk screening label is a rule-generated proxy rather than a confirmed clinical outcome, and unusual billing records are not evidence of fraud. The regression results also require further validation for potential target leakage.

Admission prediction and length-of-stay prediction were not established as validated predictive tasks in the current workflow. SHAP/LIME explanations were not completed.

## Responsible AI

This project is for educational purposes and is not a clinical decision-support system. Its outputs should not be used to diagnose patients, determine treatment, or make real-world healthcare decisions. Any future deployment would require appropriate data governance, privacy safeguards, clinical validation, bias assessment, and expert oversight.

## Future Improvements

- Validate target definitions and improve data quality.
- Evaluate models using suitable metrics and stronger validation methods.
- Investigate potential data leakage and class imbalance.
- Add SHAP or LIME explanations.
- Develop a prototype dashboard and evaluate it with appropriate stakeholders.

## Author

Developed as part of the AnalystLab Africa Experience Lab — Week 6 project.

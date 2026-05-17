Task 1: Choose a Business Domain

Selected domain: Healthcare

Healthcare is chosen because hospitals generate large amounts of patient records and diagnostic reports, and many routine decisions can be improved through AI systems. This creates opportunities to reduce delays, improve accuracy, and support doctors in diagnosis.

Task 2: Define the Business Problem
Problem Being Solved

Hospitals often face delays in detecting diseases from patient medical reports, especially when reports contain large amounts of unstructured text such as doctor notes, discharge summaries, and lab findings. The problem is to automatically classify patient reports to identify high-risk disease cases early.

Users / Stakeholders
Doctors
Hospital administrators
Patients
Healthcare data analysts
Current Manual Process

Currently, doctors manually review patient reports and diagnostic notes before making decisions. This process depends heavily on human effort and time.

Limitations of Current Process
Time-consuming
Prone to human error
Difficult to scale with increasing patient load
Delayed identification of critical cases
Task 3: Identify the AI Task Type

Selected AI task type: Text classification

Text classification is suitable because patient records and clinical notes are primarily text-based. The goal is to assign each report into categories such as normal, moderate-risk, or high-risk disease condition.

Task 4: Data Requirement Plan
Type of Data Needed
Electronic health records
Doctor notes
Lab test reports
Diagnosis history
Data Format
Structured data: age, blood pressure, lab values
Unstructured data: medical notes, diagnosis descriptions
Input Features
Patient age
Gender
Symptoms
Test results
Clinical notes
Previous disease history
Target Variable
Disease risk category (low, medium, high)
Data Collection Method

Data can be collected from hospital management systems and historical medical databases.

Data Quality Risks
Missing patient values
Inconsistent report formats
Incorrect labeling by staff
Imbalanced classes
Task 5: Model Recommendation

Recommended model: Transformer-based model (BERT)

BERT is appropriate because it performs well on text understanding tasks and can process complex medical language. It captures contextual meaning better than traditional machine learning models.

Reasons:

Handles long textual reports
Understands context in medical terminology
High accuracy in text classification
Can be fine-tuned on healthcare datasets
Task 6: Evaluation Plan
Technical Metrics
Accuracy
Precision
Recall
F1-score
Business Metrics
Reduction in diagnosis time
Increase in early detection rate
Reduced hospital operational cost
Improved patient outcomes
Possible Failure Cases
Misclassification of rare diseases
Incorrect prediction for incomplete reports
Low performance on noisy text
Human Review

Doctors should review AI predictions before final diagnosis decisions are made.

Task 7: Responsible AI Considerations
Bias in Data

If training data mostly represents certain age groups or demographics, predictions may be biased.

Incorrect Predictions

False positives or false negatives may affect patient treatment decisions.

Privacy Concerns

Patient data contains sensitive information and must be protected according to healthcare regulations.

Over-Reliance on AI

Doctors should not depend solely on AI. Human expertise must remain central.

Impact on Users

Wrong predictions may create anxiety for patients or incorrect treatment paths.

Human Oversight

Every high-risk case prediction should be validated by medical professionals.

Task 8: Final Solution Summary
Problem

Manual review of patient reports causes delays in identifying high-risk disease cases.

Proposed AI Solution

Use an NLP-based text classification system to analyze patient reports and automatically identify disease risk categories.

Required Data
Patient records
Doctor notes
Lab reports
Historical diagnosis labels
Model Recommendation

Transformer-based model: BERT

Expected Business Impact
Faster diagnosis
Better patient care
Reduced manual workload
Improved hospital efficiency

Risks and Mitigation Plan
Data bias may lead to unfair predictions → use diverse training data
Incorrect predictions may affect diagnosis → doctor review before final decision
Privacy concerns with patient records → anonymize sensitive data
Over-reliance on AI → keep human oversight in decision-making
# Thyroid-Cancer-Recurrence-Predictor
# Predicting Recurrence in Well-Differentiated Thyroid Cancer
## Introduction
Objective: To predict the recurrence of well-differentiated thyroid cancer using clinicopathologic features.

Data: Collected over 15 years, with each patient followed for at least 10 years.

## Dataset Overview
Features: 13 clinicopathologic features

Follow-Up Period: At least 10 years for each patient

## Key Predictive Factors
### Risk Factors for Recurrence
**1. Structural Incomplete Response**

Patients with structural incomplete response to treatment are at a significantly higher risk of recurrence.

**Recommendation**: Close monitoring and aggressive follow-up protocols.

**2. N Stage (N1b)**

Lymph node involvement (N1b) is a strong predictor of recurrence.

**Recommendation**: Intensive monitoring and possible additional therapeutic interventions.

**3. Intermediate Risk Category**

Patients classified as intermediate risk have a higher likelihood of recurrence.

**Recommendation**: Tailored follow-up and treatment plans.

**4. Presence of Distant Metastasis (M1)**

Distant metastasis is a critical factor in predicting recurrence.

**Recommendation**: Aggressive follow-up strategy.

### Protective Factors
**1. Excellent Response**

Patients with an excellent response to treatment have a significantly lower risk of recurrence.

**Recommendation:** Standard follow-up protocols.

**2. Low Risk Category**

Patients classified as low risk are less likely to experience recurrence.

**Recommendation**: Less intensive follow-up protocols.

**3. Uni-Focal Tumors**

Patients with uni-focal tumors have a lower likelihood of recurrence.

**Recommendation**: Standard monitoring protocols.

# Logistic Regression Model

A logistic regression model was developed to predict recurrence based on the identified risk and protective factors.

Model Deployment: The model was saved using pickle for future use.

# Conclusion

Clinical Implications: The identified factors can help clinicians in designing personalized follow-up and treatment plans for patients with well-differentiated thyroid cancer.

Future Work: Continuous evaluation and improvement of the model with new data.
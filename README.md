# Machine Learning-Based Medication Prescription Support System

This project presents the development and evaluation of a *Machine Learning-Based Medication Prescription Support System*, aimed at assisting healthcare professionals and patients by providing automated, data-driven prescription recommendations based on symptoms.

##  Project Description

Using structured healthcare datasets, various machine learning models (Decision Trees, SVM, Random Forest, Gradient Boosting, K-Nearest Neighbors, and Multinomial Naive Bayes) were trained to predict diseases based on symptoms. The system integrates model interpretability tools (SHAP and LIME) to ensure transparency and trust in predictions. It further provides users with recommended medications, precautions, diets, and workout plans based on the predicted disease.

##  Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Dataset Description](#dataset-description)
- [Performance](#performance)
- [Explainability](#explainability)
- [Future Work](#future-work)
- [License](#license)

##  Installation

1. Clone the repository:
   bash
   git clone https://github.com/vasaviboyina06/MSC-Final-project.git
   cd MSC-Final-project
   
2. Install the dependencies:
   bash
   pip install -r requirements.txt
   
   *(If requirements.txt is not present, generate it based on the libraries used.)*

3. Run the model or notebooks in your preferred environment (e.g., Jupyter Notebook, Google Colab).

##  Usage

- Input symptoms via user prompt.
- System predicts disease based on symptoms.
- Recommendations for medications, precautions, diets, and workouts are provided.

Example:

bash
Enter your symptoms....... itching, skin_rash, nodal_skin_eruptions


Outputs:
- Predicted Disease
- Short Description
- Suggested Medications
- Precautionary Measures
- Recommended Workouts
- Suggested Diet Plans

##  Models Used

- *Support Vector Machine (SVM)*
- *Random Forest Classifier*
- *Gradient Boosting Classifier*
- *K-Nearest Neighbors (KNN)*
- *Multinomial Naive Bayes*

##  Dataset Description

- *Symptoms Dataset*: Maps symptoms to diseases.
- *Symptom Severity Dataset*: Severity weight of each symptom.
- *Medication Dataset*: Disease to medication mapping.
- *Precautions Dataset*: Safety guidelines per disease.
- *Diet & Workout Dataset*: Lifestyle advice based on illness.

##  Performance

All models achieved *100% accuracy* during testing, reflecting:
- Highly structured, clean datasets.
- Well-separated symptom-disease relationships.

Metrics used:
- Accuracy
- Precision
- Recall
- F1-Score

##  Explainability

- *SHAP (SHapley Additive exPlanations)*
- *LIME (Local Interpretable Model-Agnostic Explanations)*

These techniques enhance user and clinical trust by providing interpretable model predictions.

##  Future Work

- Expand datasets with real-world medical data.
- Integrate external validation with clinical data.
- Improve real-time deployment (e.g., API integration).
- Conduct clinical validation studies.
- Build mobile/web interfaces for wider accessibility.

##  License
This project is developed as part of the *MSc Data Science Project* at *University of Hertfordshire*.


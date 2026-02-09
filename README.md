# Crime Case Classification Using Machine Learning

This project applies supervised machine learning and natural language processing to classify North Carolina criminal court cases into seven crime categories based on textual content.

Legal documents are long and unstructured, making manual classification time-consuming. This project demonstrates how NLP and ML techniques can assist with organizing legal case data.

---

## Dataset

The dataset contains 602 criminal cases from the North Carolina Court of Appeals, sourced via the Harvard Caselaw Access Project and CourtListener.

Due to size constraints, raw datasets are not included in this repository.

---

## Approach

- Text preprocessing using tokenization, stopword removal, and lemmatization  
- Feature extraction using TF-IDF and topic modeling (LSA / LDA)  
- Supervised classification using:
  - Naive Bayes  
  - Random Forest  
  - Support Vector Machines  
  - Gradient Boosting  
  - Neural Networks  
- Addressed class imbalance using SMOTE  
- Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices  

---

## Results

- Best performing model: Gradient Boosting  
- Final accuracy after SMOTE: 61.86%  
- Strongest performance on Drug Offenses and Sex Offenses categories  

---

## Technologies

- Python
- Pandas
- NumPy
- scikit-learn
- NLTK
- imbalanced-learn
- Matplotlib / Seaborn

---

## Repository Contents

- Jupyter notebooks containing preprocessing, modeling, and evaluation
- Project report (PDF)
- Supporting scripts

---

## Notes

This project represents an applied machine learning workflow focused on text classification.

For detailed methodology and analysis, see the included project report PDF.

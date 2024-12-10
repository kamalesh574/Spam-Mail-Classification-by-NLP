# Spam-Mail-Classification-by-NLP-and-ML

# Spam Mail Classification by NLP and ML

## Project Overview
This project demonstrates the use of Natural Language Processing (NLP) techniques and Machine Learning (ML) models to classify emails as spam or ham (non-spam). By leveraging text preprocessing, feature extraction, and ML algorithms, the project aims to build a robust system that efficiently detects spam emails.

---

## Features
- Text preprocessing, including tokenization, stop-word removal, and stemming/lemmatization.
- Feature extraction using techniques like Bag of Words (BoW), Term Frequency-Inverse Document Frequency (TF-IDF), etc.
- Multiple machine learning models for classification, including:
  - Naïve Bayes
  - Support Vector Machines (SVM)
  - Random Forest
  - Logistic Regression
- Model evaluation metrics like accuracy, precision, recall, F1-score, and confusion matrix.

---

## Installation
### Prerequisites
- Python 3.8+
- Virtual environment (optional but recommended)

### Required Libraries
Install the required libraries using the following command:
```bash
pip install -r requirements.txt
```
Sample `requirements.txt`:
```
altair==5.4.1
attrs==24.2.0
blinker==1.8.2
cachetools==5.5.0
certifi==2024.8.30
charset-normalizer==3.3.2
click==8.1.7
colorama==0.4.6
gitdb==4.0.11
GitPython==3.1.43
idna==3.8
Jinja2==3.1.4
joblib==1.4.2
jsonschema==4.23.0
jsonschema-specifications==2023.12.1
markdown-it-py==3.0.0
MarkupSafe==2.1.5
mdurl==0.1.2
narwhals==1.6.0
nltk==3.9.1
numpy==2.1.0
packaging==24.1
pandas==2.2.2
pickle-mixin==1.0.2
pillow==10.4.0
protobuf==5.28.0
pyarrow==17.0.0
pydeck==0.9.1
Pygments==2.18.0
python-dateutil==2.9.0.post0
pytz==2024.1
referencing==0.35.1
regex==2024.7.24
requests==2.32.3
rich==13.8.0
rpds-py==0.20.0
scikit-learn==1.5.1
scipy==1.14.1
six==1.16.0
smmap==5.0.1
streamlit==1.38.0
tenacity==8.5.0
threadpoolctl==3.5.0
toml==0.10.2
tornado==6.4.1
tqdm==4.66.5
typing_extensions==4.12.2
tzdata==2024.1
urllib3==2.2.2
watchdog==4.0.2

---

## Dataset
- **Source**: The dataset used is a labeled email dataset containing spam and ham labels (e.g., the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)).
- Ensure the dataset is in `.csv` format with two columns: `label` and `text`.
- Example:
  | label  | text                          |
  |--------|-------------------------------|
  | ham    | "Hello, how are you?"         |
  | spam   | "Win a free iPhone now!"      |






---

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request.

---


---

## Acknowledgments
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- [NLTK Documentation](https://www.nltk.org/)
- [Scikit-Learn Documentation](https://scikit-learn.org/)



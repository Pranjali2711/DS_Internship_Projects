# Fake News Detection 

## Objective
To classify news articles as **REAL** or **FAKE** using Natural Language Processing techniques.

## Dataset
- Fake.csv
- True.csv

## Techniques Used
- Text Cleaning
- TF-IDF Vectorization
- Support Vector Machine (LinearSVC)

## Steps
1. Load and merge datasets
2. Clean text data
3. Convert text to TF-IDF vectors
4. Train SVM model
5. Evaluate using accuracy and classification report
6. Predict custom news interactively

## Output
- REAL NEWS (Green)
- FAKE NEWS (Red)

## How to Run
```bash
pip install -r requirements.txt


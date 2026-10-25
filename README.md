# Machine Learning-Based Classification of DNA Sequences for Bioinformatics Applications

## Project Overview
This project uses machine learning techniques to classify DNA sequences for bioinformatics applications. The dataset contains DNA sequences from human, chimpanzee, and dog sources.

## Dataset
The project uses three files:
- `human.txt`
- `chimpanzee.txt`
- `dog.txt`

Each dataset contains DNA sequences and their corresponding class labels.

## Machine Learning Models
The following models are used:
- Multinomial Naive Bayes
- Logistic Regression
- Random Forest Classifier

## Methodology
1. Load and combine the datasets.
2. Check missing values and duplicate records.
3. Remove duplicate rows.
4. Split the data into training and testing sets.
5. Extract character 4-gram features using CountVectorizer.
6. Train the machine learning models.
7. Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrices.

## Tools and Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run
Open the uploaded Jupyter Notebook in Google Colab and run the cells in order.

## Author
Shamraj Deb Nath  
Department of Computer Science & Engineering  
Premier University, Chattogram

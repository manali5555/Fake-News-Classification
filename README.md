# Fake-News-Classification

## Project Overview
This project aims to address the challenge of distinguishing between real and fake news articles. Utilizing the WELFake dataset—which comprises 72,134 articles, with a balanced mix of real and fake news—we apply various machine learning techniques to develop a classifier capable of identifying deceptive information.

## Dataset
The WELFake dataset is used, featuring:
- **72,134 news articles** (35,028 real and 37,106 fake)
- Columns: Serial Number, Title, Text, Label (0 for fake, 1 for real)

## Methodology
1. **Data Preprocessing**: Cleaning text data and handling missing values.
2. **Feature Extraction**: Using TF-IDF to convert text to numerical format.
3. **Model Evaluation**: Testing models like Naive Bayes, Logistic Regression, and SVM.
4. **Optimization**: Fine-tuning the best model for improved accuracy.

## Requirements
- Python 3.x
- Libraries: numpy, pandas, sklearn, matplotlibNLTK, WordClou

## How to Run
1. Clone this repository.
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the script

## Results
The Logistic Regression model demonstrated superior performance, with a testing accuracy of 95.55%, indicating strong potential for real-world application in identifying fake news.

## Contributing
Contributions to this project are welcome. Please fork the repo and submit a pull request with your proposed changes.

## Acknowledgments
- Kaggle
- McIntire
- Reuters
- BuzzFeed Political


# Spam Email Classification using NLP

## Overview
This project applies Natural Language Processing (NLP) techniques to classify emails as spam or non-spam (ham). The Python-based solution utilizes libraries such as NLTK, pandas, scikit-learn, and matplotlib for preprocessing, analysis, and classification.

## Dataset
The dataset used in this project contains email messages with their respective classification labels (spam or ham). 

## Preprocessing Steps
1. Tokenization of the email messages.
2. Removal of punctuation and stop words.
3. Stemming of words to their root form.
4. Vectorization of the preprocessed text into a bag-of-words representation.

## Visualization
- Pie chart to show the distribution of spam vs non-spam messages.
- Bar chart of the top 20 most frequent words.
- Word cloud visualization for the bag-of-words.

## Classification Model
A logistic regression model is used to classify emails after converting the text data into a TF-IDF representation and augmenting it with a binary feature for non-English content detection.

## Files in the Repository
- `spam_email_classification.py`: The main Python script with all the preprocessing, modeling, and evaluation steps.
- `requirements.txt`: Lists all the dependencies to run the script.

## How to Run
1. Install the required dependencies:
   \`\`\`sh
   pip install -r requirements.txt
   \`\`\`
2. Run the Python script:
   \`\`\`sh
   python spam_email_classification.py
   \`\`\`

## Results
The model achieved an accuracy of approximately 95.78% on the test set. Further details can be found within the classification report in the script's output.

## Future Work
- Investigating more complex models to improve recall for spam emails.
- Tuning the classification threshold.
- Employing ensemble methods for better predictive performance.

## Contributions
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

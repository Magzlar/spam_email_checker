<b> Spam Detection System </b>
This project develops a machine learning model to classify text messages as spam non-spam by using NLP from the nltk library and machine learning, using the RandomForestClassifier algorithm from scikit-learn, the system preprocesses text data, extracts features, and trains a classifier for accurate spam detection.

Features
Data Preprocessing: Cleansing of text data by removing punctuation, tokenization, removal of stop words, and lemmatization
Feature Engineering: Incorporation of text-based features such as message length, percentage of punctuation, and spam word count alongside TF-IDF vectorization for model training
Model Training and Evaluation: Training a RandomForestClassifier with cross-validation and grid search to optimize model parameters for better evaluation metrics
Data Transformation: Application of Box-Cox transformation to improve the normality of feature distributions

Dependencies
Python 3.x
pandas
NumPy
scikit-learn
NLTK
Matplotlib
emoji
Setup
Ensure Python 3.7 is installed

Run the script with Python to train the model and evaluate its performance:

bash
Copy code
python spam_detection.py
Dataset
The model expects a tab-separated file (SMSSpamCollection.tsv) with two columns: label (spam or ham) and text (the message content). Ensure the dataset is prepared in this format.

Customization
You can customize the script to suit different datasets or requirements by modifying the feature extraction functions or the model parameters.

Contribution
Contributions are welcome! Please feel free to submit pull requests or open issues to improve the accuracy, efficiency, or functionality of the system.

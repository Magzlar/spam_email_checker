### <b> Spam Detection System: </b>
This project uses a machine learning model to classify text messages as spam non-spam by using NLP from the nltk library and machine learning, using the RandomForestClassifier algorithm from scikit-learn, the system preprocesses text data, extracts features, and trains a classifier for accurate spam detection.

### <b> Features: </b>
**Data Preprocessing**: Cleansing of text data by removing punctuation, tokenization, removal of stop words, and lemmatization
**Feature Engineering**: Incorporation of text-based features such as message length, percentage of punctuation, and spam word count alongside TF-IDF vectorization for model training
**Data Transformation:** Application of Box-Cox transformation to improve the normality of feature 
**Model Training and Evaluation:** Training a RandomForestClassifier with cross-validation and grid search to optimize model parameters for better evaluation metrics

**Dependencies**:
- Python 3.7
- pandas
- NumPy
- scikit-learn
- NLTK
- Matplotlib
- emoji
- spamwords (already present in folder) 

**Run the script with Python to train the model and evaluate its performance:**
The model expects a tab-separated file (SMSSpamCollection.tsv) with two columns: label (spam or ham) and ttext message i.e. the message content. Make sure the dataset is prepared in this format.

**Customization**
- You can customize the script to suit different datasets or requirements by modifying the feature extraction functions or the model parameters.
- I will also continue to update when new ML alorithms provide better results

any questions please email ryanmaguire1@hotmail.co.uk

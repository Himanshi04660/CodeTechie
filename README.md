# CodeTechie
Task 1: This project is a complete implementation of a **Spam Detection System** using **Natural Language Processing (NLP)** and **Machine Learning**, integrated into a **Tkinter-based Graphical User Interface (GUI)**.

### 1. **Dataset Loading**
- The dataset `spam_ham_dataset.csv` is loaded using `pandas`, which contains labeled SMS messages as `spam` or `ham`.

### 2. **Text Preprocessing**
- Lowercasing the text.
- Removing punctuation.
- Removing stopwords (using NLTK).
- Applying stemming using `PorterStemmer`.

### 3. **Label Encoding**
- The labels `ham` and `spam` are converted into numerical form (`0` and `1`) using `LabelEncoder`.

### 4. **Feature Extraction**
- Text data is transformed into numerical features using `TfidfVectorizer`.

### 5. **Model Training**
- A **Logistic Regression** classifier is trained using `scikit-learn` on 80% of the data.

### 6. **Model Evaluation**
- Accuracy and a classification report (precision, recall, F1-score) are printed to evaluate performance on the test set.

### 7. **GUI with Tkinter**
- A simple and intuitive GUI is built using the `tkinter` module.
- Users can input any text message and click on the "Detect" button.
- The message is analyzed and classified as either **Spam** or **Ham**, with the result shown in a popup window.

## Working
1. User enters a message in the text area.
2. The message is cleaned and preprocessed.
3. It is transformed into TF-IDF vector form.
4. The trained model predicts whether it's spam or ham.
5. The result is shown in a message box.

## Libraries Used:
- `pandas`
- `nltk`
- `sklearn`
- `tkinter`




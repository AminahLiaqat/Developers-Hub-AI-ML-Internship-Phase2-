# Developers-Hub-AI-ML-Internship-Phase2-

# News Topic Classifier Using BERT

## Task 01: Auto Tagging Support Tickets Using LLM
Objective:
The objective of this project is to build a News Topic Classifier using the *BERT (Bidirectional Encoder Representations from Transformers)* model. The model is fine-tuned on the AG News dataset to automatically classify news articles into one of four categories: *World, Sports, Business,* and *Science/Technology. The trained model is evaluated using **Accuracy* and *F1-score* and deployed with *Gradio* for real-time predictions.

---

## Dataset Used

*Dataset:* AG News Classification Dataset

The dataset contains *120,000 training samples* and *7,600 testing samples*.

### Features

* *Title:* News headline
* *Description:* Short description of the news article
* *Class Index:* News category label

During preprocessing:

* The *Title* and *Description* columns were combined into a single *text* column.
* The *Class Index* column was renamed to *label*.
* Labels were converted from *1–4* to *0–3* for compatibility with BERT.

### News Categories

| Label | Category           |
| ----: | ------------------ |
|     0 | World              |
|     1 | Sports             |
|     2 | Business           |
|     3 | Science/Technology |

---

## Model Applied

* *Pre-trained Model:* bert-base-uncased
* *Framework:* Hugging Face Transformers
* *Tokenizer:* BERT Tokenizer
* *Fine-Tuning:* Hugging Face Trainer API
* *Deployment:* Gradio

---

## Project Workflow

1. Download and prepare the AG News dataset.
2. Combine the Title and Description into a single text field.
3. Tokenize the text using the BERT tokenizer.
4. Fine-tune the pre-trained BERT model.
5. Evaluate the model using Accuracy and F1-score.
6. Save the trained model.
7. Deploy the model using Gradio for live news classification.

---

Evaluation Metrics:
The model performance was evaluated using:

* *Accuracy*
* *Weighted F1-score*

These metrics measure the classification performance on the test dataset.

Key Results and Findings:
* Successfully fine-tuned the *bert-base-uncased* model for news topic classification.
* Achieved strong classification performance using transfer learning.
* Correctly classified news articles into four categories:

  * World
  * Sports
  * Business
  * Science/Technology
Demonstrated the effectiveness of transformer-based models for NLP text classification.
Built a lightweight Gradio interface that enables users to classify news headlines in real time.

---

Technologies Used:
* Python
* Google Colab
* Pandas
* Hugging Face Transformers
* Hugging Face Datasets
* Evaluate
* PyTorch
* Gradio

---

Skills Gained:
* Natural Language Processing (NLP)
* Transformer Models (BERT)
* Transfer Learning and Fine-Tuning
* Text Tokenization and Preprocessing
* Model Evaluation (Accuracy and F1-score)
* Lightweight Model Deployment using Gradio



Task 2: End-to-End ML Pipeline with Scikit-learn Pipeline API

Objective:
The objective of this project is to build an end-to-end machine learning pipeline to predict customer churn using the IBM Telco Customer Churn dataset. The project demonstrates how to preprocess data, train classification models, optimize model performance using hyperparameter tuning, and create a reusable pipeline for predicting whether a customer is likely to churn.

Methodology / Approach:
- Loaded and explored the IBM Telco Customer Churn dataset.
- Performed data preprocessing by handling missing values and converting the target variable into numerical format.
- Identified numerical and categorical features.
- Built preprocessing pipelines using Scikit-learn's Pipeline and ColumnTransformer.
- Applied StandardScaler to numerical features and OneHotEncoder to categorical features.
- Trained two classification models: Logistic Regression and Random Forest.
- Evaluated both models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
- Performed hyperparameter tuning using GridSearchCV to improve model performance.
- Compared both models and saved the best-performing pipeline using Joblib.
- Used the saved pipeline to make predictions on new customer data.
  
Key Results / Observations:
- Successfully developed a complete end-to-end machine learning pipeline for customer churn prediction.
- Automated data preprocessing using Scikit-learn Pipeline and ColumnTransformer.
- Trained and compared Logistic Regression and Random Forest classifiers.
- Improved model performance through hyperparameter tuning using GridSearchCV.
- Exported the best-performing model as a reusable pipeline using Joblib.
- Demonstrated how the saved pipeline can be used to predict churn for new customer records, making the workflow suitable for real-world deployment.



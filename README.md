
# Secured Password Management
This project aims to build a machine learning model to predict the strength of a password as either Weak, Medium, or Strong using Logistic Regression. 


## Dataset
The dataset for this project is available on Kaggle and can be accessed [here](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset).
## Preprocessing
1. Dropped unnecessary columns.
2. Shuffled the passwords to randomize the dataset.
3. Tokenized passwords using a custom tokenizer function.
4. Converted passwords into numerical form using TF-IDF vectorization.
## Model
- Logistic Regression was used for the prediction.
- The model was trained on a split dataset (80% train, 20% test).
- Achieved an accuracy of 81.24% on the test dataset.
## Conclusion
This project successfully predicts password strength with an accuracy of 81.24% using Logistic Regression. It demonstrates the process of tokenizing passwords and converting them into numerical features using TF-IDF.
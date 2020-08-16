# Tweet-classification

This project experiments different models perfomance in predicting whether a given tweet is about a real disaster or not. 

The data used for this tutorial can be downloaded from Kaggle by following this [link](https://www.kaggle.com/c/nlp-getting-started/data).
The dataset contains text, keywords (may be blank), location (may be blank), a unique identifier for each tweet and the corresponding label.

Models tried out were logistic regression, gaussian classifier and a Recurrent Neural Network built using Keras.
Hyperparameters were tuned using GridSearchCV model selection and GradientBoostingClassifier to improve performance.

---

### To run the model
- Clone the repo

```git clone https://github.com/AniekanInyang/tweet-classification ```


- Install packages

```pip install -r requirements.txt ```


- Load the model

```from keras.models import load_model
model = load_model(os.path.join(cache_dir, "rnn_model.h5"))
```

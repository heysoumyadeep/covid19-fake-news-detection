# Fake News Detection from COVID-19 Dataset using Machine Learning Approach 

---

## Project Description

Along with the COVID-19 pandemic we are alsofighting an ’infodemic’. Fake news and rumors are rampant on social media. Believing in rumors can cause significant harm. This is further exacerbated at the time of a pandemic.

To tackle this, we curate and release a manually annotated dataset of multiple social media posts and articles of real and fake news on COVID-19. We perform a binary
classification task (real vs fake) and benchmark the annotated dataset with six machine learning baselines - Decision Tree, Logistic Regression, Gradient Descent Boosted Trees, and Support Vector Machine (SVM). We have also implemented LSTM and BERT models. 

For example, the following two posts belong to fake and real categories, respectively.
![image](https://github.com/heysoumyadeep/covid19-fake-news-detection/blob/master/imgs/fakevsreal.png)

One which gives the highest F1-Score is selected as the best model.

**Dataset Used**: https://github.com/diptamath/covid_fake_news/tree/main/data

---

## Results

* We find the highest F1 score for the SVM model, i.e. **93.45%**. Hence we conclude it can best detect fake news, for the used dataset.
* The descending order of F1 scores for all the models are: **SVM > LR > BERT > LSTM > GDBT > DT**

----

## References for the Project
The following GitHub repositories were used as references for our project: 
* https://github.com/parthpatwa/covid19-fake-news-detection
* https://github.com/krishnaik06/Fake-New-LSTM
* https://github.com/codebasics/deep-learning-keras-tf-tutorial/tree/master/47_BERT_text_classification

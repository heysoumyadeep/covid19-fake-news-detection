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

[1]  Darcy Warkentin, Michael Woodworth, Jeffrey T. Hancock, and Nicole Cormier. 2010. [Warrants and deception in computer-mediated communication](https://doi.org/10.1145/1718918.1718922). In Proceedings of the 2010 ACM Conference on Computer Supported Cooperative Work, CSCW ’10, page 9–12, New York, NY, USA. Association for Computing Machinery.

[2]  Arkaitz Zubiaga, Maria Liakata, Rob Procter, Geral- dine Wong Sak Hoi, and Peter Tolmie. 2016. [Analysing how people orient to and spread rumours in social media by looking at conversational threads](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0150989). PLOS ONE, 11(3):e0150989.

[3]  J.Cement. 2020. [Number of social media users 2025](https://www.statista.com/statistics/278414/number-of-worldwide-social-network-users/). Statista. Accessed: 2020-10-30.


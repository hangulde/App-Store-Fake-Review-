<h1><center>App Store Fake Review Detection</center></h1>



<p align="justify">Online reviews are an important and inevitable aspect of e-commerce. App stores are one of the common use of online reviews. The reviews include the users' feedback and experience related to the application. Besides, research shows that positive reviews promote the download and sales of applications. Unfortunately, some application developers mislead users by posting fake and high-rating reviews. They can show their applications better or rival companies' applications worse than they are with fake reviews. As a result, they misguide users into making wrong decisions and cause economic damage to other application owners, so detecting fake reviews is highly necessary.</p>

<p align="justify"> In this project, I aim to develop a model to filter fake application reviews. </p>

**Data:** The App Store reviews dataset is created by [Martens and Maalej (2019)](https://link.springer.com/article/10.1007/s10664-019-09706-9).

**Pre-Processing** Glove Word Embedding and SENTENCE_BERT were used for vectorization of review text.

**Models:** Random Forest, Naive Bayes, Multinomial Naive Bayes, Logistic Regression, Gradient Boosting, Ada Boost Classifier, XGBoost Classifier, Decision Tree 

**Output:** XGBoost classifier identifies fake reviews with an AUC/ROC value of 98%. 

<h2><center>File structure</center></h2>

Notebooks: All steps of the Data Science Method was conducted in seperate notebooks.

* Data wrangling
* Exploratory data analysis
* Pre-Processing
* Modelling

Media: Includes media which are used in report.

Report: Pdf of project report.

Presentation: pdf and pptx format of presentation




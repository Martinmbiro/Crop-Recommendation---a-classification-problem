# Crop Recommendation - a classification problem

<p align="center">
  <img src='pics/work.png'  width='530'/>
</p>

Hello again 👋
+ **Crop recommendation** is an agriculture-specific task, but this repository is
meant to show that agriculture could leverage the power of Artificial Intelligence (AI) to make **data-informed** crop recommendations
+ Also, by collaborating and being guided by domain experts, Machine Learning (ML) engineers can craft innovative solutions to challenges in agriculture. That said, the classification ML model built for this exercise was trained to classify 22 crop varieties based on 7 features affecting crop growth (nitrogen, phosphorus, potassium, temperature, humidity, soil ph & rainfall)
+ If the model were deployed, a farmer would pass the 7 features describing their prevailing farming conditions. The model would then recommend an ideal crop that would thrive in those conditions. Ultimately, this would maximize crop output and profits
+ Crop recommendation maps to a well-established concept in ML: **classification**. I illustrate implementing this concept in the notebooks _(labeled 01...03)_ by creating, training, and evaluating a _multiclass_ **classification** model. Comments, working code, and links to the latest official documentation are included every step of the way
+ As always, feel free to build upon these concepts


## Milestones 🏁
**Concepts covered in this exercise include:**  
1. [x] Data wrangling, analysis and visualization
2. [x] Training and evaluating a classification model ([`CatBoostClassifier`](https://catboost.ai/en/docs/concepts/python-reference_catboostclassifier))

## Tools ⚒️
1. [`Google Colab`](https://colab.google/) - A hosted _Jupyter Notebook_ service by Google.
2. [`pandas`](https://pandas.pydata.org/docs/index.html) - An open-source data analysis and manipulation tool built on Python
3. [`scikit-learn`](https://scikit-learn.org/stable/#) - A free open-source library that offers Machine Learning tools for the Python programming language
4. [`matplotlib`](https://matplotlib.org/) - A comprehensive library for making static, animated, and interactive visualizations in Python
5. [`numpy`](https://numpy.org/) - The fundamental package for scientific computing with Python
6. [`seaborn`](https://seaborn.pydata.org/) -  A Python data visualization library based on [`matplotlib`](https://matplotlib.org/), that provides a high-level interface for drawing attractive and informative statistical graphics
7. [`CatBoost`](https://catboost.ai/en/docs/) - An open-source Machine Learning algorithm that uses _gradient boosting_ on _decision trees_

## Results 📈
> So, how did the model classify unseen data into respective crop classes? On a scale of `0.0` to `1.0`,
+ Weighted & macro [`f1_score`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html#sklearn.metrics.f1_score) : `1.00`
+ Weighted & macro [`recall_score`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.recall_score.html#sklearn.metrics.recall_score) : `1.00`
+ Weighted & macro [`precision_score`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html#sklearn.metrics.precision_score) : `1.00`
+ Overall [`roc_auc_score`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html) : `0.99`
+ Overall [`accuracy_score`](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html#sklearn.metrics.accuracy_score) : `1.00`

> The saved model can be found in the `model` folder of the current repository. The dataset used for this exercise is included in the `dataset` folder.

## Reference 📚
+ Thanks to the insight gained from [`Microsoft Learn`](https://learn.microsoft.com/api/achievements/share/en-us/MartinMuriithi-6560/NZ987NAF?sharingId=C156514E494249EC), [`datacamp`](https://www.datacamp.com), and [`medium`](https://medium.com)
+ Not forgetting these gorgeous gourgeous [`emojis`](https://gist.github.com/FlyteWizard/468c0a0a6c854ed5780a32deb73d457f) 😻

> _Opensource dataset by [`Kaggle`](https://www.kaggle.com/datasets)_ ♥  
> _Illustration by [`Storyset`](https://storyset.com)_ ♥


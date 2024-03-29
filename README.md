# Project: Can you recognize the emotion from an image of a face? 
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/project3_desc.md)

Term: Fall 2019

+ Team 7
+ Team members
	+ Cao, Rui rc3208@columbia.edu

	+ Chen, Luyue lc3363@columbia.edu

	+ Dai, Tong td2602@columbia.edu

	+ Weiss, Daniel dmw2180@columbia.edu

+ Project summary: In this project, we created a classification engine for facial emotion recognition. Our Client is using a classification engine using boosted decision stumps on fudicial features. Our task is to propose a feasible improvement in client’s current practice to distinguish facial emotions. We were given a training set of 2500 images with 78 fudicial points to train a new model. Our proposed model is using Neural Network based on verizon and horizon distance between two fudicial points, which produced 2(78*77)/2 features in total. The model leads to an accuracy of 60% , with a running time of 600 seconds. This is a huge improvement from the Client's original model, which had an accuracy of ~40 % with a running time 2200 seconds. 

<img src="figs/results.png" alt="evaluation results" width="500"/>
	
**Contribution statement**: 
 	Rui implemented feature selection, built baseline model (GBM) and Neural Network Model. Created feature.ipynb, GBM_base.ipynb, Neural Network Model.ipynb, and test.ipynb. Updated the Summary section in the Readme file of the project; Luyue built Xgboost, Support Vector Machine model and Linear Discriminant Analysis model and implement SVM & XGBoost & LDA.ipynb and main file, involved in Github management and help to prepare the presentation, summarize model evaluation table. Tong contributed to data EDA, trained SVM model; Daniel is the presenter of this project for the group.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

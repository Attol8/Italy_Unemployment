# Italy Unemployment

#### -- Project Status: [Active]

## Project Intro/Objective
A full-stack data science project that looks to investigate unemployment in Italy. The project is a demonstration of the capabilities of Machine Learning models and investigates how Data Science can be leveraged to study Social Data.


### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* Flask
* PostGres, MySql
* Pandas, jupyter
* HTML

## Project Description
The main data source for this project is ISTAT, I have collected and scraped data from [their public database](http://dati.istat.it/), in particualr from the workforce survey conducted in Italy every quarter. I have built models to predict for unemployment at the individual level and deployed a web-application to explore the results (under construction).

Models predictions are analysed with SHAP (SHapley Additive explanations) values, a unified approach to explain the output of machine learning models.

## Getting Started

1. Clone this repo 
2. Place the `Colab Notebooks` inside your Google Drive main page
2. Raw Data is being kept [here](https://github.com/Attol8/Italy_unemployment/tree/master/Colab%20Notebooks/data) within this repo.  
3. All the notebooks are kept [here](https://github.com/Attol8/Italy_unemployment/tree/master/Colab%20Notebooks/notebooks). If you want to run a Notebook, just open it from Google Drive and start running cells
4. If you want to reproduce training for the model that predicts unemployment at the individual model, run `individual_model.ipynb` in the `notebooks` folder of the repo.

## Model(s) Results 

	  
Model|	     accuracy|	precision|	recall|	f1-score|	
--- | --- | --- | --- | --- |			
Random Forest |	0.796139|	0.799797|	0.796139|	0.797398|
XGBoost	0.771542	|0.782238	|0.771542	|0.774723|
KNN	0.719323|	0.724730	|0.719323	|0.721355|
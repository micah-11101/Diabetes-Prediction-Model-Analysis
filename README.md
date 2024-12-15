# Diabetes Prediction Project

This project seeks to analyze various demographic indicators and lifestyle behaviors as they relate to the incidence of diabetes in the United States. Diabetes research and data analysis is crucial as it addresses a global health crisis affecting millions of people; our project will focus on if we are able to better predict which outcomes may indicate if one has diabetes. 

Diabetes is a chronic condition that can lead to serious complications such as heart disease, kidney failure, blindness, and poor quality of life. Being able to predict who has or will have diabetes to an accurate degree based on lifestyle factors could assist with better treatment options, earlier detection and even prevention. 

Research in this field also supports the development of new therapies, technologies, and public health strategies that can significantly improve quality of life and reduce the burden of diabetes on individuals and society.

The dataset used for this project was found on Kaggle, where it existed as a cleaned and                                                                                                                                                                         conducted annually in the United States by the CDC. The original survey has responses from over 400,000 participants. The cleaned version we used has responses from over 250,000 people and is trimmed to only include selected demographic, lifestyle, and diabetes information. These results are from the year 2015.

As the dataset was already quite clean, most of our data cleaning involved ensuring the absence of null values, as well as reorganizing the data into usable data frames using groupby and related mathematical functions to calculate the counts and proportions of participants in each demographic or lifestyle group with a given outcome.

## The Data We Used
                                                                                                                                                                                                     
Our original data was obtained from a [kaggle]- Cleaned dataset: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset dataset created by user [Prosper Chuksl](https://www.kaggle.com/prosperchuks) – we used only the .csv file entitled ‘diabetes_data.csv’. The data was originally sourced from the [CDC's]- Original dataset: https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system 2015 Behavioral Risk Factor Surveillance System survey that collects data annually. **Note:** This dataset was synthetically cleaned and standardized so as to be more useful in a machine learning setting.
                                                                                                                                                                                                                                                                                                                      
# Diabetes Prediction Model Analysis

We created a multitude of models in an attempt to accurately predict if an individual will be diagnosed with diabetes based on limited information that is indicative of their current overall health.

### Python Dependencies

* Pandas
* sklearn
* sqlalchemy
* sqlite3
* matplotlib.pyplot
* seaborn
* tensorflow

!pip install

* xgboost
* lightgbm


### Installation and Setup

* Clone the repo
* Install all dependencies listed above
Models:
* Open the Model_Evaluation.ipynb file and run all of the models labeled 1 through 10.
* The results for all of the trials will be printed to the f_model_eval_log.csv file.
Neural Network:
* Open the Neural_network_evals.ipynb file.

* Run the notebook and scroll to the bottom to see the model's results.
* The log files related to the keras-tuning can be found in the folder labeled ‘keral_tuner_log’.

## Conclusion
Our analysis revealed challenges in accurately predicting diabetes status, as none of the models we tested achieved an accuracy higher than 75%, even after optimization. Neural networks, despite their complexity, did not outperform traditional machine learning models such as logistic regression or decision trees. This outcome suggests potential limitations in the dataset, including its quality and the challenges associated with its balanced nature.

## Authors

* [Nicholas Fussy](https://github.com/nfussy)
* [Samantha Eaton](https://github.com/SamEaton20)
* [Abigail Serpa](https://github.com/AbigailSerpa)
* [Micah Springer](https://github.com/micah-11101)

## Version History

* 0.1
	* Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details




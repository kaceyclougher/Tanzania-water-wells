# Predicting Functionality of Tanzanian Water Wells
### Author: Kacey Clougher

Within this repository, you will find a comprehensive analysis that classifies Tanzanian water wells into three categories: functional, non-functional, or in need of repair. The aim of this detailed analysis is to ensure accessibility and replicability.

![bb 2014-02-18 12-05-49](https://github.com/kaceyclougher/Tanzania-water-wells/assets/137820049/37004b15-6709-4794-8518-d151b3c2936c)

## Repository Structure
- Water-Wells-Final.ipynb: Modeling process
- EDA-and-Cleaning.ipynb: Exploratory analysis and data cleaning for final data set
- README.md: High level README for reviewers of this project
- Tanzania Water Wells.pdf: Presentation for use cases

## Project Understanding

This project aims to employ machine learning classification models for predicting the operational status of water wells in Tanzania. The classification encompasses three groups: functional, non-functional, and functional but in need of repair. The ultimate goal is to leverage this modeling approach to forecast the functionality of a newly constructed well or the rejuvenation of an existing non-functional well.

## Data
Using machine learning classification models to predict the operational status of water wells in Tanzania, we classify each well into three categories: functional, non-functional, and functional but needs repair. You can find the original data set of over 60,000 wells here: [Pump it Up: Data Mining the Water Table] (https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/). Additional features of this dataset included excavation type, age of well, waterpoint type, etc. 

## Modeling and Methods
The data underwent preprocessing, including feature engineering, filling missing values, and scaling, with the aim of enhancing the accuracy of the model. A logistic regression model was employed to forecast the operational status of water wells in Tanzania. An initial baseline model and a simple first model were developed to establish a foundational understanding of the data. Subsequently, an extensive grid search was conducted to identify optimal hyperparameters for the final model.

## Results
The model successfully met the target range of 75% ± 5% at a score of 0.7512, and further affirming its success, the test metrics include an accuracy score of 0.7512, a precision score of 0.7435, a recall score of 0.7512, and an F1 score of 0.7337. 

![Screen Shot 2023-10-08 at 2 06 09 PM](https://github.com/kaceyclougher/Tanzania-water-wells/assets/137820049/4c498b81-ea98-42d1-8a92-f80e92bee67e)

## Conclusion
This model effectively predicts the operational status of future Tanzanian water wells, achieving a 75.12% accuracy in distinguishing between functional, functional but in need of repair, and non-functional categories. While the variance between training and test scores suggests some overfitting, it falls within an acceptable 10% range, prompting its adoption. To address overfitting, the next steps involve implementing regularization techniques as well as exploring alternative models better suited to the data problem.

## Presentation and Sources
- Presentation designed for Tanzania Ministries of Natural Resources and Tourism to propose model. You can view the presentation from the repository [here](https://github.com/kaceyclougher/Tanzania-water-wells/blob/main/Tanzania%20Water%20Wells.pdf).
- The presentation is a part of a larger modeling competition by DrivenData: [Pump it Up: Data Mining the Water Table] ([https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/)

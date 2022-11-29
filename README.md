# Vehicle Price Prediction

### Business Understanding
A car dealership with multiple locations has a large vehicle inventory and is currently facing financial challenges.

Keeping a large inventory with a significant number of vehicles that are either difficult or unable to sell has a negative impact in its profitability.

The car dealership believes the business problem relies on a poor understanding of what the customer demands is and therefore wants to better understand what factors determine car prices, such understanding will drive the decision-making process to optimize the vehicle inventory.

The goal is to analyze a dataset containing information on 426K vehicles by applying both descriptive and inferential statistics to later develop and evaluate multiple regression models to predict car prices based on vehicle characteristics.

The results and insights will serve as recommendations for the car dealership to optimize the vehicle inventory and eventually improve its profitability.

### Methods Used
* Descriptive Statistics
* Inferential Statistics
* Data Visualization
* Predictive Modeling
* Machine Learning

### Evaluation Metrics Used
* Mean Squared Error (MSE)  
Is a most used and very simple metric, it represents the squared distance between actual and predicted values. we perform squared to avoid the cancellation of negative terms and it is the benefit of MSE.

* R Squared (R2)  
Is a metric that tells the performance of the model, not the loss in an absolute sense that how many wells did the model perform.
So, with help of R squared we have a baseline model to compare a model which none of the other metrics provides. 
Hence, R2 squared is also known as Coefficient of Determination or sometimes also known as Goodness of fit.

### Technologies Used
* Python
* Pandas, Jupyter
* scikit-learn

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Dataset is kept [here](data) within this repo.
3. Run Jupyter notebook.

## Deliverables
* Jupyter notebook: [vehicles-price-prediction.ipynb](link)

## Author
* [Ivan Santaella Martinez](mailto:itsantaella@gmail.com)

## Findings
* The dataset presented some challenges from the data quality standpoint such as outliers and missing values for multiple features.
* Most of the data quality issues were addressed during the data preparation phase.
* After evaluating multiples models and their quality, the following vehicle characteristics  are the most important:
  * fuel: gas
  * transmission: automatic
  * condition: excellent or good
  * title status: clean
  * paint color: white, black, silver
  * size: full-size, mid-size
  * drive: fwd
  * type: sedan, SUV
  * cylinders: 4 cylinders
  * manufacturer: ford, honda, toyota

## Next steps and recommendations
* Develop a plan for a pilot deployment of the model in some car dealership locations.
* Implement data quality controls for vehicle data gathering to improve data quality for future model development.
* Vehicle model feature may have some prediction power, however due to many vehicle models in the dataset, it was not included in this iteration.
* Include external data sources to standardize vehicle model in dataset to improve model quality.

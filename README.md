# Holiday-Package-Recommended-Prediction

The data set is downloaded from kaggle 

## Problem Statement:
*To predict which customer is more likely to purchase the newly introduced travel package and also to known which customers should be targeted more.*

## Libraries Used:
- Pandas
- Numpy
- Matplotlib
- Scikit learn
- Seaborn

## Flow of Project:
- Import the needed libraries
- Read the Dataset
- Basic information about Dataset
- Drop the unique partten column
- Cleaning
  - Missing value Treatment
  - Dtype Convertion
- EDA-Exploratory Data Analysis
  - correlation
  - Heat Map
  - Data Visualization
- Model Before EDA
- EDA
  - Class Imbalance Treatment
  - Outlier
  - Skewness
  - Feture Selection
- Model after EDA
- Conclution
  - Graphical Representation Of Output
  - Data frames of output
  - Cross validation
 
## Information about Target  Data 
Product taken is my target column and my target column is categorical.
The ML Model used will be Classification Model. The Classification algorithm is a Supervised Learning technique.
The data is in binary form (0,1).

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest 
- Ada Boost
- XG Boost 
- Support Vector Machine(SVM)
- Naive Bayes

## Best fit Model:
### Random Forest
Random Forest  is giving a good accuracy, precision, recall and F1 score comparing  with other models. Graphical Representation of Random Forest (ROC-curve)varies in before
and after eda.
 
## Basic information Observed From Given Data
1. From the given data we can Observ that there are less chances of accepting the new holiday package
2. The self enquire people mostly picking the basic and deluxe package are taken more
3. king product pitched(package) is selected by rare persons
4. From the graph the average income of traveler is ablove 20k 
5. The persons with Designation of Manager and Executive are traveling more
6. The maximum number of trips that are taken by the traveler are married and no.of trips taken are 2 to 3 trips
7. Self enquired Peoples are more compared to  company invited people

### Report from the observed information To increase the Travelers and Marketing.
1. The newly creating package should be similar to basic and deluxe package and it should be budget friendly
2. The persons with Designation of Manager and Executive are traveling more so these peoples can be focued more for marketing
3. Self enquired Peoples are more compared to  company invited people. So there is a chance of increasing the marketing



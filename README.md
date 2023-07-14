# Inspection-Data
# **Wine Sales Prediction**
## Build a model and predict the wine price

- **Author:** Jacob Tanzi 

## **Project Desciption**
### Our Stakeholders need to price their wine on par with their competition. They are new to the market, and pricing their wine too high or too low would have a dramatic effect on their customers expectations.

### **Overview**
Using wine data, we will create a model to assist their pricing guidelines. Using features like body, rating, acidity, year. We will provide our stakeholders with guidence.


### **Data Source**
https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset

There are 7500  rows, and 11 columns.

### **Data Dictionary**
![image](https://github.com/jtanzi56/Spanish-Wine-Data-price-prediction-/assets/130960008/10acf8da-eed1-4d6e-9a47-ec0430822ebe)


## Methods
- Data was cleaned and analyzed. A wide range of prices, from 4.99 euros to over 3k, gives us great options. We can see correlations with wine price, to many different features. From wine that would be considered high end, low end and everywhere inbetween.
  

### Exploratory Data Analysis
![sp wine b p a r](https://github.com/jtanzi56/Spanish-Wine-Data-price-prediction-/assets/130960008/b0045a4c-b136-40b4-bf8b-11df85e0ecdf)
Here we see that most wines are rated 4.3 and a range of only 4.2-4.9. Acidity is mainly classified as 3. 


![Screenshot 2023-07-14 053007](https://github.com/jtanzi56/Spanish-Wine-Data-price-prediction-/assets/130960008/cf225acf-7529-4b76-8653-335bbf729070)
Here we can see how rating and price are relate to eachother. The lowest rating of 4.2 does not have any wines over 1000 euros. But the highest rated wines are not the most expensive.


##  Models:
    - Decision Tree Regression
    - Random Forest Regression
    - Regression Neural Model
    - Keras Neural Networks  
    
## Models Evaluated & Results

 - Tuning with Gridsearch CV 
 - Feature Engineering
 - - Clustering
   - Binning

## Best Results
The Regression Neural Network Model works the best.

The MAE: of 25.79 is great, that will be the amount on average the prediction will be off.

R2: of 64% showing us that 64% of the variance in the target, can be explained by the features we used.

This model will help the steakholders solve their pricing problem, giving them a roadmap to price their wines based off rating, body, type, year and other features that are well known to them.

## Recommendations:
I recommend the stakeholders adopt this model to assist in theirpricing guidelines, 

or 
that they provide us with a list of wines and corresponding feature that we can model for them and provide pricing recomendations. 


## Next Steps
We will continue to update and tune this model and I hope to test it against other wine lists soon.


### For further information

For any additional questions, please contact:
-Jacob Tanzi
**Jtanzi56@gmail.com**

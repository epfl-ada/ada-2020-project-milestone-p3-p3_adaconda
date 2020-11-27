# Enhancing predicition of civil war onset with terrosism dataset and neural network model

## Abstract
The examined civil war paper shows that most models developed to date show poor performance at predicting civil war onset in out-of-sample data. This project will explore an extension of the work and analysis done in the civil war paper with the goal of enhancing the predictive power. We want to know if the methods used in the paper are extensible to other Machine Learning methods. The project will be two-fold. First, a model based on artificial neural networks (ANN) and a Random forest model (RF) will be implemented and evaluated on the original dataset. Secondly, data from the Global Terrorism Database will be added to the original features of the prediction model. The original dataset (civil war) spans from 1945 to 2000 while the added dataset (terrorism) spans from 1970 to 2018. For simplicity, the model will be developed on data from 1970 to 2000. A performance-evaluation will be performed to assess the utility of the terrorism data. Indeed, the hypothesis put forth by the authors: 
>There is a correlation between terrorist attacks and civil war onset. 
We want to compare the efficiency of the two models: Random forest and the neural network. Furthermore, we want to propose and select features that could be important for the predictive power of the ANN and that seemed relevant for us.



The new, enhanced model will be evaluated using ROC-curves and other relevant machine learning (specifically ANN) metrics.


## research question(s) 
Can we enhance the predicition power on civil war onset by adding additional features, such as terrorism data ?
Can training artificial neural network improve prediction results compared to Random Forest (RF) ?


## proposed data set 
Note : the different data set here would be merged into one to create an extended civil war data set
1. civil war data set (CDW)
2. terrorist attack data set (to merge with CWD)
	https://gtd.terrorismdata.com/
3.

## methods
We proposed two methods to improve the paper results:

1. Add more features to the CDWt to refine the result and then to enhance the models and the resulting prediction
List of possible features:
- Terrorist attack
	[not in the data set], dataset above
- Happiness -> Note: official world happiness index (UNO) is recent so we have to calculate it!
	[not in the data set, but we need a calculation method. Several variables present in the data set: political status, school, literacy, gdp~living standard, infant mortality, life expectancy]
- Political system 
	[mirps0,1,2,3 ,part of the 91 variables but not used for the logistic regressions]
	[auto4,dem4,fedpol3,sip2]

2. Apply Artificial Neural Network (ANN) method to the original and extended CDW. Indeed, this method is a machine learning method such as Random Forest. The main point here is to determine if the results of the paper can be generalised to other machine learning method. the secondary purpose is to see how this method has a different efficiency compared to Random Forest.

To visualize and interpret the different models obtained we propose the following graphic methods :
- ROC plots 
- K-folds cross validation
- Plot of the variable importance in Gini Score
- Sensitivity analysis: we want to answer this question: how much do the parameters contribute to the prediction?

## proposed timeline
1. 4th December: Data wrangling, Training of models (RF, ANN)
2. 11th December: Testing of models, results: visualization, interpretations, calculations
3. 18th December: Deadline - Milestone P4, Code cleaning, code commenting, discussions

## Organization within the team
Jean: Data Wrangling
Paul: ANN
Grég: RF
All: interpretation, discussion, visualizations

## questions for TA

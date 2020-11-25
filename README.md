# Enhancing predicition of civil war onset with terrosism dataset and neural network model

## Abstract
The examined civil war paper shows that most models developed to date show poor performance at predicting civil war onset in out-of-sample data. This project will explore an extension of the work and analysis done in the civil war paper with the goal of enhancing the predictions. The project will be two-fold. First, a model based on artificial neural networks (ANN) will be implemented and evaluated on the original dataset. Secondly, data from the Global Terrorism Database will be added to the original features of the prediction model. The original dataset (civil war) spans from 1945 to 2000 while the added dataset (terrorism) spans from 1970 to 2018. For simplicity, the model will be developed on data from 1970 to 2000. A performance-evaluation will be performed to assess the utility of the terrorism data. Indeed, the hypothesis put forth by the authors:
> There exist a correlation between terrorist attacks and civil war onset.

The new, enhanced model will be evaluated using ROC-curves and other relevant machine learning (specifically ANN) metrics.


## research question(s) 
Can we enhance the predicition power on civil war onset by adding additional features, such as terrorism data ?
Can training artificial neural network improve prediction results compared to Random Forest (RF) ?


## proposed data set 
Note : the different data set here would be merged into one to creat an extended civil war data set
1. civil war data set (CDW)
2. terrorist attack data set (to merge with CWD)
	https://gtd.terrorismdata.com/
3.

## methods GREG
We proposed two methods to improve the paper results
1. Add more features to the CDWt to refine the result and then to enhance the models and the resulting prediction
List of possible features:
- terrorist attack
	[not in the data set]
- happiness -> Note : official world happiness index is recent so we have to calculate it on our own
	[not in the data set, but we need a calculation method. several variable present in the data set : politcal status, school, literacy, gdp~living standard, infant mortality, life expectancy]
- economic situation 
	[gdpgrowth, and several other gdp related in the data set]
- political system 
	[mirps0,1,2,3 ,part of the 91 variables but not used for the linear regression]
	[auto4,dem4,fedpol3,sip2
- numbers of years since the last war (with a foreing country) 
	[note in the data set]
- number of years since the last civl war (easily calculated from the CDW)

2. Apply Artificial Neural Network (ANN) method to the original and extended CDW. Indeed, this method is a machine learning method such as Random Forest. The main point here is to determine if the results of the paper can be generalized to other machine learning method. the secondary purpose is to see how this method has a different efficency compare to Random Forest.

To visualize and interprete the different models obtained we propose the following raphic method :
- ROC plots 
- k-folds cross validation
- Plot of the variable importance in Gini Score
## proposed timeline JEAN

## organization JEAN 

## question for TA

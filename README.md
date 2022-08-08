# Project Name
> Prediction of bike sharing count with multiple linear regression.


## Table of Contents
* General Info
	Steps followed as 
	EDA, test-train split
	Feature Selection (RFE-p-value,VIF based) 
	Model Fit & Prediction with liabrary 
	Residual check, Prediction on test with R2 score
* Tools use:
	Python jyupitar notebook
	scikit-learn & statsmodel liabraries for regression fitting
* Conculsions:
	Finalized 7 variables based model with R2 ~73% on train and ~69.4% on test data
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## General Information
	Bike sharing is online platform where users book the bikes for self use. Pick up from one location and drop at other. Pandemic hit the buisness a bit. 
	Now the company wants to analyse the driving factor in particular region boost the buisness for future. 
	There are various factors are available in dataset, like rentals count, atmosphere conditions, date wise entries of share count. 
	This data is available for 2018 & 2019.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. The “temperature” has strongest positive impact on bike rentals
2. Next is the weather conditions have considerable negative corelation with count. During light snow condition rentals would reduce.
3. Holiday and whether a working day or not has an impact on bike sharing count. 
Holiday reduces the count by coefficient 0.04, while working day has higher bike users maybedue to 
registered users (seen from univariate analysis) This may be due to people using bikes for commuting to office.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - scikit-learn & statsmodel (RFE, VIF, Regression model fitting)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad & BoomBikes data 


## Contact
Created by [@ksoham9552] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
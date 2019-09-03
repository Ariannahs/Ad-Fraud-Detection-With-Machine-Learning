## Mobile Ad Anti Fraud with Maching Learning Algorithms - randomforest, lightgbm, catboost
### 移动广告反欺诈算法挑战赛 - 2019科大讯飞 
___
#### -EDA-  

- 0.Set configuration  
- 1.Explore on data  
1.1 Read data  
1.2 Shape and label distribution  
1.3 Feature description  
1.4 Identify missing value  
1.5 First glimpse of distribution of the data  
- 2.Data pre-process  
-fill missing value with existing columns/external data  
-clean punctuation/non-digit character/cases problem  
-timestamp\datatime\day\hour transformation  
-feature engineering by combining columns  
- 3.Data visualization  
-bar chart  
-line chart  
-subplotgrid  
- 4.Prepare dataset for modeling  
4.1 Correlation test for feature selection  
4.2 Label Encoding for non-numerical column  
  
  
#### -Modeling-  
(including simple model, cv model, parameter tuning, F1 score, AUC curve plotting, feature importance)     
- Randomforest  
- Lightgbm  
- CatBoost  
  

#### *For the main code and analysis, please read the .ipynb file.

The introduction is as belowed:
___
# Mobile-Ad-Anti-Fraud-Algorithm-Challenge 
(2019 iFLYTEK A.I. Challenge)   
## 移动广告反欺诈算法挑战赛 
2019科大讯飞 

Introduction:  

Advertising fraud is a major challenge facing digital marketing, with the maturity of basic technology (tampering device information, IPv4 service, black card, code-picking platform, etc.), advertising fraud presents a large-scale, group-based trend, its means of cheating mainly include robots, simulators, group control, chicken / back door, crowdsourcing and so on. Advertising fraud is constantly eating away at the marketing ecology, and anti-fraud has become a key issue in the field of digital marketing that needs to be broken.

Objective:  

This contest provides a large amount of current network traffic data from the AI marketing cloud as a training sample, and contestants need to build models based on the samples provided to predict whether traffic cheats or not.

Data description:  

The competition provides contestants with 5 types of data: basic data, media information, time, IP information and device information. The basic data provides the ad request session sid, as well as the "cheating" identification.

Media information, time, IP information, and device information, 4 categories of data, provide syllable information that may be helpful to cheating estimates. For data security reasons, all data is desensitated. The dataset provides a sample of several days, the last day of data is used for prediction, the data for the remaining dates is not given as training data.

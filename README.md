# Titanic competition

Random Forest: 

* 1st: 
  * Public Score: 0.78947
  * Feature: ['Survived', 'Pclass', 'Sex', 'Family_Survival', 'Fare', 'Age']
* 2nd: 
  * Public Score: 0.80861
  * Feature 修改 Fare, Age，因為從 Partial dependence 中發現，
    * Fare 票價超過 80 塊 對存活率沒有什麼影響，所以將 80 塊以上視為 80
    * Age 年齡超過 20 歲以上對存活率沒有什麼影響，所以將 20 歲以上視為 20

Deep Learning:

* 1st:
  * Public Score: 0.81339
  * Feature 使用 Random Forest 第二次結果
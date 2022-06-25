# Service Cancellation Predictor

Machine learning based system that can predict service cancellation for a business based on its dataset using 5 different machine learning models


<p align="center">
<img src="https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/splashScreen.gif" >
</p>

## About Project
 Service cancellation is when a customer decides to end thier businesses or unsubscribe from a service with a specific company. 
This system is oriented to determine the possibility of customers cancelling services. 
For most businesses, the ability to predict that a particular customer is at a high likelihood of cancelling service could actually result in a better way
for handling such problems.
Foreseeing business-related actions is the core of this project, and therefore, this system was developed to meet the business related requirements 
to predict user churn with an average accuracy of 78% with an attractive user-friendly UI.

<b>Dataset Link: [Service Cancellation Dataset](https://drive.google.com/file/d/1PrE7kY9h8yTawg0Ul0Ij5RFjiSO0hdYk/view)<b />
  
## Problem and Algorithms
  
Problem stipulated that based on 20 attributes and 7043 record we should make several models that predict whether a user will cancel his service or not 
we applied 4 models :
* `Decision Tree (ID3 / CART)` 
* `Logistic Regression `
* `SVM `
* `KNN`
  
Models consumed cleaned data and produced the following accuracies:   
| Model | Accuracy |
| --- | --- |
| Decision Tree(ID3) | 77.69% |
| Decision Tree(CART) | 74.2784% |
| Logistic Regression | 80.7109% |
| SVM | 79.18% |  
| KNN | 74.48% |  

## GUI
  
### Splash Screen  
![Splash Screen](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/splashScreen.gif)  

### Main Screen
#### Empty with no data
![empty inputs](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/noData.png) 
![inputs validation](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/dataValidation.png)
![methodology validation](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/noMethodology.png)
#### All data filled
![filled inputs](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/inputsWithAllData.png)
![how to fill inputs](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/toFillData.png)  
#### When customer cancels the service
![customer cancel service](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/coustomerWillCancelService.png)  
#### When customer keeps the service
![customer accept service](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/customerWillKeepTheServices.png)
#### Training model on input data
![train model](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/trainPhoto.png)  
#### Testing models accuracy
![test model](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/test_accuracy.png)
![test logistic regression model](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/test_accuracy_logisticReg.png)

  * Visualising results
  
![show graphs](https://github.com/NourAyman10/ServiceCancellationPredictor/blob/master/showGraphs.png)  
 
## Contributors
- [Mohamed-Samy26](https://github.com/Mohamed-Samy26) 
- [RedBiscuits](https://github.com/RedBiscuits)
- [KareemHussen](https://github.com/KareemHussen)
- [NourAyman10](https://github.com/NourAyman10)
- [HaneenIbrahim2](https://github.com/HaneenIbrahim2)
- [OmarSherif2](https://github.com/OmarSherif2)
- [Abdelrhman-Sayed70](https://github.com/Abdelrhman-Sayed70) 

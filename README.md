# Predictive-Modelling---Animal-Adoption
This project is a predictive modelling on animal adoption data using SAS EMiner. 
The data was extracted from Kaggle: https://www.kaggle.com/aaronschlegel/austin-animal-center-shelter-outcomes-and


The goal of the analysis is to predict the fate of the dogs in the shelter, whether they are adopted or not. This data set contains details and outcome of the animals in Austin Animal Centre Shelter from 10/1/2013. The original data set has more than 70000 rows and a total of 12 columns containing the age, animal ID, type, breed, color, date of birth, name and several outcomes which range widely from adoption to euthanasia. 

For predictive modelling, the type of animal selected to be analysed is dogs. Hence, the data set is cleaned and manipulated to fit the objective. Missing values as well as other unrelated columns are deleted to make things simpler for modelling. Factors that are taken into consideration for the outcome prediction would be the sex, age, colour and condition of the dogs.

The predictive modelling was completed on the SAS EMiner software. There were several processes we did which includes data preparation and the different modelling techniques. Based on the attached document that can be ran on the software, the results is as follows:

Tree5 which is a decision tree with data partition ratio of 80:20 (training:validation), default partition method is selected. The misclassification rate turned out to be the lowest among other models. According to the validation, the accuracy of this model is the highest with a score of 79.35% of the dogs would be adopted in the shelter or the misclassification rate of 20.65%. The subtree assessment plot for the misclassification rate shows that there is sufficient training as the separation of both train and validate are minimal. This model has the lowest complexity with five number of leaves and four attributes to predict the fate of dogs in shelter. The best node for adopted is not intact with the validation percentage of 83.06% and not adopted is the age upon outcome years (less than 0.5) with the percentage of 73.54%.  This means that the model is able to identify the adopted is better than not adopted. Based on the best model selected, when a new dog goes to the shelter it is predicted that 100% of the dogs would be adopted with the confident level of accuracy is 79.35% and 20.65% that it might guess wrongly.


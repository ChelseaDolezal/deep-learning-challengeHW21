# deep-learning-challengeHW21


Purpose 
The purpose of this analysis is to build and evaluate a deep neural network (DNN) model to classify applications based on their features. The model aims to whether applicants will be successful if funded by Alphabet Soup.

Data Import and Cleaning
The initial dataset was imported from a CSV file. There were some non benefit columns such as 'EIN' and 'NAME' which were dropped. 

Architecture
The neural network was defined using TensorFlow/Keras with an inner layer, 3 hidden layers and an outer layer.

Training 
The model was trained for 20 epochs with a batch size of 32 and a validation split of 20%. 

Summary 
The model had a high level of accuracy on both the training and validation datasets, which shows good performance and generalization. The loss metrics indicated that the model was learning effectively and not overfitting too much.

The Random Forest Classifier could be another option. From what I am seeing its easy to use and versatile, can handle big data sets which would be good for real world problems like this assignment where we are looking to select the applicants for funding with the best chance of success.


Conclusion
I think the model shows strong performance in classifying charity applications, achieving high accuracy.

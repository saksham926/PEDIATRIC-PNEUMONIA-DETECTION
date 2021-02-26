# PEDIATRIC-PNEUMONIA-DETECTION
Pneumonia is an inflammation in one or both of the lungs that is almost always caused by a viral or bacterial infection. The inflammation interferes with the body’s ability to deliver oxygen and remove carbon dioxide from the blood. A person is more likely to get pneumonia as a child, known as pediatric pneumonia, than they are as an adult.

Symptoms of pediatric pneumonia depend on the cause of the infection and several other factors, including the age and general health of the child. Rapid breathing, a high temperature and coughing are three of the most common signs of the condition.

Here we have a kaggle dataset which can be accessed here https://www.kaggle.com/andrewmvd/pediatric-pneumonia-chest-xray ,which contain chest X-Ray images of NORMAL and PNEUMONIA affected person. Here I have build a model which contains of Convolution layers, Dropout layers, Maxpooling layers, Dense and Flatten layers and have got the training accuracy of 96.90% and validation accuracy of 81.41%.Here I have used L2 Regularization to prevent overfitting of our model. Here I have also used kerastuner to get the best possible hyperparameters for our model.

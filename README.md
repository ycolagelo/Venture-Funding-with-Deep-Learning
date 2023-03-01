# Venture-Funding-with-Deep-Learning
![Image](download.jpg)


# Predicting which file which applicants will be sucessful if funded by a company. 


# Creating a model that predicts which applicants will be successful after receiving funding. 
Using a csv file containing more than 34000 organisations that have received funding over the years. With knowledge of Machine learning and neural Network, I use the dataset to create a binary classifier model that will predict whether an applicant will become a successful business. 

The Data was prepared and unnecessary columns were dropped
OneHotEncoder was used to Encode categorical Variables, placed into new Datasets and later concatenated to dataframe containing encoded data
Data was split into X features and Y target and further split into training and testing datasets


#   Compile and Evaluate a Binary Classification Model Using a Neural Network

First attempt: I used two hidden layers activated by Relu. 
* Accuracy was 0.47
* Loss was 0.60
Second attempt: I used two hidden layers activated by sigmoid.
* Accuracy went up to 0.73
* Loss went down to 0.5489
Third attempt: I used two hidden layers activated by Relu and the outer layer activated by sigmoid.
* Accuracy slightly improved to 0.7320
* Loss slightly went up to 0.5523.

Each model was saved in an HDF5 file. 

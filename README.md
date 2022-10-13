# Neural_Network_Charity_Analysis

# Project Overview
For this project, we will help Alphabet Soup, a nonprofit organization that raises funds for charities, to analyze which organizations are worth donating to, review their history and which were successful in the past. We started from a CSV database with all the organizations that received funds from Alphabet soup over the years, and we will develop a Deep Learning Neural Network Model using the Python TensorFlow library. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively


# Resources
- Dataset: Charity Data
- Tools: Python, Pandas, Numpy, Scikit, TensorFlow, Jupyter lab

# Results 
# Deliverable 1: Data Preprocessing
For this deliverable, the EIN and NAME columns are dropped because they are the identification information and hold no value to the model. the variable IS_SUCCESSFULL is the target for the purposed model, and the variables APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS,  INCOME_ANT and ASK_MT as the features of the model.

<img width="1105" alt="Screen Shot 2022-10-13 at 11 02 22 AM" src="https://user-images.githubusercontent.com/105765150/195634089-02a7c788-0e85-441b-8ccb-2031aa7d8761.png">

## Dataset after processing for the Neutral Network Model
<img width="1115" alt="Screen Shot 2022-10-13 at 11 21 02 AM" src="https://user-images.githubusercontent.com/105765150/195638312-7139d575-2492-4c9a-bab4-a5fbcc760feb.png">

# Deliverable 2: Compiling, Training and Evaluating the Model
## Model Summary
<img width="552" alt="Screen Shot 2022-10-13 at 11 32 43 AM" src="https://user-images.githubusercontent.com/105765150/195641029-1c11dbec-62b1-49cc-9823-832361ccc69a.png">

- This model reached an accuracy of 72.45%, but not the 75% requested, and a lost of 56.49%
- 80 neurons in the first layer and 30 neurons in the second
<img width="1105" alt="Screen Shot 2022-10-13 at 11 50 27 AM" src="https://user-images.githubusercontent.com/105765150/195645148-e0a5d604-ddb2-4303-b048-cdbfc7a2d39b.png">

# Deliverable 3: Optimization of model performance
## Attempt 1: Removing Features
<img width="896" alt="Screen Shot 2022-10-13 at 12 03 20 PM" src="https://user-images.githubusercontent.com/105765150/195647912-4b69a2be-d93b-4e1d-9a0a-444737b8ad76.png">

## Attempt 2: Adding Additional neurons to hidden layers and additional layers are added
<img width="841" alt="Screen Shot 2022-10-13 at 12 05 41 PM" src="https://user-images.githubusercontent.com/105765150/195648383-2d908987-726f-4b3a-a61b-c9cb66f8edad.png">

## Attempt 3: Changing activation function of output layer

<img width="1097" alt="Screen Shot 2022-10-13 at 12 07 15 PM" src="https://user-images.githubusercontent.com/105765150/195648780-31054cfe-3df7-4adc-8d8b-0fa5e08e16f4.png">


# Deep-Learning-Challenge
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:
* **EIN** and **NAME**—Identification columns
* **APPLICATION_TYPE**—Alphabet Soup application type
* **AFFILIATION**—Affiliated sector of industry
* **CLASSIFICATION**—Government organization classification
* **USE_CASE**—Use case for funding
* **ORGANIZATION**—Organization type
* **STATUS**—Active status
* **INCOME_AMT**—Income classification
* **SPECIAL_CONSIDERATIONS**—Special consideration for application
* **ASK_AMT**—Funding amount requested
* **IS_SUCCESSFUL**—Was the money used effectively

## Instructions
1. Preprocess the Data
2. Compile, Train, and Evaluate the Model
3. Optimize the Model
4. Write a Report on the Neural Network Model

## Results 
In this project, I ran approximately 5 different models using different combinations to compile, train, and evaluate the model (Resource: AlphbetSoupCharity file). These models removed the EIN and NAME columns and with applying different neurons and layers and binning achieved an accuracy of 73%.

<img width="753" alt="Screenshot 2024-07-31 at 2 33 05 PM" src="https://github.com/user-attachments/assets/63a8ff5f-a956-44a1-8f53-e8e1a9210725">

<img width="503" alt="Screenshot 2024-07-31 at 2 35 09 PM" src="https://github.com/user-attachments/assets/5ea8b34c-73e1-4e35-ace1-aad039636c9d">

As stated before, even my best model did not achieve the desired accuracy of 75% using these combinations of neurons, layers, and activation functions. 

Next, I created a different model which only removed the EIN column (Resource: AlphabetSoupCharity_Optimization file). The model did great, achieving a performance of nearly 80% accuracy! 

<img width="754" alt="Screenshot 2024-07-31 at 9 21 04 PM" src="https://github.com/user-attachments/assets/f1bbe6c7-4a78-4f6f-9f85-1148a75eff64">

<img width="499" alt="Screenshot 2024-07-31 at 9 21 24 PM" src="https://github.com/user-attachments/assets/5290cbb1-b1e1-449a-9f7b-ea13efa7e0ea">



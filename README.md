# deep-learning-challenge

For this project, Alphabet Soup has tasked us with developing a tool that can help it in selecting the funding applicants with the highest chance of success in their ventures. Using Alphabet Soup’s CSV data containing more than 34,000 organizations that have received Alphabet Soup’s funding over the years, we are to develop a binary classifier neural network model to be used as a tool for finding funding applicants that are best likely to succeed with a target accuracy of 75%. The data consists of the following columns:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Dependencies and Libraries
The following dependencies and libraries were used for this project:
- sklearn.model_selection, train_test_split
- sklearn.preprocessing, StandardScaler
- pandas 
- tensorflow 

## Steps
To develop the model, the following steps were completed:
1) Preprocess the Data - this involved identifying the target and features variables, dropping unnecessary columns, and encoding and splitting, and scaling the data.
2) Compile, Train, and Evaluate the Model - this involved using Tensorflow to create the first instance of the model.
3) Optimize the Model - this involved tweaking various parameters of the model to try and improve the target accuracy, such as increasing hidden layers, changing activation functions, and changing neuron counts for hidden layers.
4) Analysis Report on the Model - this involved understanding the approach taken to create the model, the various optimizations attempted and the results yielded, as well as whether this model can be implemented or if further improvements are recommended. 


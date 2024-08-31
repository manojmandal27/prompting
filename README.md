# Problem Statement
Generating a prompt / prompts using no code based LLMs to solve a text classification problem.
Dataset: Spam / ham classification
# Learning Objectives
At the end of the project, you will be able to :
Understand how to successfuly generate code using LLMs
Following sections will help you understand the various steps required for text classification:
Create text vectorization layer.
Create embeddings of words in the message.
Visualize the different categories of words.
Build a model to classify the messages as Spam or Ham.
Get the evaluation score of the model.
Dataset
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
Link: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

# Steps to generate code by prompt :
Imagine yourself as a python expert to code the below as per steps defined: 

Step:0 Use Dataset: Spam / ham classification
     URL :https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fuciml%2Fsms-spam-collection-dataset
     Download and extract the zip file and show first 5 samples of data.

Step1:Import Necessary Packages for code generation with tensorflow, sklearn,sea born, matplotlib , numpy ,pandas etc.

Step2:Read the Data & basic cleaning remove NaN columns , duplicates , rename labes etc. Optionally you can use NLTK , Spacy to remove punctuation, stopwords, Reg Expressions , Lamization etc.

Step3:Explority data analysis like counts

Step4:Apply the Vectorization to the text data using TextVectorization


Step5:Find words are maximum coming under SPAM & HAM lebel. Show top 20 samples

Step6:Split the data into training, test and validation dataset

Step7:Extract the Embeddings before Training

Step8:Train the Model : Model Arch - Neural network Relu, Sigmoid

Step9: During Training Collect the loss and Metrics of Train and Validation. Plot the Metrics after Training like make confusion matrix

Step10:Calculate and Display the Test and validation Performance

Step11:Extract the Embeddings after Training. Use Top 10 words from 
SPAM:[Free,Call,Text,Now,Urgent,claim,won,collect,prize,mobile]  and 
HAM:[love,need,know,time,want,come,make,think,thing,good] and show the similarity using PCA and plot

Step12:Reduce the Embeddings using PCA

Step13:Plot the Embeddings in 2D with words name displayed

Step14:Take a example SMS and show if the model is able to predict the outcome

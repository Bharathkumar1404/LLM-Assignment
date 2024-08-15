# LLM-Assignment- TEXT CLASSIFICATION ON R8 DATASET BY USING BERT BASE MODEL
           


TABLE OF CONTENTS:
•	INTRODUCTION
•	DATASET OVERVIEW
•	EDA
•	MODEL IMPLEMENTATION 
•	PREPROCESSING
•	FINE TUNNING
•	CLASSIFICATION

INTRODUCTION:  
In this assignment we have used a pre trained Bert base model to train the dataset R8. The task done by model in this assignment is text classification, it is one of the essential method in Bert model, this method is essential in a variety of applications, including spam detection ,sentiment analysis subject tagging and document organization , in this assignment I have classify the news data into 8 different label and it is done by using text classification Bert base uncased model.

DATASET OVERVIEW:
   The R8 dataset is a benchmark dataset used in the field of text categorization, specifically, to evaluate algorithms for news articles. It contains roughly 8,000 documents divided into eight unique categories, including "acquisition," "crude," "earn," "grain," "interest," "money-fx," "ship," and "trade." Each item in the dataset is a news article, making it an excellent resource for testing and training models on classification problems. These are having training data contains Approximately 4,937 documents, validation data contains Approximately 548 documents and test data contains 2,189 documents.
EDA:
By using the train data, I have done some visualisation by using the plotly and word cloud function in this the bar plotty describes  the label and their count and the word cloud function describes the most common words present in the data text columns by using this function  I have explored the data and do some visualisations
MODEL IMPLEMENTATION:
 In  this project I have used a pre-defined Bert base model to classify the data, the model is Bert base uncased it’s the model and pipe line used is text classification it means it is the task which needs to be done  in the process. The BERT (Bidirectional Encoder Representations from Transformers) base uncased model analyses text using a transformer architecture that comprehends context in both directions—left-to-right and right-to-left. For text classification tasks, such as categorizing news items, BERT uncases the input text before tokenizing it into sub word units. These tokens are subsequently transformed into embeddings, which are processed through various layers of self-attention processes to capture the contextual links between words.
PREPROCESSING:  
For this method I have the tokenization and after the tokenization i have mapped the data in this tokenization I has the tokenize the data by separating the words into tokens and then convert them in to input ids for the model training so how the preprocessing works
FINE TUNNING:
For this process we use the processed tokenized data to train the model from by giving the different parameters for the training fine tunning processes the accuracy of the data will evaluates by using that we prediction the future outcome so in the way the model will works.
CLASSIFICATION: after completing the fine tunning process we will get the evaluation metrics so that we get the accuracy, F1 score and support  for thus model after using on the R8 dataset  I have got an accuracy of 98 percentage and f1 is around 90 from that we can classify and predict the test data with high accuracy values.




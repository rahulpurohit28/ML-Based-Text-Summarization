# ML-Based-Text-Summarization
ML Model for Extractive Text Summarization of BBC News Articles (Kaggle Data Set) 
### Text Summarization 
The technique for generating a concise and precise summary of voluminous texts while focusing on the sections that convey useful information, and without losing the overall meaning. 
### Benefits  
1. Summaries reduce reading time.
2. When researching documents, summaries make the selection process easier.
3. Automatic summarization algorithms are less biased than human summarizers.
4. Personalized summaries are useful in question-answering systems as they provide personalized information.
5. Using automatic or semi-automatic summarization systems enables commercial abstract services to increase the number of texts they are able to process. 
### Types 
1. Extraction-based summarization
A subset of words that represent the most important points is pulled from a piece of text and combined to make a summary.
Extractive summarization usually involves weighing the essential sections of sentences and using the results to generate summaries.

In the current project Extractive summarization technique using ML model will be developed. 

2. Abstraction-based summarization
In abstraction-based summarization, advanced deep learning techniques are applied to paraphrase and shorten the original document, just like humans do. 

### Data Set Description 

Data Set used : BBC News Summary (Kaggle Dataset)  
https://www.kaggle.com/pariza/bbc-news-summary

Description : The dataset for extractive text summarization has five categories of news articles of BBC from 2004 to 2005 in the News Articles folder. For each article in each category, five summaries are provided in the Summaries folder. The first clause of the text of articles is the respective title.   

Each news article is stored in .txt file , and is placed in the respective category folder. 
The size of the Dataset is 7 Mb

### Methodology  
1. Preparation/Parsing of Text Data
2. Storing the documents into Data Frame, and the Target variable
3. Extracting Text statistics features 
4. Pre-processing Data
5. Generating Vectorial representation using Word2Vec Model 
6. Extracting Syntactic features from Vectors 
7. Training a base model with default Hyperparameters 
8. Hyperparameter Tuning using Grid Search CV 
9. Inspecting the performance of model  





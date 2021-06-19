# News Classification  

<img src="https://img.shields.io/badge/-Jupyter%20Notebook-orange"> <img src="https://img.shields.io/badge/Language-Python-cyan">
<img align="right" src="https://github.com/GarethSequeira/News-Classification/blob/main/NewsClassification/Images/NewsSq.png" width="300">   
  
#### Using the Real News and Fake News Dataset from Kaggle. <br> The Aim is to Analyse and Segregate Real News from Fake News.
<br>

### Table of Contents:  
1. [Approach](#Approach)  
2. [Requirements](#Requirements)  
3. [Setup](#Setup)  
4. [Summary](#Summary)  
<br>  

## 🔸Approach
#### This notebook follows a Visualization based approach to identify words occuring <br>  frequently in Real and Fake news and categorizes them accordingly. <br> Mentioned below is the flow of processes that has been followed.   
  
#### 🔸Data Visualization 
Visualising Uncleaned Data fom the Datasets using Word Cloud.
#### 🔸Data Pre-Processing
        Helper Functions
        Unique Word Analysis
#### 🔸Data Cleaning
        Punctuation Removal
        Numeric Value Removal
        Tokenization
        URL Removal
        HTML Tag Removal
        Emoticon Removal
        Stopword Removal
        Dataset Labelling
        Word to Text Conversion
#### 🔸Data Visualization 
Visualising Cleaned Data fom the Datasets using Word Cloud.
#### 🔸Model Creation
        Feature Extraction
        Cross Validation
        Pipelining
        Model Fitting
#### 🔸Model Evaluation
        Predictions
        Score and Metric Assesment
  
<br><br>  
  
## 🔸Requirements  
#### Jupyter Notebook  
#### Python  
     Packages:  
            re              #Finding or Matching Strings/Texts   
            nltk            #Natural Language Processing  
            numpy           #Arithmetic Operations  
            pandas          #Data Analysis and Manipulation  
            string          #Text and String Operations  
            itertools       #Fast Iteration   
            matplotlib      #Visualization and Plotting  
   
<br><br>  
  
## 🔸Setup  
Install Python and Jupyter Notebook if not done already.  
Download **NewsClassification** Folder with all files present.  
Unzip and Extract **NewsDataset.zip** to find **RealNews.csv** and **FakeNews.csv** Files.  
Place these 2 CSV Files in the same location as the Notebook.  
Open and Initialize **NewsClassification.ipynb** on Jupyter Notebook.  
<br><br><br>    
  
## 🔸Summary  
#### Real News Stopwords:
On Cleaned Data  
<img align="left" src="https://github.com/GarethSequeira/News-Classification/blob/main/NewsClassification/Images/RealNews.png" height="350">   
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

#### Fake News Stopwords:
On Cleaned Data  
<img align="left" src="https://github.com/GarethSequeira/News-Classification/blob/main/NewsClassification/Images/FakeNews.png" height="350">   
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

#### Model Evaluation:  
<img align="left" src="https://github.com/GarethSequeira/News-Classification/blob/main/NewsClassification/Images/ModelEval.png" width="650">   


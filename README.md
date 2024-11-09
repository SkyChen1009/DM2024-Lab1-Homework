# Data Preprocessing Section with the state-of-the-art tools

### This is homework 1 for ISA5810 Data Mining 2024 course Lab 1

## Table of Contents
1. Data Source
   - Load the data
   - Categorize all the target value
       
2. Data Transformation
   - 3.1 Converting Dictionary into Pandas dataframe
     - Import the modified helpers module in data_mining_helpers folder
     - Adding the category label (integer form) in the table
   - 3.2 Familiarizing the Data
     
4. Data Mining using Pandas
 - 4.1 Dealing with Missing Values
     - Check for null value (fortunately none)
 - 4.2 Dealing with Duplicate Data
     - Check for duplicate data (if none, add a dummy value to check it's functional)
       
5. Data Preprocessing
 - 5.1 Sampling
     - Randomly choose 1000 items in the original data
     - Visualize the data with matplotlib and seaborn
     - compare the distribution between original data and smaple one
 - 5.2 Feature Creation
     - **Import the NLTK to conduct tokenization.**
     - *Obtain unigrams as tokens or individual words*
 - 5.3 Feature Subset Selection
     - *from sklearn.feature_extraction.text import CountVectorizer*
     - **Transform article to term-document matrix**
     - **Heat map of the term-document matrix**
     - *Compute these frequencies for each term in all documents*
 - 5.4 Atrribute Transformation / Aggregation
     - **Take the word distribution and put it in a scale to analyze pattern**
     - *Sort the terms by frequenct*
     - **Finding frequent patterns using PAMI**
     - *Filter the top 5% and bottom 1% of the definite article and uncommon word*
     - *2 graphs ：Item frequemcy distribution & Transactional length distribution*
     - ***FPGrowth to mine for patterns in transactions***
     - **Focusing on unique patterns can significantly improve the classification process**
 - 5.5 Dimensionality Reduction
     - 5.5.1 PCA
     - 5.5.2 t-SNE
     - 5.5.3 UMAP
     - 5.5.4 Reduce the dimensionality into 3 and use 3D plot
     - **5.5.5 Generate better feature from term-vector matrix as TF-IDF**
 - 5.6 Discretization and Binarization
     - from sklearn import preprocessing, metrics, decomposition, pipeline, dummy
     - **preprocessing.LabelBinarizer()**
   
6. Data Exploration
     - Binarize the data using sklearn.preprocessing
     - Calculate the cosine similarity
8. Data Classification
     - **8.1 Multinomial Naive Bayes fits for documnet-term matrix
       
## Assesment
Accuracy: 0.8777777777777778

Classification Report:

     accuracy                         0.8778       450
    macro avg     0.8808    0.8802    0.8778       450
    weighted avg     0.8831    0.8778    0.8777       450

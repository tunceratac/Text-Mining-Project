# Text Mining Project

<h2>Objective</h2>
The goal of the term project is to gain practical experience with various text mining tasks. Tasks that the project covers are cleaning, preprocessing data, feature extraction, data visualization, model classification with machine learning algorithms, topic modeling, text summarization.

<h2>Project Description</h2>

<h3>Part A</h3>
A. There are two different folders in the dataset named ‘neg’ and ‘pos’. Read the data files and combine them to use as a whole. Examine the data in detail and clean it while applying 4 different preprocessing methods which are proper for the data.
<h3>Part B</h3>

B.1. Choose 4 different general features fit for the data and extract these features from the cleaned dataset.

B.2. Create Bag of Words and Term Frequency-Inverse Document Frequency models for the data that you cleaned in step A, compare 10 most frequently occurring words and choose one of the models which you think is more suitable to use as a feature for that dataset.

B.3. With the model that you choose in step B.2, determine the 50 most frequently occurring words and visualize them with Word Clouds.

B.4. Apply 4 machine learning algorithms to develop text classifiers into your data using features you extracted in part B. Apply k-means clustering, linear regression, one classification method and one tree based method that you think is more suitable for the data. Calculate the performance measures: confusion matrix, precision, F1 score, receiver operating characteristic (ROC) curve, root mean square error (RMSE). (Note: Decide the k by yourselves while trying a specific range).

<h3>Part C</h3>
C. Apply topic modeling to data that you cleaned in part A. Use Latent Dirichlet Allocation (LDA) algorithm. Decide the correct number of topics. Then, compare its results with K- Means algorithm.

<h3>Part D</h3>
D. Apply the text summarization method using TextRank algorithm for both ‘neg’ and ‘pos’ files in the dataset. Save the summarized texts as two different new .txt files (neg_summarized.txt, pos_summarized.txt).



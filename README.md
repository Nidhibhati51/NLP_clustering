# Text_clustering using NLP
## Abstract
We Have used nltk library to prepare the dataset for processing, cleaning, preparing and modelling. The preparion of documents has been done by removing stopwords, punctuations, stemming the words to make the data less comlicated for model generation. TF-IDF method is used to produce the matrix of vectors which we will use to produce  clusters by different clustering algorithms. For our problem, Guassian mixture is giving us best clusters than other clustering algorithms.
## Introduction
The intent of this project is to produce similar clusters of Gutenberg's digital library books using different clustering algorithms and comparion of performance and accuracy of each cluster. For this project, Seven different samples of Gutenberg's digital books are taken, which are of different genres and of five different authors, and are sementically different. Kmeans, Agglomerative clustering and Guassian mixture are used to produce the clusters. The accuracy and the performance is determined by Kappa and silhoutte score of each algorithm.
## Method and Dataset
The source of our data is the [Gutenberg digital library ](https://www.gutenberg.org/)which consists of 60,000 ebooks, which are ready to read and download. Data is loaded using 'nltk' library. These books are open source. You will find the world's great literature here, with a focus on older works for which U.S. copyright has expired. For our project, we have taken 7 different books in which 200 documents of each book is taken randomly and further 150 words records of each document is taken.
I have broken down the project into following sections (click to view code):
* [Removal of stopwords and tokenizing the texts of each book](https://github.com/Nidhibhati51/NLP_clustering/blob/main/Text_clustering_cleaning.ipynb).
* [Creating Tf-Idf matrix of all the merged books](https://github.com/Nidhibhati51/NLP_clustering/blob/main/Text_Clustering_tf-idf.ipynb)
* [Modelled the data and checked accuracy of each generated model](https://github.com/Nidhibhati51/NLP_clustering/blob/main/Text_clustering_model.ipynb)
* [Implemented the model on training dataset](https://github.com/Nidhibhati51/NLP_clustering/blob/main/Text_Clustering_train_model.ipynb)
* [Result and Conclusion](https://github.com/Nidhibhati51/NLP_clustering/blob/main/Text_Clustering_result.ipynb)
## In the end, it turns out that Gaussian Mixture performed the best in producing good clusters using BOW method.
![image](https://user-images.githubusercontent.com/72065690/138212866-c65489df-6f83-48df-bc04-11fd9e318a80.png)




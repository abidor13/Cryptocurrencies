# Cryptocurrencies

## Overview of the Project:

#### In this project we are creating an analysis for a client of ours who is preparing to get into the cryptocurrency market. At this point, we understand what Unsupervised Learning is used for, how to process data, how to cluster, how to reduce dimensions, and how to reduce the principal components using PCA.

#### Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of our most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked us to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.


## Results:

### This new assignment consists of four technical analysis.

* Preprocessing the Data for PCA

    * Using our knowledge of Pandas, we preprocessed the dataset in order to perform PCA, we first created a dataframe that we preprocessed, removed null values, dropped non important columns/features, and we also used get_dummies() to create variables for the Algorithm and ProofType features. Then finally we used StandardScaler().fit_transform function to standardize all features from the dataframe.

    [Load Data](Images/load_csv.png)

    [](Images/tradedcrypto2.png)

    [](Images/removedcolumns3.png)

    [](Images/standardized4.png)

* Reducing Data Dimensions Using PCA

    * Using our knowledge of how to apply the Principal Component Analysis (PCA) algorithm, we reduced the dimensions of the X DataFrame to three principal components and placed these dimensions in a new DataFrame.

    [](Images/pca1.png)

    [](Images/pca2.png)


* Clustering Cryptocurrencies Using K-means

    * Using our knowledge of the K-means algorithm, we created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame previously created. We then ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

    [](Images/elbowcurve1.png)
    [](Images/elbowcurve2.png)

    [](Images/kmeans2.png)

    [](Images/newdf3.png)


* Visualizing Cryptocurrencies Results

    * Using our knowledge of creating scatter plots with Plotly Express and hvplot, we visualized the distinct groups that correspond to the three principal components we created, then we created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.


    [](Images/scatter3d1.png)
    [](Images/scatter3d2.png)

    [](Images/tradablecrypto.png)

    [](Images/hvplotscatter.png)



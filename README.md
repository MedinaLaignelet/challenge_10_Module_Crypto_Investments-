# challenge_10_Module_Crypto_Investmentspto-

The objective of the challenge is to apply the unsupervised learning coding using python to cluster the performance of different crypto currency over time.  The challenge also requires to apply different visualizations to the clustering to analyze the crypto portfolio.
The file containing the code is located in the Git Repository File named crypto_investments.ipynb

## Data preparation and cleaning ##

The code used in my Jupyter Notebook starts by importing all the necessary libraries and dependencies that will be used for the Crypto Portfolio analysis and reading the CSV files provided with the crypto data,
Next, the code will create the Pandas Data frame from the CSV files and will calculate summary statistics and a plot to show the data.
To prepare the Data, the code will normalize it and will set up the column with the cryptocurrencies names as the index.

## Elbow Curve Method and K Means ##

The code sets up a lists and loop to calculate the inertia of possible K means in order to apply the  Elbow method  to find the K means. 
Using the previously found K-means, the code will then cluster the data by adding the cluster information as a new columns in a copy of the original data frame  and will use a scatter plot to visualize the clustering.

The code will then use the Principal Component Analysis approach for the same data by using 3 components by transforming the data and calculating displaying the variance ratio to determine the overall variance computed in the PCA model.

The code will then recalculate the new PCA adjusted date and apply the Elbow Curve method to calculate a PCA based K-means.  Finally, the code will also add the predicted cluster data to the new PCA adjusted data frame to plot the data using a scatter plot to visualize it.
The code then compares the two approaches to the crypto data clustering to analyze the similarities and differences between the Elbow Curve results and K means clustering of the different methods.

### Resources ###

Berkeley Extension- Fintech Bootcamp Camp material


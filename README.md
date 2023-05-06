# Constraining Cosmological Parameters using Supernovae

This notebook uses supernovae data, specifically, the data of the distance modulus vs. redshift to fit equations and constrain cosmological constants.

Here is an overview of our methods:
1) Fetch supernova data

2) Visualize data and get the data where redshift is small

3) Fit data with small redshift to the following equation and use the fitting results to calculate Hubble Constant $H_0$ and cosmological constant $q_0$.

$m - M = 43.17 - 5log_{10}(\frac{H_0}{70}) + 5log_{10}z + 1.086(1-q_0)z$           ------ (Eq. 1)


To better understand our data, we also try fitting our data backwards in the following steps, i.e., how well different $q_0$ fits our data.

4) Visualize the difference between our data fitted model and some hypothesized models.

5) Try different cosmological constants on our data and calculate the loss for each.

6) Use Cosmolopy package to more accurately calculate luminosity distance and thus the distance modulus.


Note: To run Part 6, you will need to install CosmoloPy Package by `pip install cosmolopy`.

Contributor: Charline Shen, Johnson Du
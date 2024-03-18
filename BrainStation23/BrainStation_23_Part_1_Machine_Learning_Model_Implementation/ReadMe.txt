Here both files are .ipynb and are run with Jupyter Notebook
EDA.ipynb contains all preprocessing and EDA analysis. It contains all the observation which we can get by performing EDA analysis and have been shown
with graphs. It also contains the implementation of KMeans.

Model_Final.ipynb contains the implementation of Random Forest and the preprocessed dataset is run with it. Here I did not run the code on the complete
dataset as it was taking a lot of time and resources. This has resulted a poor r2 score. Also because of these time and resource constraints I could
not do analysis with the model and its results. If you want to run the code on the full dataset comment out df=df.sample(frac=0.05).

Challenges:
Here I am converting the 'InvoiceDate' column to datetime . However in my notebook it shows error if I use (format='mixed'). So I have not used this.
 But in other devices or platforms it is advised to use format='mixed'. I have commented it.
 
Also the target variable which I want to predict is sales. It is computed by multiplying unit_price with quantity.
# Space_Y

For this project we needed to estimate the budget for each next space launch missions by creating a prediction model which 
determines whether the current mission phase 1 will successfully land or not. From the successful landing of phase 1 we can 
economize upto 65 million dollars by reusing the phase components.

Here we collected data by two means:
  - From an API
  - Webscraped the contents of a table from the falcon 9 mission launch wikipedia page
  
The data was saved into a Pandas dataframe and cleaned using Python in Jupyter notebook.
  - Null values were replaced with the mean of Payload mass for the payload mass column
  - The dataframe was isolated to contained only data relevant to falcon 9 launch missions only
  - Categorical features data were replaced with dummy values for easy processing of the data
  
After cleaning of the dataset EDA was performed:
  - SQL was used to perform exploratory data analysis to gain insight by querying the data
  - Python seaborn and matplotlib was used to create data visualization for exploratory data analysis as well
  - Plotly dash was also used to create a brief dashboard to gather insights as to which sites, payload range 
    and booster type had the most success
  
  Lastly, a prediction model was created:
  - SVM, logistic regression, decision tree and K-nearest neighbors machine learning algorithms was used to
    create a prediction model. The accuracy of the four models were compared to determine which specific model
    provided the best prediction. 
    
  The project finding was summarized in a powerpoint. 

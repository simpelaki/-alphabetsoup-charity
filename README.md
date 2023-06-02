# deep-learning-analysis

# Information
Using the charity_data I created a training model for the predictions. The data was read into a pandas dataframe and then preprocessed before training. For the preprocess, irrelevant columns such as EIN and NAME were removed. Then each column was reviewed to determine if binning the rare values would be a good approach to maximixe accuracy. Then the target variables and categorical values were determined and assigned as 'X' and 'y'. I used get_dummies() to encode the 'X' values before passing it to the train_test_split function to get the training and testing datasets. The training dataset was then scaled using StandardScaler() and fitted with the transform function. 

# Technologies Used
* Pandas
* TensorFlow and Keras
* Sklearn
* Google Colab
* Jupyter Notebook

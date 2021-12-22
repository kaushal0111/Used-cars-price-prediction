# Car-Price-Prediction
Complete Machine Learning Project
Used Car Price Prediction
This is a complete machine learning project that includes all processes of a typical machine learning life cycle from creating the project environment on your local computer to deploying the final app.py file on the cloud server.
Get the dataset from here.
Steps to follow before creating this notebook:
Create a virtual environment for your project on your local computer using "conda create --name myenv" or follow This Link for more details on creating s virtual environment using conda command prompt or follow this link. for more details on python package dependencies.
Activate the environment and launch the jupyter notebook that functions in the respective environment.
Pip install all the libraries needed for this project into the respective project environment.
NOTE: you can install the libraries as you go, that way you don't have to remember all required libraries in the beginning
NOTE: you can pip install all libraries either in the conda command prompt or in the jupyter notebook.
Steps to follow in this Notebook.
Giving summary about the project dataset and primary objectives.
Importing necessary libraries
Loading the car data.csv dataset
Analysing various columns of the dataset
Performing data cleaning and data visualization
Checking on null values in the dataset
Filtering and converting important categorical features into numeric columns using dummy variable technique
Performing Feature Engineering
Creating final dataset for spliting it into testing and training dataset
Splitting the final dataset into independent and dependent features X and y respectively and performing feature importance for optimizing the dataset for regressor algorithms
Splitting datasets further into testing and training dataset with test_size of 0.3
Implementing Random Forest Regressor after doing hyperparameter tuning
Selecting best hyperparameters using random grid and Randomized Search CV
After that, creating base model to tune
Trying random search of parameters using 3 fold cross validation
Implementing the final model rf_random
Predicting the independent feature of X testing dataset by implementing rf_random model and comparing predictions to y_test dataset.
Calculating Mean Absolute Error(MAE), Mean Squared Error(MSE) and RMSE, and dumping the model into a pickle file using pickle.dump
Steps to follow after finishing the notebook:

Fetch the requirement.txt file from your environment to get the list of all libraries needed to install for this project using "$pip install -r requirements.txt" or refer to this.
You will have the random forest regression model.pkl file generated after running this notebook.
Create app.py file that contains all the code described in the notebook in a concise one python file.
Run app.py on your local by activating the project virtual environment and writing python app.py command
An IP address will be given which can be put in any brower where you can access the project on your local computer
Create very basic frontend .html file for deploying the project on heroku.
Create procfile for heroku after referring this.
Create a free account on heroku
Create a new app in your heroku account and upload the files after choosing relevant deployment method.

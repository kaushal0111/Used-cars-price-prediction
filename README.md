# Complete Machine Learning Project
### Used Car Price Prediction

- This is a complete machine learning project that includes all processes of a typical machine learning life cycle from creating the project environment on your local computer to deploying the final app.py file on the cloud server.
- Get the dataset from [here.](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho)

### Steps to follow before creating this notebook:
1. Create a virtual environment for your project on your local computer using "conda create --name myenv" or follow [This Link](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands) for more details on creating s virtual environment using conda command prompt or follow [this link.](https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1) for more details on python package dependencies.
2. Activate the environment and launch the jupyter notebook that functions in the respective environment.
3. Pip install all the libraries needed for this project into the respective project environment.
    - NOTE: you can install the libraries as you go, that way you don't have to remember all required libraries in the beginning
    - NOTE: you can pip install all libraries either in the conda command prompt or in the jupyter notebook.

### Steps to follow in this Notebook.
1. Giving summary about the project dataset and primary objectives.
2. Importing necessary libraries
3. Loading the car data.csv dataset
4. Analysing various columns of the dataset
5. Performing data cleaning and data visualization
    - Checking on null values in the dataset
    - Filtering and converting important categorical features into numeric columns using dummy variable technique
    - Performing Feature Engineering
    - Creating final dataset for spliting it into testing and training dataset
6. Splitting the final dataset into independent and dependent features X and y respectively and performing feature importance for optimizing the dataset for regressor algorithms
7. Splitting datasets further into testing and training dataset with test_size of 0.3
8. Implementing Random Forest Regressor after doing hyperparameter tuning
    - Selecting best hyperparameters using random grid and Randomized Search CV
    - After that, creating base model to tune
    - Trying random search of parameters using 3 fold cross validation
    - Implementing the final model rf_random
9. Predicting the independent feature of X testing dataset by implementing rf_random model and comparing predictions to y_test dataset.
10. Calculating Mean Absolute Error(MAE), Mean Squared Error(MSE) and RMSE, and dumping the model into a pickle file using pickle.dump

Steps to follow after finishing the notebook:
1. Fetch the requirement.txt file from your environment to get the list of all libraries needed to install for this project using "$pip install -r requirements.txt" or refer to [this.](https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1)
2. You will have the random forest regression model.pkl file generated after running this notebook.
3. Create app.py file that contains all the code described in the notebook in a concise one python file.
4. Run app.py on your local by activating the project virtual environment and writing python app.py command
    - An IP address will be given which can be put in any brower where you can access the project on your local computer
5. Create very basic frontend .html file for deploying the project on heroku.
6. Create procfile for heroku after referring [this.](https://devcenter.heroku.com/articles/procfile)
7. Create a free account on [heroku](https://signup.heroku.com/)
    - Create a new app in your heroku account and upload the files after choosing relevant deployment method.
    

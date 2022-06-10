# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.


## To excute the script
python < scriptname.py >

## To run the code
- we have to create an environment from env.yml file which is attached in this repository.
- First we have to download that file and save it in working directory.
- "conda env create -f environment.yml" Type this command in the terminal.
- Now we can see newly created environment by typing the command "conda env list".
- Activate the environment -- "conda activate <env name>"
- Now execute the python script (python nonstandardcode.py).

# sparkify

### Table of Contents

1. [Instructions](#instructions)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Instructions <a name="instructions"></a>

In addition to the Anaconda distribution of Python (version 3), this project also requires the Spark library pyspark to be installed.

## Project Motivation<a name="motivation"></a>

For this project, I aimed to build a Machine Learning pipeline to identify users of a music streaming service who may "churn", i.e., cancel their service. I utilize a dataset provided by Uduacity showing user actions in the streaming service. I load & clean the data, build out features, train two different models (Logistic Regression and Random Forest) and tune parameters for each. Finally, I train and test the models.

## File Descriptions <a name="files"></a>

    - Sparkify.ipynb - Jupyther notebook containing Python code
    - mini_sparkify_event_data.zip - mini-dataset of user events

## Results<a name="results"></a>

The main findings of the code can be found in my blog  post available [here](https://carrie-kruppa.medium.com/if-i-can-do-ml-in-spark-so-can-you-e32a7b56275c). 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit goes to Udacity for the data.  Otherwise, there are no licensing restrictions on this code.

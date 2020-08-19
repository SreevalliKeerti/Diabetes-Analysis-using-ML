# Diabetes-Analysis-using-ML
A simple Azure ML Studio Project to predict the onset of diabetes.

## Scored probabilities of different ML algorithms
The dataset used is available in the Azure Machine Learning Studio named as **Pima Indian Diabetes Binary Classification dataset**.
| Algorithm                                     | Scored Probabilities | 
| --------------------------------------------- |:--------------------:|
| Two Class Decision Forest                     | 0.875                |  
| Two Class Logistic Regression                 | 0.598                |  
| Two Class Boosted Decision Tree               | 0.992                |  
| Two Class Locally Deep Support Vector Machine | 0.838                |
| Two Class Bayes Point Machine                 | 0.655                |
| Two Class Averaged Perceptron                 | 0.74                 |


The scored probabilites are based on the default sample data.

### To run on a Cloud-based Nookbook VM
Here are the following steps:

1. Clone this github repository
2. Create an Azure Machine Learning service workspace
3. Create a cloud notebook server in your workspace.
4. On the Notebooks page, click on the Upload files icon to upload the .ipynb file from the github repository
5. Execute the Jupyter notebook script by either clicking on the Run link on the run Notebook server page, or Click on the [...] link to open in Jupyter and run the script.

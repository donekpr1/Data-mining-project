# Data-mining-project
Deceptive/Fake product reviews detection 

The OSF(Open science framework) generated fake reviews dataset is a binary text classification dataset with labels computer generated(CG) assigned as 0 and Original Reviews(OR) assigned as 1 in this project.This dataset consists of 40k+ records and is a balanced data.

Prerequisite:
To execute this project code, Python 3 or above version is required.You can execute this using Jupyter Notebook standalone or use Colab.
Dataset should be imported and referred in the code before the execution starts.It can be downloaded from the git provided.
There is no separate test dataset as this dataset is considered for train and test split of 80% and 20%.

All the libraries to be imported is mentioned as part of the code.If you don't find any library in your server,please install it accordingly using pip command.

Models compared and evaluated:SVM classifier,Passive aggressive classifier,BiLSTM,BiGRU.
Prediction based embeddings compared:Word2vec,Glove
Regularization used:Drop out 

To run this project in colab,you can change the run time type to GPU to be in sync with the project report and for faster execution.If it is run on CPU run time type ,then it will take minimum 10 minutes for deep learning models to execute,depending on the network bandwidth.



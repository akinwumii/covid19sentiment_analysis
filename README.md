# covid19sentiment_analysis
Twitter Covid19 Sentiment Analysis using ANN and various classification model
-----------------------------------------------------
I trained a sentiment classsification model which uses Artificial Neural Network after using VADER to classify statements as Positive, Negative and Neutral * The dataset is publicly available on kaggle.

Installation And Running Steps:
1) Download Dataset Folder - Folder contains the Dataset . It contains 1 file:
     1)vaccination_tweets-1 - Twitter Covid-19 Vaccine Tweet publicly available on Kaggle
     2)Tweet_Sentiment(Covid19VaccineTweet).ipynb - Exploratory Data Analysis Jupyter notebook/Model Trainin and Testing
     3)mldata.csv- Processed Dataset used for Machine Learning Model.(The same can be downloaded in the last step after using VADER to classify statement)
     4)README.md 

2)Exploratory Data Analysis
     1) Open jupyter notebook or Google Colab and upload the contents of the Datasets folder and vaccination_tweets-1.ipynb file
     2) Once the file is uploaded and opened, then run each cell
     3) The comments and the inferences are mentioned in the file itself
     4) The last step is downloading the cleaned dataset from the jupyter notebook
     5) Move the downloaded dataset mldata.csv to the workspace (or you can use the mldata.csv file already present in the folder
     
3)Python Machine Learning Model 
     1) Open jupyter notebook or Google Colab
     2) Open the file mldata.ipynb from the repository 
     3) Create a folder called "logs" and "model" 
     4) The code reads the mldata.csv file and process it and built the model. 
     5) The model image will be downloaded to folder as ANN_SentimentM.png 
     6) The model were trained and the ouputs were displayed on the Run tab of Google colab or jupyter notebook. 
     7) The model was evaluated against the testing data 
     8) The epoch loss and accuracy were then be displayed on the screen which can be saved to your machine. 
     9) The current model was saved into the model folder created in step 3 and can be loaded from there and compare with original model.
     10) Prediction System : The script can read the user input and then predict the output based on the learnings.

4)Visualization 
     1) Open the Terminal tab of google colab 
     2) Type the below command there: tensorboard --logdir="<Fully qualified logs folder name used in step 3 of Python Machine Learning Model>" please mind the / ,if you are in windows machine. 
     3) The output of the above command will give a link for the tensorboard dashboard 
     4) Open the link in the web browser 
     5) It will show you the dashboard with tabs such as "SCALARS", "GRAPHS", "DISTRIBUTIONS", "HISTOGRAMS" and "TIME SERIES" 
     6) Explore the graphs

5)Other Classification Machine Learning models 
     1) Naive Bayes 
     2) Decision Tree 
     3) Logistic Regression 
     4) Random Forest

Thank You

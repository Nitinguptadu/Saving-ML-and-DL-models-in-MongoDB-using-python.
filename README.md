# Saving-ML-and-DL-models-in-MongoDB-using-python.
This repo is for self learning purpose 
 
Saving and loading model in the database is easy using python. After saving these models we can use them in the future whenever we want . I choose MongoDB because it is an open-source document database and leading NoSQL database.

There are three floder

In which 
First code is for tranning the model and saving in local mongodb server 
Second code is for loading saved model from Local mongodb server and use it for prediction 

In machine learning i have used IRIS dummy data for tranning xgb  model amd prediction 

In deep learning in have used Cifar 10 dummy data set for trainng cnn and prediction

In second deep learing dir i have used raw data for tranning and predction 

In all above code i have saved train model in mongodb and  load the model from mongodb for peredcition 

I have also uploded one notebook i which i have written some basic code of mongodb quiery for tabular data 

dir  = downloading data and trained model from mongodb server for prediction

In this project i have 

1) dowloaded traninng data from mongodb server for tranning 
2) Trained the model and save it to server 
3) downloded test data and trained model from mongodb server for prediction
4) uploaded the predicted data to mongodb
5) save data in cvs file with current date 
6) implemented mailer to send predicted .csv file 
7) for daily basis we use cron job 


for starting service of mongodb after install in linix

sudo service mongod start


for checking on which local port mongodb is running 

sudo service mongod status

* * * * *  conda activate base; python /home/nitin/Desktop/cro/cro.py >> test.out






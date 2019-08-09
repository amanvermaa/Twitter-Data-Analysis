# Twitter-Data-Analysis
Whether the user on twitter that I am going to follow would follow me back or not.
## Steps to follow :
1. Firstly you need to create a app by accessing the twitter developer website.
2. Secondly, Generate tokens and key values to access you twitter account followers and other operations on yours twitter data.
3. Thirdly, start with the Followingusers.ipynb.
4. Fourthly, then creating data.ipynb.
5. Fifthly, then you can use any model one without cross validation and one with cross validation implemented.

### A brief summary :
So, I am first accessing a user twitter profile, then looking into his/her friends who have the same interests as mine and following them.(*There is a limit of following 400 users per day by twitter*). So you need to do it for a week to get a better amount of data. Then I have already added followed people, now they are my following lets say. Now In the CreatingData.ipynb I have accessed my twitter followers data using the python-twitter API(*you need to install it using " pip install python-twitter "*) and by data i mean some features like when was their last tweet, how many followers they have etc.(*Python-twitter allows only few of the features to extract from users*). I have also reated features like if users have  "#followback" or these type of hashtags in their description. So you need to think which features to add by just having a few amount of features provided by the API. And in the end of the creatingData.ipynb you would be done with collecting data. Now the next step is to create a model. I am new into Machine Learning, thats why my model would appear to be immature but you can try on your own the modelling techniques.
Btw, I only a few of the people follow back and hence the accuracy would be low, I got 33% accuracy and was better than anyone who participated in the competition and luckily I got the 1st price. 

###THANK YOU

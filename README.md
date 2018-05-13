# Twitter_Sentiment_Analysis__iCampus__WS1718
The following program catches Tweets from Twitter and assigns an emotion based on the text using a Neural Network. <br><br>
For that, the program covers catching the Tweets, preprocessing the Tweets, training a Neural Network, scoring new Tweets based on the trained model and plotting the result.
<br><br>
This notebook is structured as following:
1. __Imports__ and __Global Variables__
2. Main functions to control the execution flow: <br>
   2.1. __Function__ to catch training tweets based on a given query. <br>
	 2.2. __Function__ to train the Neural Network model. <br>
	 2.3. __Function__ to score emotions of tweets and plot spider graphs. <br>
3. Classes  which contains the logic:<br>
	3. __Class__ to create the Database-API and manage the Database.<br>
	3. __Class__ to create the Twitter-API and to load Tweets based on a given search query.<br>
	3. __Class__ to preprocess a given Tweet.<br>
	3. __Class__ to train the Neural Network.<br>
	3. __Class__ to score a given text based on the trained Neural Network.<br>
	3. __Class__ to plot the emotions as a spider graph.<br>
4. Helper classes<br>
	4. Helper __Class__ to get informations about Tweets in database.<br>
	4. Helper __Class__ to delete a given Database.<br>

<br>
© Tobias Brähler | tobias.braehler@mni.thm.de

Installation:
-------------
Tweepy: tweepy is the python client for the official Twitter API.
Install it using following pip command:
    pip install tweepy
TextBlob: textblob is the python library for processing textual data.
Install it using following pip command:
    pip install textblob
Also, we need to install some NLTK corpora using following command:
(Corpora is nothing but a large and structured set of texts.)
    python -m textblob.download_corpora


Authentication:
---------------

In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:

Open this https://apps.twitter.com/ and click the button: ‘Create New App’
Fill the application details. You can leave the callback url field empty.
Once the app is created, you will be redirected to the app page.
Open the ‘Keys and Access Tokens’ tab.
Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.
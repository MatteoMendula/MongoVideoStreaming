# Mongo Video Streaming #
This is a small application to upload and view video on a mLab mongo databse.

First, you need to create an account on https://mlab.com/
Then, create a new databse and a user to connect it to your application

At this point edit in app.js the 19th line
const mongoURI = 'mongodb://username:psswd@ds255463.mlab.com:55463/bunjeeuploads';

replacing you credentials (username and password).

Now, simply excute 
## npm install ##
to satisfy all the dependencies
and then
## npm start ## 
to run the apllication

Enjoy!
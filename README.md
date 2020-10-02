# README

In order to submit your solution to Hennge, you'll need to do a post request with some necessary parameters including a token (Time-based One Time Password). 

In order to generate the token, replace the values in the `testTime` array with values of future dates (timestamp) when you'd like to send the 	`POST` request. 

Go to [epoch converter](https://www.epochconverter.com/) and get the timestamp of when you're going to submit the `POST` request and then generate the tokens by running the script and send the `POST` request with the respective token. 

So for example, suppose now it is 12:10 P.M.:

 - I'll get the timestamp of five minutes in the future from now, 12:15 P.M. Suppose it is `1601644756` 
 - I'll add that timestamp to the `testTime` array and run the script to generate the token for that time in the future.
 - When it is actually 12:15 P.M., I'll send the `POST` request with the token!

Enjoy; and fuck Hennge!


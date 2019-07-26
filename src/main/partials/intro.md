# Welcome to the M. Shanken Service Documentation

You will need a username and password in order to use this documentaion. If you do not have a username and password for this documentaion please email a request for credentials to apihelp@mshanken.com.

If you have your username and password go to the [Auth Service Page](http://docs.mshanken.io/auth) and follow these steps:
  1. Get an access_token via POST to the /oauth/token endpoint
    - grant_type = password
    - username (as indicated above)
    - password (as indicated above)
  2. Copy the "access_token" from the Response Body
  3. Get a session_token via POST to the /mshanken_auth endpoint
  3. Paste the access_token into the Authorization parameter field preceded by the token_type "Bearer"
    - i.e. - Bearer qwerty789jkl4321etcetc
  4. Enter the app_id and post the request to the service
  5. Copy "session_token" from the Response Body
  6. Go to the [Wine Service Page](http://docs.mshanken.io/wine)
  7. Click "AUTHORIZE" button
  6. Paste token into API Key field in Authorize pop up window
  9. Make requests against the service

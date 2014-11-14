# Using the Developer API

The Chew Developer API lets you access Chew platform resources, enabling the integration of episodes and other data into your mobile or web application. 

## Versions

API versions are numbered with the year and month of release and are locked at the end of the marked month. API versions older than most recent release may be removed or stop working. API users will be notified when versions of the API will be removed. 

## Authentication

Each request must be authenticated with an API key or testing API key - found on the Chew account page. 

## SSL

All requests must be sent through SSL to keep your API keys private. 

## Endpoint

The API endpoint for the 201405 API is app.chew.tv to allow compatability with the alpha versions of the API.

	app.chew.tv/api/{version}/{method}


## Example uses
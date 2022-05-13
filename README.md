# Assignment 2 - Web API.

Name: Michael Hart

## Features.

A bullet-point list of the ADDITIONAL features you have implemented in the API **THAT WERE NOT IN THE LABS** (or modifications to existing features)

 + Added various API endpoints from TMDB
 + Added Mongo database support
 + Setup a sign up and log in screen

## Setup requirements.

To run the movies-api
-open folder in terminal
-type "npm install"
-type "npm run dev"
-Server should be running on local host 8080

To run the react-app
-open folder in terminal
-type "npm install"
-type "npm start"
-Server should be running on local host 3000

npm audit fix may be required to fix commands


## API Configuration

Describe any configuration that needs to take place before running the API. For example, creating an `.env` file and what variables to put in it. Give an example of how this might be done.

REMEMBER: DON'T PUT YOUR OWN USERNAMES/PASSWORDS/AUTH KEYS IN THE README OR ON GITHUB, just placeholders as indicated below:

______________________
NODEENV=development
PORT=8080
HOST=
mongoDB=YourMongoURL
seedDb=true
secret=YourJWTSecret
______________________

If you wish to gain access to TMDB API you may need to input your API key within the .env, in order for the applications to retrieve movie data

## API Design
Give an overview of your web API design, perhaps similar to the following: 

- /api/recommendationsmovies | GET | Gets a list of recommended movies 
- /api/similarmovies | GET | Gets simlar movies
- /api/creditsmovies | GET | Get the credits for movies
- /api/trendingmovies | GET |  Gets the trending movies for the day

If you have your API design on an online platform or graphic, please link to it (e.g. [Swaggerhub](https://app.swaggerhub.com/)).

## Security and Authentication

Give details of authentication/security implemented on the API (e.g. passport/sessions). Indicate which routes are protected.

JSON Web Tokens used to authenticate user logins

## Integrating with React App

Describe how you integrated your React app with the API. List the views that use your Web API instead of the TMDB API. Describe any other updates to the React app from Assignment One.

React App serves as a visual representation of API data, which only appear as plain text through API app.

## Independent learning (if relevant)

Briefly explain any non-standard features developed for the app.
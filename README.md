# React-coding-challenge

The goal of this challenge is to give you an opportunity to show us what you know and how you would work in a real-life project with real-life behaviours.
To prove your self, follow the next steps.

# Introduction
Your local movie theater wants to make things a bit more interesting to attract the younger audience.

To do this, they came up with the idea of building a mobile application so users can see which movies are available to watch, leave reviews, build a community, etc.

They have commended you with the task of building such app. Since it's a first version to test if it's a good product or not, they have chosen a few features to build first and then see what happens.

Since they don't have a backend service, the first version of the application will be built using the public api https://developers.themoviedb.org/3

# Features
The key features of the application will be:

## 1. Welcome
The first screen should be a welcome:

![image](https://user-images.githubusercontent.com/79332087/163282720-5f4292e2-66cc-4190-9b66-84270d35d329.png)

    a) After click on "Accept", catch the username and store it globally. Using Redux.

## 2. Discover
After opening the app, users should be able to see a row list of movies suggested by the app sorted by popularity.
And a second row list to see the whole rest movie list.

![image](https://user-images.githubusercontent.com/79332087/163282701-45f2c2da-4aa3-4a25-a93f-60f4484ca812.png)

    a) API endpoint: `https://developers.themoviedb.org/3/discover/movie-discover`

## 3. Details Rating

![image](https://user-images.githubusercontent.com/79332087/163282779-84b61abe-c819-4da1-a21a-314f23938a60.png)


    a) API endpoint: https://developers.themoviedb.org/3/movies/get-movie-reviews

## Request example: 
    https://api.themoviedb.org/3/movie/550?api_key={api_key}

Suggestion: Use Postman for Request Testing.

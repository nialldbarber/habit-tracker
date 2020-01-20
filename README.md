# Habits tracking app

## Features 📝
* Add a habit you want to track
* They should just be daily habits
* Tap on the habit card to increment habit
* If the habit occurs more than once a day - it should not complete until number is reached
* Current streak should show 
* Create a profile - quick sign in with google or manually
* Dark/light mode optional
* Have a list of possible habits to track
* If not, then habits can be entered manually
* A colour can be chosen
  * This becomes then habit bar when incrementing
* Should have categories for habit
  * I.e. create a habit and then select the category it falls into
  * Every habit will have a category icon
* Eventually there should be a graph showing weekly/monthly/yearly progress

## Considerations 🤔
* Need to find a way to reset habits at a day 
  * Maybe, find the users location and reset the habit to 0 at 23:59:99
  * If the habit goal was reached, then add to the cumulative counter
* When you sign in - either the app asks for your location/timezone or you get it from google (if thats a thing)

## Tools 🛠️
### Front end
* Web - typescript react, context for state,  apollo client
* Mobile - react native
* Testing - jest for both, react testing library

### Backend
* MongoDB
* GraphQL
* ApolloServer

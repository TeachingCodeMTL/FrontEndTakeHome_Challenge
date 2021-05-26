# CoTeacher FrontEnd TakeHome Project
Take Home Challenge for CoTeacher FrontEnd position.

## Your Mission
Hey, your mission is to carve out 1-2 hours and create a Single Page React App (SPA) using the github users API defined below.

## Your Task
* Code has to be written in React.js with functional components using React Hooks (UseState, UseEffect).
* The home page of your app shows a list of all the available users to select. You decide how you want to order the users and how they are displayed.
* You should be able to filter through those users via an input on the same page, filter by their username for example.
* Should be able to click on a user in the list. When a user is clicked, the page shows details about the user.
* Once finished send your solution files to tiberiu.cristian.suciu@gmail.com

## Some Tips
* Don't overthink it! There's no need to over-engineer the application either, a simple solution shows that the problem is well understood and you have good control over the notions we are looking for
* As this is a frontend evaluation, the presentation of your solution is as imporant as the overall functionality, you need to make sure that the application works well and looks good at the same time.
* Make sure your code runs out of the box. (npm install && npm start should do the trick).
* Use any libraries you like. Pick something you are comfortable with.
* Some of the basic things that you're being evaluated at among other things would be.
  * Directory structure
  * Overall presentation
  * Presence of all demanded functionalities
  * Clean code
  * State management.

## Bonus Points
* Make usage of React context API
* Make usage of React Router
* Application looks decent on a mobile device
* Think outside of the box, if you think you can add something extra to further improve this application (maintainability, functionality, presentation), bring it on! We value greatly people who can bring creative and original solutions to the tasks at hand.

## Github Users api
All api requests are made to:

`https://api.github.com`

### Get Users
List all users

`https://api.github.com/users`

### Get User by username
Get user by username

`https://api.github.com/users/${username}`

# CoTeacher FrontEnd TakeHome Project
Take Home Challenge for CoTeacher FrontEnd position.

## Your Mission ❗
Hey, your mission is to carve out 1-2 hours and create a Single Page React App (SPA) using the github users API defined below.

## Your Task ✅
* Clone this challenge into a **private** repo.
* Code has to be written **from scratch** in React.js with functional components using React Hooks (UseState, UseEffect).
* The home page of your app shows a list of all available users to select.
* You should be able to filter through those users via an input on the same page, filter by their username for example.
* You should be able to click on a user in the list. When a user is clicked, you should be redirected to a page that shows further details about the user.
* Please do not use any libraries for styling (Material UI, Chakra UI, Bootstrap) As this is a front-end challenge, we'd like to see your styling skill as well!
* Once done, give reading rights to your repo to this account: `tiberiusuciu`

## Some Tips 👍
* Don't overthink it! There's no need to over-engineer the application either, a simple solution shows that the problem is well understood and you have good control over the notions we are looking for
* As this is a frontend evaluation, the presentation of your solution is as imporant as the overall functionality, you need to make sure that the application works well and looks good at the same time.
* Make sure your code runs out of the box. (npm install && npm start should do the trick).
* Some of the basic things that you're being evaluated at among other things would be.
  * Application runs without any errors via "npm start"
  * Directory structure
  * Overall presentation
  * All tasks are present
  * Clean code
  * State management.

## Bonus Points ✨
Here are some bonus things you could do that would make you stand out!
* Make usage of React context API
* Make usage of React Router
* Application looks decent on a mobile device
* Take it to the next level! Make use of NextJs and make this into an SSR app!
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

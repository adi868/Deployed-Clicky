# Deployed-Clicky

## Overview
Hello fellow Pokémon masters (or masters-in-training)! Welcome to the Pokémon Clicky-Game. This is a Pokémon-themed game that tests your ability and memory in tracking and choosing amongst a randomized array of images. Try as catch as many Pokémon as you can! But be careful. Don't click the same one more than once....(or you'll lose them all!)

### How To Play:
1. The application will render different images to the screen. Each image will listen for click events.
2. The application will track of the user's score. The user's score increments when clicking an image for the first time. The user's score will be reset to 0 if they click the same image more than once.
3. Every time an image is clicked, the images rendered to the page shuffles themselves in a random order.
4. Once the user's score is reset after an incorrect guess, the game restarts.
5. The maximum score is 15 in a row. Are you up for the challenge? 😬

### Installation:
1. Clone the complete repository from Github [here](https://github.com/adi868/Clicky-Game)
2. Run `npm init` in the terminal. This will install the dependencies in the `package.json`. When that's done, you can run the application in the command line with `npm start`. This will open the link to the application at http://localhost:3000.

#### Application Organization:
This application has its UI broken into components using React and follows a MVC paradigm. The components are as follows:
* Title
* NavBar
* Wrapper
* FriendCard
* Footer

#### About Using React:

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

#### Technology Used:
* React.js
* HTML5
* CSS3
* Javascript
* JSX
* ES6
* Bootstrap

#### Screenshot:
![Deployed Game](/images/clicky-game.png)

#### Deployed Link: 
[Pokémon Clicky-Game](https://adi868.github.io/Deployed-Clicky/)

---
© 2019 Adina Cianciotto adi868

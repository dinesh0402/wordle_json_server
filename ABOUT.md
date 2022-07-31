# Wordle Game using React.js and JSON Server 🔠
## A simple word-guessing game.

This project is a look alike of the original Wordle Game of the New York Times.This project was build using React.js and JSON server.
### Website Link :- https://dinesh0402.github.io/wordle_json_server/

### How the app works :-
* 👉 React is used to handle events like current guess, matching the guess, adding color to the guess based on its positions, etc.
* 👉 JSON server is used to serve up the words for the game.
* 👉 Using the keyboard, we type in the guesses and on pressing enter, the guess colors up accordingly.
* 👉 If you manage to complete the game within 6 guesses, you win and you get a pop-up message. On crossing 6 guesses, you loose and get a pop-up message.

### How to run the app on your system :-
**Local Environment**
* Go to the right directory and run "npm run start" to spin the React app locally.
* In another terminal, type in "json-server ./data/db.json --port 3001" because or app is already running in port 3000. So, start up the JSON-server in port 3001.

**Browser Environment**
* Click on the above link for the app ☝.
* If the app doesn't show up completely, open another tab and paste this link :- https://my-json-server.typicode.com/dinesh0402/wordle_json_server
* This should open up the app completely. 

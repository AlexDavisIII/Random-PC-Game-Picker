**To Demo this project, please use Live Server or a local server to run the application.**

This application does the following: 


-Calls from an external, third party API (RAWG API) to provide users with one game suggestion when visiting the page OR by clicking the "Different Game" button. 
    
-Steps through objects and arrays provided by the external API at random to select game image art and the name of the game the art refers to, but ONLY if the game found is available to play on the PC. This is by design as I want this to be an application built for people who play games primarily on the PC.

-Allows a user to continually press a button currently called "Different Game?" to cycle through the PC games found if they'd like to be recommended a different game than what they are provided with when first visiting the app.

-*REQUIRES NODE.JS uses EXPRESS.JS* Utilizes local API created by me through Express.js to store and display a list of quotes at random to be displayed whenever a user visits the page. The quotes are stored in an array of objects and are displayed in the footer above my "copyright".

-Check the console to watch it search through the different platforms before finding a PC game if you'd like! It also contains the RAWG API Object this demo is pulling from.

In order for this application to run properly:

- Install nodejs and npm. Make sure they are updated them if you already have them installed.
- Run "npm install express"
- Run "npm install cors"
- Go to the folder where you've cloned the repo
- Run "npm start" to allow the localAPI to work and avoid CORS request block (localhost:3000 is NOT the application)
- Run the demo in Live Server from Visual Studio Code
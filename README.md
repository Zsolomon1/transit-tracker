# transit-tracker
The client has two dependencies:

Google Maps JavaScript API to show the map on which the vehicles are placed.
Firebase Realtime Database to get details about the location of vehicles, along with upcoming schedule times.
To authorise access to the Google Maps JavaScript API, add an API key to index.html, using the process outlined in Google Maps Javascript API: Get a Key.

To configure access to Firebase Realtime Database, see Add Firebase to your JavaScript Project. You will need to add a Firebase API Key to the top of js/index.js.

To install library dependencies, use Node Package Manager.

$ npm install
To serve the front end using gulp, again use npm.

$ npm run main

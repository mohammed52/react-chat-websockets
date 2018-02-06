--
React Redux chat app using web sockets
--
Code for Chat app built with React, Redux, Redux-Saga, and web sockets. 
--
Tutorial:
https://youtu.be/x_fHXt9V3zQ
--
starts with create-react-app
--
first create plain html and css files to create the ui
--
redux to manage the state of the app
--
import and create store in index.js
--
create Reducers and initialize store, create actions, specify consts for action TYPES
--
when an action is dispatched, reducer updates the state of the store
--
arr1.concat(arr2) // join arr2 with arr1
--
use ST3 extension: sidebarenhancement
--
reduxSaga is a redux Middleware
--
npm install chance // random string generator
--
server is running and client is running in another terminal, both have to run for this to work
--
ws module does not work in the browser
--
browser clients must use native websocket object
--
npm install --save ws
--
to run backend server:
1. go to server directory
2. node app.js
--
to run front-end
npm run start
--
both backend server and front-end have to be running
--
front end is running on port 3000
--
backend server is running on 8989
--

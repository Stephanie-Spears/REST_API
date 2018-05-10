#Q&A RESTful API
~ This is a RESTful API which allows users to submit questions, answer questions, and vote on the efficacy of those question answers. The higher voted answers will move up in ranks and be displayed in ascending order. The lower voted questions will be mocked and looked upon with scorn. ~

## To run locally:
* `cd /REST_API` // move to API root directory
* `npm install` // install default modules specified in package.json
* `mongod` // run the mongoDB driver to host the Q&A database
* `cmd+t` // open new tab of parallel terminal (same directory)
* `node app.js` // (in new terminal tab) start the Express server using app.js as our entry point
* `cmd+t` // new terminal tab
* `cd /client_app` // change directories to client_app. client_app is simply a micro-server designed to highlight the use of the main application's API
* `npm install` // install client_app's dependencies 
* `nodemon` // run nodemeon mini-server to emulate client implementation of the main API
* visit `localhost:3001` in browser
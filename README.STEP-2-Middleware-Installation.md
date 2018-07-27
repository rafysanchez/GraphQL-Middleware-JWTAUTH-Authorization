<h2><u>Install NodeJS, Express and GraphQL Middleware</u></h2>
<h4>Let's get started:</h4>
<a href="https://nodejs.org/en/">Install nodejs</a><br />
$ node -v  // check node version, if this doesn't return node version, please fix and re-install (or update your %PATH%)<br />
$ npm -v // node versions comes with npm install, just check the versions<br />
npm install -g @angular/cli  // we will be using Angular for front-end development later<br />
$ ng -v // check angular cli version<br />

$ npm install -g nodemon // need this to autostart node server <br />
$ npm install -g cors // use this to secure Cross Origin Requests to Node and GraphQL server <br />

// create a new project, let's call it server<br />
$ mkdir server  or md server //create a new folder<br />
$ cd server <br /><br />

// copy gitclone entire directory<br />
// browse to folder where repository is cloned and<br />
$ npm install<br />
// make sure database is up and running<br />
// *** update env file as per you database settings **//<br />
$ nodemon start<br />

open an browser window on browse to<br />
 localhost:3000<br />
 localhost:3000/grahpql<br />

<h2>Setup CORS</h2>
<h2>Setup Database</h2>
<h2>Setup Authentication and Authorization</h2>

// detail steps <br /><br />
$ npm init // answer all the questions appearing in command prompts <br />
$ npm install express express-graphql graphql lodash cors mongoose express-jwt jwt-decode jsonwebtoken dotenv mysql2 sequelize--save <br />
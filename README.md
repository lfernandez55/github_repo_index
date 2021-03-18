# github_repo_index

Repo documenting:

I.
https://github.com/lfernandez55/express-hosting-react-barebones

Desc: Mixes ejs with react. 

Express serves "/" route with partial named layout.ejs.  Layout.ejs contains other partials and
<div id="main"></div> and <script src="javascripts/main.js"></script> which renders React component App.js <br /><br />

Express serves "/alt" route with partial named layout.ejs.  Layout.ejs contains other partials and
<div id="alt"></div> and <script src="javascripts/main.js"></script> which renders React component Alt.js 

GUI Desc:  Shows one page rendering layout.ejs, header.ejs, footer.ejs and React app in middle. One can swap
out different React components by clicking on the nav. 

To spin up: npm run server.  Visit localhost:8080.

Build notes:  Nodemon means changes to xpress automatically update.  Watch in webpack.config.js mean that react code also
automatically updates.  
 
DB: NO DB

Origin:  This was copied from a pc directory that's a clone of https://github.com/lfernandez55/web3430-activity5/tree/3d4ac1efc49867b971532ea9f5cf083f62610429

II.
https://github.com/lfernandez55/react_helloworld

Desc:  Mongo, Express, React CRUD App
A project bootstrapped with Create React App.  
A separate react frontend running on 3000.  Code is in root/src and root/build
A separate express backend  running on 8080.  Code is in root/server
Basic CRUD methods against a Mongo DB

GUI Desc: In header shows Mongo, Express, React CRUD App.  In nav, can click  on "Project List" which shows a list of projects. Can add a new project, delete a project and edit a project

To spin up: Open up two terminals.  In right terminal type npm run server.  In left terminal type npm start.  Interact with localhost:3000 which is the react app.  In the background it will make CRUD api calls to the server running on 8080.  There's a proxy set in package.json the api calls get automatically sent to 8080.  

DB: Mongo DB titled projectsminidb.  Contains only one Mongo table

Origin:  The readme contains a full log of how to build it.  Created from scratch with npx create-react-app my-app, added express,  


III. https://github.com/lfernandez55/web3430-activity5

Desc:  Movie app.  This app is what I develop slowly following all of Abdul Malek's videos.

Origin:  lfernandez55/https-github.com-lfernandez55-web3430-activity4 > lfernandez55/web3430-activity3

Note:  There are more activities after 5 but I got tired of creating new movie repos.  

IV. lfernandez55/web3430-assignment4

Desc: Projects app.  This is what I develop following Abdul Malek's assignments.

V. https://github.com/lfernandez55/yt-webpack2-basics

Desc:  Learning the basics of webpack



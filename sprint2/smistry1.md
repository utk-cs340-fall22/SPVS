# Sprint 2

(Shivam Mistry, smistry4, SPVS)

### What you planned to do
- create a backend interface in node.js
- connect frontend and backend interfaces
- figure out a solution to connect backend to the portscanner(c++ code)
- implement the above mentioned solution
- for future deployment, find a hosting service

### What you did not do
- connect node.js to the portscanner(partially implemented)

### What problems you encountered
In the previous sprint, frontend solutions were to be created in React. However, I changed it to vanilla javascript. The problems were following:
1. For a simple interface as ours, there is no need of ReactJS
2. Deployment of final build will be lightweight without ReactJS.   

Finding a solution to connect node.js and c++ file's was the biggest problem.

### Issues you worked on
 [#1 https://github.com/masonhyman-school/spvs/issues/23](https://github.com/masonhyman-school/spvs/issues/23) Create a server and connect to frontend
 [#2 https://github.com/masonhyman-school/spvs/issues/24](https://github.com/masonhyman-school/spvs/issues/24) Create a server and connect to frontend
 [#3 https://github.com/masonhyman-school/spvs/issues/25](https://github.com/masonhyman-school/spvs/issues/25) Create a server and connect to frontend

### Files you worked on
- spvs/spvs_server/app.js 
- spvs/spvs_server/index.html
- spvs/spvs_server/results.html

### What you accomplished
Firstly, I regrouped all the files into a fresh directory that will work from the server perspective. Then, I used npm and its services like express, body-parser to set up the server. This server loads the page and process post requests. The server also writes the user input to a file that will be used by the portscanner .cpp programs. This is part of paritally implemented part mentioned above. To make that fully functional, app.js file will run a child process which will be a cpp file and its stdout will be redirected to be displayed to the user. I also found a way to deploy the web app on Heroku after it is fully functional.


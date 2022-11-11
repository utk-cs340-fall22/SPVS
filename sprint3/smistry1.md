# Sprint 3

(Shivam Mistry, smistry4, SPVS)

### What you planned to do
- connect frontend with spvs tool using node
- implement file upload

### What you did not do
- implement file upload

### What problems you encountered
I was trying to run a child process from nodeJS which runs spvs tool, however due to a lot of dependencies of spvs(relative paths) made it difficult to debug.

### Issues you worked on
 [#1 https://github.com/masonhyman-school/spvs/issues/6](https://github.com/masonhyman-school/spvs/issues/6) Connect backend to spvs tool   
 [#2 https://github.com/masonhyman-school/spvs/issues/32](https://github.com/masonhyman-school/spvs/issues/32) Make backend and frontend interact with each other


### Files you worked on
- spvs/spvs_server/app.js 
- spvs/spvs_server/index.js

### What you accomplished
I completed connecting the nodeJS to run the spvs tool. Essentially, the code parses the user input, and determine what arguments to be passed to the child process to run the spvs(only host name, or host name and port number). Moreover, the nodeJS also handles replying the output back to the frontend.


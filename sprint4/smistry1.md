# Sprint 4

(Shivam Mistry, smistry4, SPVS)

### Files you worked on
- spvs/spvs_server/index.html
- spvs/spvs_server/public/javascript/index.js
- spvs/spvs_server/app.js

### What you accomplished
There are two main features I worked on: creating and sending a json reply to the frontend, and adding the file upload option.
I send all the error meassage as simple text, but all the successful executions are sent as json in a specified format. The format is as follows:
[{"Line_Number": "Line_Text"}]. Later the response is interpreted by the    frontend and displayed to the user.
The file upload is implemented by creating a new post route. The route downloads the file on server, and then runs the spvs tool by creating a child process and send a json reply and creating a file to download. For this part, I also implemented client side response handler, fetch API.
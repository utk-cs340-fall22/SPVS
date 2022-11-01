# Sprint 2

* Cody Blankenship
* cblank10
* SPVS

### What you planned to do
* Connect the frontend design to a local node js server.[#23](https://github.com/masonhyman-school/spvs/issues/23)
* POST data to backend using ajax[#24](https://github.com/masonhyman-school/spvs/issues/24)
* run simple scan with passed data and return results[#25](https://github.com/masonhyman-school/spvs/issues/25)

### What you did not do
* The big thing I was unable to complete was running the port scanner through the backend. Unfortunately my OS would not run the version of the program as it currently compiles. Over all this issue is minor to the completion of the backend, but it was an unfortunately large time sink for no showable code. We unfortunately may have to host from a linux machine, but that is what it is. 

### What problems you encountered
As I previously mentioned, running the scanners across operating systems was quite a pain, and an unfinished project. I was also unhappy with the tradtional POST. So I decided to redesign it with ajax and now it is much smoother and faster. Of course, ajax is slightly more complicated than traditional POST so I had to figure that out.

### Issues you worked on
* [#11](https://github.com/masonhyman-school/spvs/issues/11) NOTE: This one morhped from what was originally needed
* [#24](https://github.com/masonhyman-school/spvs/issues/24)
* [#23](https://github.com/masonhyman-school/spvs/issues/23)
* [#25](https://github.com/masonhyman-school/spvs/issues/25)

### Files you worked on
* [spvs/spvs_server/app.js](https://github.com/masonhyman-school/spvs/blob/main/spvs_server/app.js)
* [spvs/spvs_server/index.html](https://github.com/masonhyman-school/spvs/blob/main/spvs_server/index.html)
* [spvs/spvs_server/public/javascript/index.js](https://github.com/masonhyman-school/spvs/blob/main/spvs_server/public/javascript/index.js)
* [spvs/spvs_server/public/css/styles.css](https://github.com/masonhyman-school/spvs/blob/main/spvs_server/public/css/styles.css)

### What you accomplished
Despite the set backs, I was happy with what I got accomplished. Shivam and I worked to get the node js server up and running successfully, I then spent a good amount of time figuring out what protocal would work best to pass data to the server. After choosing POST, then redesigning to ajax I am very happy with the results. We reduced complexity and made the site faster. I also now understand how to run the scanner across different operating systems so I feel prepared now to bury that problem once and for all. We now have a fully functional site(front and backend). The only missing piece is actually executing the program. Despite the problem we had with it, it's rather elementry to implement.

# How to install a node.js module without using npm #

Download lib folder from the https://github.com/isaacs/multipart-js (including all the files inside it).

Put all those files next to your node application in the same folder.

On the top of your application file where you have included other modules like HTTP etc. ..append this >

var multipart = require("./multipart")

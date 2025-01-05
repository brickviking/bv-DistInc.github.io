# Distance-Incremental

;)

That was the original content in this file, and wasn't very informative about how to run this, figuring anyone who was cloning this would already know how to start it up. I came to this and scratched my head, and thought *if someone was coming to this for the very first time, how would they know how to get the game running for themselves?*

In essence, you clone this repository, and start up a web server (not a browser) with this directory as the webroot, and on a spare port, such as 8080 or 8081. I use althttpd, but any really lightweight web server will also do. You can then point your browser at the web address you've set up as such:  `http://localhost:8081/`. Once you've done that, you should be viewing the running application in the page. Have fun playing!

These instructions are set up specifically for Linux, but they may possibly work inside a WSL2 installation, or any modern BSD invocation that can run git, a modern web browser and the althttpd server from the sqlite project.

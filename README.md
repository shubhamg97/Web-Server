# Web Server

This web server written in Python sets up a local (& simple) web server on the host machine that allows someone to access a file on this (server) device. This particular web server is set up only to display a `helloworld.html` file since that is what is included in this repository but one should be able to access any other file, if placed within the directory of the server.

## Using the web server

1) Download this repository on your machine.
2) Run the web server (webserver.py) using Python 2.7 on your device. I shall refer to this device as the "server"
3) On your server, go to: http://www.whatsmyip.org/ and take a note of your IP. This shall be referred to as the "serverIP"
3) On a completely different device ("host" device), open your browser and search: `serverIP:6789/helloworld.html`
4) If you wish to test with another file/object (filename.extension), move that file into the same directory as the one which contains the web server. Now search: `serverIP:6789/filename.extension`

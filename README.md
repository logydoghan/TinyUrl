# TinyUrl

How to install this project:

A. Basic version (Without docker implementation)

Git clone. And then:

I. Run following command in your terminal:

npm install (if npm is not installed, install Node.js)
npm dependencies install (express, etc...)

II. Run local MongoDB and apply key in app/server.js (I use MLab)

Now you should be able to access the project by going to http://localhost:3000 in your browser.

----------------------------------------------------------------------------------------------------

B. Implementing with Docker

I. Download and install Docker. Check Docker version.
$ docker --version

II. Download Redis

III. Run local MongoDB and apply key in app/server.js (I use MLab)

III. Run following command in your terminal:

npm install (if npm is not installed, install Node.js)
npm dependencies install (express, etc...)
docker-compose up --build

Now you should be able to access the project by going to http://localhost:3000 in your browser.

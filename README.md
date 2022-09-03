# Getting started

## Project overview

AKitoChat is developed with Nodejs and socket.io, is responsive on all devices and 
supports Dark & Light modes. It has many features like one to one chat - audio - video
call, group chat, contacts, send files, send emojis, online users, authentication pages,
and much more. It is a real-time chat application with socket.io. 
Is used browser navigator for audio and video calls. Didn't used any third-party packages for audio and video calls.

Clone the repository

    git clone git@github.com:akitomen/Video-audio-chat-on-nodejs.-socket.io.git


## Installation guide

1. Create Mongo database on production or locally

    https://www.mongodb.com/basics/create-database
        
2. Install all node modules

        npm i or npm install
    
3. Set your secret key in config.json
4. Set all required configurations in config.env
5. Launch AKitoChat (The development server is accessible at http://localhost:2000)

        npm start or node app.js


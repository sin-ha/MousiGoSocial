# MousiGoSocial

This is a social media website that serves you messages from the people you follow
The following features are implemented
## live chat room (socket.io)
## interactive search
## csurf validation for security
apart from general things like login validations profile pictures etc.

WebApp

The server side of the app is a written using node js

To run the app locally install all dependencies as in package.json and use `node db` in the terminal

you have to configure your own .env file
it should have three fields

`
CONNECTIONSTRING= <key>`<br>`
PORT =<port no. || preset 3000>`<br>`
JWTSECRET = <jwt api key for login>`<br>`
SENDGRID = <sendgrid api key>`<br>`
`

The preset port is 3000 so you may visit localhost:3000

The app is deployed on Heroku.<a href = "https://letsgosocial.herokuapp.com/" target = _blank> <b><u>ClICK HERE</u></b></a>

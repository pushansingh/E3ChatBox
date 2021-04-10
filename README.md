# Intro
This project is made to show EEE or End to End encryption in the chatbox. This is not a real-world project rather a proof of concept.  

## Prerequisits 
To successfully deploy this package we need basic encryption knowledge and also some cloud computing knowledge, apart from that we would require some basic programming skills.
# End-to-End Encrypted Chat

[![Demo on Heroku]](https://aeschat.herokuapp.com/) 

This is a node chat application with end-to-end encryption. It uses [AES-256](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) and [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) encryption algorithms under the hood. You can either see the *demo* of the app using the button above or alternatively, you can *deploy* your own copy of the app using this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Getting Started

You'll need to install all the npm packages in order to start the app server:

```bash
cd end-to-end-enc-chat/
npm install
```

For running the app while in development:

```bash
npm run dev
```

For simply running the app in production mode:

```bash
npm start
```

**note**: Since this is a demo application I've added the `.env` file containing the environment vars on the root level, however you might not want to do that in production.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

# Sample Voice App for Jovo

Use this repository as a starting point to create cross-platform voice apps for Amazon Alexa and Google Home.

## About Jovo

[Jovo](https://www.jovo.tech "Jovo's website") is a framework for voice developers to create cross-platform apps.

You can find an early version of the documentation [here](https://docs.google.com/document/d/1SN_M-kS76Yz6B5pfMFrlYtM-ly2l10aZce3ULrZJztw/edit?usp=sharing "Jovo Docs"). We recommend using the [quickstart guide](https://docs.google.com/document/d/1g5xKevfDwaZ3FOvwLuA9iKiwOARGqPz_Yd7xlUQizOw/edit?usp=sharing "Jovo Framework Quickstart Guide") to get started in the best way.

## Get Started

### Download the template

Clone this repository to your coding environment:

```
$ git clone git@github.com:jovotech/jovo-sample-voice-app-nodejs.git
```

Use node package manager to install the dependencies ([jovo-framework](https://www.npmjs.com/package/jovo-framework "Jovo NPM Package")):

```
$ npm install
```

### Create apps at the developer consoles

Depending on for which platforms you want to develop a voice app (one is enough for prototyping), you need to take differen steps:
* For Amazon Alexa, [here's a tutorial](https://github.com/alexa/skill-sample-nodejs-fact/blob/master/README.md)
* For Google Home, [here's a tutorial](https://developers.google.com/actions/apiai/tutorials/getting-started)

### Set up index.js
You can run this template in two ways:
* Webhook (stick to the index.js)
* AWS Lambda (use the index_lambda.js and rename it to index.js)

For the prototyping stage, we recommend using our webhook-template and a tunneling service like [ngrok](https://ngrok.com/) for iterative local development and debugging.

## Jovo functions

You can find a reference to all Jovo functions [here](https://docs.google.com/document/d/1SN_M-kS76Yz6B5pfMFrlYtM-ly2l10aZce3ULrZJztw/edit?usp=sharing "Jovo Docs").

## We need your help
Jovo is a free, open source framework for voice developers. We're improving it every day and appreciate any feedback. How to support us? Just go ahead and build something cool with the framework and let us know at feedback@jovo.tech. Thanks!

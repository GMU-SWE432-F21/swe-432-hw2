# SWE-432 HW-2 Starter Application

## Submission Information

### Student Information

*Please fill in this information before submission*

**Student Name:** 
**Student G-Number:** 

### Documentation of your 7 Scenarios

*Here please describe your 7 scenarios complete with details about the endpoint and expected output. We provide one example below. If using route parameters, please provide an example API query*

* Retrieve a city from our Washington DC Database
  * API Endpoint: GET /city/:cityID
  * Example: GET /city/21
  * Expected Output: "Fairfax"

## Project Overview

This repo contains a barebones Node.js app using [Express 4](http://expressjs.com/). You will use this as the "base" version of your Microserivce application for HW Assignment #2. You will simply create a copy of this repo through GitHub classroom and then work in that repo. 

## Homework Assignment #2 Detailed Instructions

You can find the deatiled instructions for HW Assignment #2 on the [course webpage](https://cs.gmu.edu/~kpmoran/teaching/swe-432-f21/hw2). Please read these carefully before getting started.

## Running this Project Locally

Make sure you have [Node.js](http://nodejs.org/) and (optionally) the [Heroku CLI](https://cli.heroku.com/) installed. You only need the Heroku CLI installed if you plan to deploy the project from the CLI instead of the Heroku web interface. See the [HW Assignment #2 instructions](https://cs.gmu.edu/~kpmoran/teaching/swe-432-f21/hw2) for more details.

*Note the following commands assume a Unix-based enviornment. If you are on windows, you may need to use Windows Subsystem for Linux (https://docs.microsoft.com/en-us/windows/wsl/about).

```sh
$ git clone <this-repo> # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

After executing these commands, your app should now be running on [localhost:3000](http://localhost:3000/). You can visit this in your browser to see your 

## Deploying to Heroku

Check out [our instructions](https://cs.gmu.edu/~kpmoran/teaching/swe-432-f21/hw2) for deploying your application to Heroku. You can use the button below for quick access to your Heroku account.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Additional Resources

For more information about using Node.js on Heroku, see these Heroku Dev Center articles:

- [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)

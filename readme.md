# Assignment

## Objectives

By the end of this project you will:

- clone a Github project.
- install a npm package.
- debug a piece of code.

## Introduction

Our intern Dan is working on this killer Movie Quotes App that returns a random movie quote. Right now all it does is render a blank screen in the web browser. Fork the repository found here and help Dan fix it.  

## Specifications

The finished project:

- loads a new fact when you refresh the page.
- runs with no errors.
- has the readme updated with how to run this web server.

![working app](app.gif)

## Submission Requirements

Please include the url to your forked repository with the fixed webserver in your application to Inclusion's program.
[My repo url](https://github.com/jencwong/application_assignment)

The steps I took:
- Forked the repo
- Cloned the repo locally
- Discovered that the npm start was not working because the script was missing.  
- Added "start": "node index.js" to scripts in package.json
- Installed the npm package that is missing to run the random movie quotes npm i random-movie-quotes 
- Added this dependency to index.js: const quotes = require("random-movie-quotes");
- Saved the file and run it with npm start
- Opened the browswer to http://localhost:3000/
- Each time we refreshed the browser a new movie quote should show up
- Git add, commit and push the changes to my master branch

## References

- [Random Movie Quotes NPM Docummentation](https://www.npmjs.com/package/random-movie-quotes)
- [How to contribute to a github project](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/)

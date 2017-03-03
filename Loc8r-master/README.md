# Loc8r

following the mean book at http://www.manning.com/sholmes/

Original app located at http://loc8r.herokuapp.com/

My current snapshot is at http://draptik-getting-mean-loc8r.herokuapp.com/

## Setup

`npm install`

## Build

`nodemon app.js`

## Deployment to Heroku

`git push heroku master`

## Heroku and MongoLab issues

[http://www.manning-sandbox.com/thread.jspa?threadID=69116&tstart=0](http://www.manning-sandbox.com/thread.jspa?threadID=69116&tstart=0)

[https://devcenter.heroku.com/articles/config-vars#using-foreman-and-heroku-config](https://devcenter.heroku.com/articles/config-vars#using-foreman-and-heroku-config)

`heroku plugins:install git://github.com/ddollar/heroku-config.git`

`heroku config:pull --overwrite --interactive`

Creates `.env` file with `MONGOLAB_URI`.

Add `.env` file to `.gitignore`:

`echo ".env" >> .gitignore`

# Randomizer App

A random string generator app using localStorage.


## Technologies Used
* ReactJS - Powers the entire front-end.
* Webpack - Application Bundling


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the project:
- [Node](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)
- A [Heroku](https://www.heroku.com/) account with a project


### Installing

```
git clone git@github.com:manish-c/randomizer.git
cd randomizer
yarn install
```


#### Heroku configuration
Create an app in your [dashboard account](https://dashboard.heroku.com/) then follow instructions given by Heroku: 

```
heroku git:remote -a <your-heroku-app-name>
```

To be sure heroku remotes urls are ok:
```
git remote -v 
```


## Watching

```
yarn dev-server
```
Open [http://localhost:8080/](http://localhost:8080/) in your browser.


## Deployment

It uses Heroku so be sure you're logged in and connect your code to the heroku repo.

```
yarn deploy
```

It opens an url like this: https://your-heroku-app-name.herokuapp.com/

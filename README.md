# Boilerplate repo for NodeJS application with Babel, Nodemon, and Dotenv

## Pre-Reqs
NodeJS & NPM

## Clone Repo & Change Directory into Repo
Clone this repoistory locally and cd into the repo directory
`git clone git@github.com:DCarrollUSMC/nodejs-babel-boilerplate.git && cd nodejs-babel-boilerplate`

## Run npm install
`npm install`

## Dependencies
The following dependecies will be installed when running the above command

### Dev Dependencies
```
@babel/core^7.4.3
@babel/node^7.2.2
@babel/preset-env^7.4.3
nodemon^1.18.10
```

### Dependencies
`dotenv^7.0.0`

## Create .env file from template
`cp .env.template .env`

## Modify package.json
As necessary, make changes to package.json for package name, description, version, etc.

## Start Node
`npm start`

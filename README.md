# market-api

json-server api for a simple product listing app for Getir assignment.

Live API Server: https://the-market-api.herokuapp.com/

## How to run locally

- Pull the latest source code from the repository to your computer: `git clone https://github.com/AtakanErmis/market-api`
- Install dependencies: `npm install`
- Run the app: `npm start`
  - It will listen to port 8000 or `process.env.PORT` on your network.

## How to deploy to heroku

- Pull the latest source code from the repository to your computer: `git clone https://github.com/AtakanErmis/market-api`
- Install Heroku CLI: `npm install -g heroku`
- Login to Heroku: `heroku login`
- Create a new app: `heroku create`
  - You can use the git remote command to confirm that a remote named heroku has been set for your app: `git remote -v`
- Push the source code to heroku: `git push heroku master`

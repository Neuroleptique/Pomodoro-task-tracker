## Pomodoro tasks tracker
A simple task tracker is built using the MVC Architecture, we have also implemented "authorization" so folx can sign up, customize & personalize the app.

## How does this app work?
Add your task(s) and you can start working on them by using our pomodoro timer. Each pomodoro session consists of a 25 min of work session followed by a 5 min of break. When click 'Completed', this app will also track your total time taken on each task.

**Link to project:** https://pomodoro-tasks-tracker.herokuapp.com/

## How It's Made:
**Tech used:** HTML, CSS, JavaScript, Node, Express 

## Packages/Dependencies used 
bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

## Install all the dependencies or node packages used for development via Terminal
`npm install` 

## Things to add
- Create a `.env` file in the config folder and add the following as `key: value` 
  - PORT: 2121 (can be any port example: 3000) 
  - DB_STRING: `your database URI` 

## Lessons Learned:
DOM interaction with EJS and manipulating DATE objects in JS

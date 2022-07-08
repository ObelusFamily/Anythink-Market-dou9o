# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. After accepting the invitation to the Anything-Market-duo9o github repository, make sure you clone it locally on your machine - https://github.com/ObelusFamily/Anythink-Market-dou9o.git
2. Install docker on your local machine and check it is installed correctly - "docker -v" & "docker-compose -v" from a terminal
3. Navigate to the project root directory and run "docker-compose up" to build the relevant containers
4. Check the backend - http://localhost:3000/api/ping
5. Check the frontend - http://localhost:3001/register and register a new user

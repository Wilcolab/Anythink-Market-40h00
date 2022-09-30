# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Here are the steps to follow in order to set up your local environment:
(1) Start by installing Docker

(2) Verify your installation in Terminal with the following two codes:
docker -v
docker-compose -v

(3) Open the project repo directory and, with Terminal running in the project's root directory, use the following command to get the frontend and backend up and running:
docker-compose up

(4a) Verify your backend is up and running by visiting the following site: http://localhost:3000/api/ping

(4b) Verify your frontend is up and running by visiting the following site: http://localhost:3001/register
If the site loads, check it by setting up your own username and password

Congratulations, your local environment is now set up. Now get to work!

# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To run this project, you must have [Docker installed] (https://docs.docker.com/get-docker/) on your local machine. You can verify Docker is ready by running: `docker -v`  and `docker-compose -v`.

Once installed, run `docker-compose up` from the project root directory to load backend and frontend, if everything works fine you will be able to have a response pointing to http://localhost:3000/api/ping
Finally, you can create a new user at: http://localhost:3001/register
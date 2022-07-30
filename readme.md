# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/)'s latest version, if you don't already have it installed.
2. Verify docker is installed by running `docker -v` and `docker-compose -v` from the command line.
3. Run `docker-compose up` from **the project's root directory** to build and start Anythink's backend and frontend (This might take a few minutes).
4. Verify the Anythink's backend is up & running by going to http://localhost:3000/api/ping.
5. Verify that Anythink's frontend works and is connected to the backend by signing up here: http://localhost:3001/register.
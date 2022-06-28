# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repository  by running `git@github.com:ObelusFamily/Anythink-Market-tkopa.git`
2. Ensure that docker and docker-compose is installed in your local machine. Verify that docker is installed by running `docker -v` and `docker-compose -v`.
3. Navigate into the root of the repository and run `docker-compose up`
4. Confirm that the application is working by checking the responses to the following endpoints from your browser
  1. http://localhost:3000/api/ping
  2. http://localhost:3001/register

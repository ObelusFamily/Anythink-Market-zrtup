# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install Docker and verify successful installation by running <code>docker -v</code> and <code>docker-compose -v</code> in terminal.
Run <code>docker-compose up</code> from project root dir.
Go to <a href=http://localhost:3000/api/ping /> to make sure that backend's up and running.
Url for frontend is <a href=http://localhost:3001/register>.

Run all scripts on a container crated by <code>docker-compose up</code> and use <code>docker exec</code> to run commands on a container.

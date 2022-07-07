# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Run from the project root directory

> docker-compose up

to load Anythink's backend and frontend

If docker is working correctly, the backend should be running and able to connect to your local database.

After that, you can test this by pointing your browser to http://localhost:3000/api/ping

If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

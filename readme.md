# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

OK step one is to [install docker](https://docs.docker.com/get-docker/)

Then, run docker and check that it is running in your terminal with `docker -v` and `docker-compose -v`

Finally, reun `docker-compose up` from the project root directory to load the project backend and frontend.

Test that everything is up and running by going [HERE](http://localhost:3000/api/ping)

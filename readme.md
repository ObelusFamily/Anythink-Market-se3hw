
# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### #Docker
***[install Docker](https://docs.docker.com/get-docker/).***
***[install Docker Compose](https://docs.docker.com/compose/install/linux/).***

verify docker is ready by running the following commands
`$docker run hello-world`
`docker compose version`

Then, run
 `docker compose up` from the **project root directory** to load Anythink's backend and frontend.
 
 ### #Test
 
If Docker is working correctly, the backend should be running and able to connect to the local database.
**test this by pointing your browser** to http://localhost:3000/api/ping

to check the frontend and make sure it’s connected to the backend
make sure you are able to **create a new user** on http://localhost:3001/register

> make sure that you **run all scripts on one of the containers** created by `docker compose up`. Also, **you can use `docker exec` to run commands** on a running container.

**Now, your environment is ready! 😀**




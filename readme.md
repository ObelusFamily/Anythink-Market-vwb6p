# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Start by cloning this repo into your local machine using `git clone`

2. Then install [Docker](https://docs.docker.com/get-docker/) in your machine if you haven't already

3. To check if docker is already running on your machine run the following commands in your terminal: `docker -v` and `docker-compose -v`

4. Next run the command `docker-compose up` inside the project root directory

5. If everything is working correctly, the backend should now be running. To check head to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)

6. Now it's time to check the frontend by heading to [http://localhost:3001/register](http://localhost:3001/register)

7. Create a user to make sure the frontend is connected to the database

# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Clone the repository locally
    - `git clone `https://github.com/ObelusFamily/Anythink-Market-286lh`
    - `cd Anythink-Market-286lh`

2. Install [Docker](https://docs.docker.com/get-docker/) and validate
    - Validate Docker is running
        - `docker -v` and `docker-compose -v`
3. Create and start docker containers using docker-compose
    - docker-compose up

4. Validate access to web server once docker-compose is ready
    - In your browser, navigate to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
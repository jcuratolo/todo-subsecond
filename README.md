# TODO Subsecond

## Install Software

* [Node.js]()

## Create Database

If you have Postgres installed you can use that. Otherwise you can use SQlite.

### Postgres

    createdb todo-subsecond

### SQlite

    export DATABASE_URL=sqlite:./todo-subsecond.sqlite

## Install dependencies

    npm install

## Run tests

    npm test

Or:

    ./features/run/all # See other scrips in the same directory

## Run the server

    npm start
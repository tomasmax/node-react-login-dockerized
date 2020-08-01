# LOGIN SAMPLE APP

## - by [tomasmax](https://github.com/tomasmax)

- A fullstack web app. Back end: NodeJS Express with MySQL database + Front end: ReactJS + some unit testing + dockerized ready to deploy to CI/CD

---

## Prerequisites

- For Docker: Install and setup docker https://www.docker.com/products/docker-desktop
- For dev: Install NPM https://nodejs.org/en/download/

## Setup and run Docker

- Build and run docker
  `cd docker && docker-compose up --build`

- Go to `http://localhost:3000/`

## Running dev local

- Front end dev local: go to `client` directory then install and run the app

```sh
  `$ npm i && npm start`
```

- Back end dev local: go to `server` directory then install and run the app. `(NOTE! you need to config mySQL in your localhost intall it with brew or in a docker)`

```sh
  `$ npm i && npm start`
```

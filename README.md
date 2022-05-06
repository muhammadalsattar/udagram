# Udagram

Udagram is a starter project from Udacity. My mission is to deploy the app to AWS and automate the process with CircleCI CI/CD pipeline.

[![CircleCI](https://circleci.com/gh/circleci/udagram.svg?style=svg)](https://app.circleci.com/pipelines/github/muhammadalsattar/udagram?branch=main&filter=all)


### [Visit application](http://udagram-frontend2022.s3-website-us-east-1.amazonaws.com/home)

## CI/CD Pipeline

1. Clone this repo locally into the location of your choice.
2. Create a .env file in the udagram-api directory for your environment variables.
3. Required environment variables: /udagram-api/src/config/readme.md
4. Create a remote repository on github to push your code to.
5. Cofigure your CircleCI project to use the remote repository.
6. Push your code to the remote repository to trigger pipeline.

## Run the app locally

1. Clone the repo.
2. create a .env file in the udagram-api directory for your environment variables.
3. Required environment variables: /udagram-api/src/config/readme.md
4. Run `npm install:frontend` to install frontend dependencies.
5. Run `npm install:api` to install API dependencies.
6. Run `npm build:frontend` to build frontend.
7. Run `npm build:api` to build API.
8. Run `cd udagram-api && npm start` to run the API.
9. Run `cd udagram-frontend && npm start` to run the frontend.


### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `npm run test:frontend`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)

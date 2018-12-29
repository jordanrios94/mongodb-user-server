# mongodb-user-server

This repository is an example of the basics and complex scenarios of using mongodb in a production environment. Using TDD, one can achieve exploring everything that mongodb has to offer.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- node (8.11.1)
- nvm
- mongodb
- robo 3T

### Installing

After cloning repository, install node packages.

```
npm install;
```

Start mongo. The command be run anywhere on the system.

```
mongod;
```

The node environment is now ready to go.

## Running the tests

The test suite used is mocha. All the tests are covering the mongoose models created.

To run tests, execute the following in the terminal.

```
npm run test;
```

# FirstSpirit Connect for E-Commerce - Mock-o-Merce

This repository contains a reference project which generates and delivers a fake e-commerce REST API.

## Getting Started

- Clone the project using Git
  - `git clone https://github.com/e-Spirit/fcecom-mock-o-merce.git`
- Navigate to the directory called `mock-o-merce`
- Start the project using Docker
  - `./start.sh`

You can also install the dependencies in the `mock-o-merce` directory via npm if you don't want to use Docker.
Run `npm install` and then `npm start` to start the project.

### Prerequisites

- Docker and Docker Compose

## Generate new fake data

Use `npm run create:db` and follow the guided creation process

Strings were generated with [random-words](https://www.npmjs.com/package/random-words), where "_translations_" are only single letter masks.
[JSON Server](https://github.com/typicode/json-server) is used to deliver the data.

## Author

[e-Spirit AG](https://www.e-spirit.com)

## License

This project is licensed under the Apache License Version 2.0, January 2004 - see the [LICENSE](LICENSE) file for details

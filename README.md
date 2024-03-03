## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## License

Nest is [MIT licensed](LICENSE).
# Simple NestJS Messages App

This project is a simple application built with NestJS that allows users to create, retrieve, and list messages. It utilizes a basic file-based storage system to persist messages data.

## Features

- Create new messages
- Retrieve a single message by ID
- List all messages

## Technology Stack

- **Framework:** NestJS
- **Language:** TypeScript
- **Data Storage:** JSON file (`messages.json`)

### Prerequisites

- Node.js (Preferably the latest stable version)
- npm or yarn

## Usage

List Messages: Send a GET request to /messages to retrieve a list of all messages.

Create Message: Send a POST request to /messages with a JSON body containing the content field to create a new message.

Retrieve Message: Send a GET request to /messages/:id, replacing :id with the ID of the message you wish to retrieve.

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[//]: # ([circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456)
[//]: # ([circleci-url]: https://circleci.com/gh/nestjs/nest)
[//]: # ()
[//]: # (  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>)
[//]: # (    <p align="center">)
[//]: # (<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>)
[//]: # (<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>)
[//]: # (<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>)
[//]: # (<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>)
[//]: # (<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>)
[//]: # (<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>)
[//]: # (<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>)
[//]: # (<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>)
[//]: # (  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>)
[//]: # (    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>)
[//]: # (  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>)
[//]: # (</p>)
[//]: # (  <!--[![Backers on Open Collective]&#40;https://opencollective.com/nest/backers/badge.svg&#41;]&#40;https://opencollective.com/nest#backer&#41;)
[//]: # (  [![Sponsors on Open Collective]&#40;https://opencollective.com/nest/sponsors/badge.svg&#41;]&#40;https://opencollective.com/nest#sponsor&#41;-->)

# ILuvCoffee

This is the repository of the Official NestJS Fundamentals Course - ILuvCoffee

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

## Commands

Here is the list of all the commands used in the course:

### NestJS CLI

```bash
# Checking NodeJS version
node --version
# output > 21.5.0
````

```bash
# Installing NestJS CLI
npm i -g @nestjs/cli
```

```bash
# Checking NestJS CLI version
nest --version
# output > 10.2.1
```

```bash
# Displaying NestJS CLI help and shortcuts
nest --help
```

```bash
# Creating a new NestJS project
nest new
# input > iluvcoffee
# input > npm 
```

```bash
# Entering the project directory
cd iluvcoffee
```

```bash
# Running the project in production mode
npm run start
```

### Configuring Git

```bash
# Checking Git version
git --version
# output > 2.42.0
```

```bash
# Installing GitHub CLI package
brew install gh
```

```bash
# Checking GitHub CLI version
gh --version
# output > 2.42.1
```

```bash
# Authenticating GitHub CLI
gh auth login
# input > GitHub.com
# input > SSH
# input > your_path_to_ssh_key
# input > title_of_your_ssh_key
# input > Login with a web browser

# output > ✓ Logged in as your_github_username
```

```bash
# Creating a new GitHub repository
gh repo create
# input > Push an existing local repository to GitHub
# input > .
# input > iluvcoffee
# input > your_github_username
# input > your_description
# input > Private
# input > Y
# input > origin

# output: ✓ Added remote git@github.com:your_github_username/iluvcoffee.git
```

### Running the project in development mode

```bash
# Running the project in development mode - allow hot reload
npm run start:dev
```

## License

Nest is [MIT licensed](LICENSE).

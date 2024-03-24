# Home Library Service

## Prerequisites
- Docker Desktop [Download & Install Docker Desktop](https://docs.docker.com/engine/install/)
- Git - [Download & Install Git](https://git-scm.com/downloads).
- Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager.

## Downloading

***git clone https://github.com/SoloSoft2000/nodejs2024Q1-service***

## Build and Run application
#### **Before starting the application, please ensure that you do not have any other containers or applications running that may conflict with the current application (such as using the same ports, volumes, etc.)**

1 - create .env file (based on .env.example): <br>
***cp ./.env.example ./.env***

2 - start application via script docker:start: <br>
***npm run docker:start***

## Stop application

***npm run docker:stop***

## Testing

#### **Before local test install NPM modules**

***npm install***

### Local testing 

After application running open new terminal and enter:

To run all tests without authorization

***npm run test***

### Testing in container

***npm run docker:test***

## Security vulnerabilities

***npm run docker:scan***

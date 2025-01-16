# New_project

This repository contains the `New_project` which is a NodeJS application.

## Prerequisite Software:

### Mac:
* NodeJS (v14.16.0) : [Download here](https://nodejs.org/en/)
* Yarn : `npm install --global yarn`

### Windows:
* NodeJS (v14.16.0) : [Download here](https://nodejs.org/en/)
* Yarn : `npm install --global yarn`

## Database Tool:
* DynamoDB Local files

## Setup steps:
1. Clone the repository
2. Navigate to the project directory: `cd New_project`
3. Install all dependencies: `yarn install`
4. Update your local .env file with the required environment variables

## To start the application locally:
* Run the command `yarn start`

## Environment Set-Up
You can setup environment specific configurations by creating `.env.<ENVIRONMENT_NAME>.local` files.
- `.env.development.local` for development environment 

## Deployment
All code related to CI/CD pipeline is defined in the repository. Refer to those files for steps for deployment.

Note: Always ensure to update `.gitignore` file to ignore files containing sensitive data such as `.env` files or any other files containing keys/secrets.
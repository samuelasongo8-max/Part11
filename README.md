# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full Stack Open course

## Live Application

The Pokedex application is deployed on Render:

[https://part11-koj9.onrender.com](https://part11-koj9.onrender.com)

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build
## Pull Request Checks

GitHub Actions automatically runs the CI pipeline when a pull request is opened or updated against the `main` branch. The pipeline checks code quality, runs tests, builds the application, and runs end-to-end tests.
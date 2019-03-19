# Node.JS Express server template

A simple Express server template which comes with the following features:

* [Express](https://expressjs.com/) server
* Testing using [Mocha](https://mochajs.org/)
* Logging using [Winston](https://github.com/winstonjs/winston)
* Optional API protection using an API_KEY
* Configuration via environment variables
* `/liveness` endpoint for liveness/health check
* Code linting using [Eslint](https://eslint.org/)
* Code formatting using [Prettier](https://prettier.io/)
* NPM scripts:
  * `start` - Start the application
  * `start:dev` - Start a server watching for code changes
  * `test` - Run tests and linter
  * `test:dev` - Run tests and watch for code changes

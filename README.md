# LAB - 07

## Project Name

### Author: Student/Group Name

### Links and Resources
* [submission PR](https://github.com/jose-401-advanced-javascript/lab-07/pull/1)


#### Documentation
* [swagger](https://app.swaggerhub.com/apis/jaojeda/storefront-api/0.1)


#### Running the app

Lifecycle scripts included in copy-file:
  start
    json-server --watch data/db.json --routes routes.json --id _id
  test
    jest --verbose

available via `npm run-script`:
  test-watch
    jest --verbose --watchAll
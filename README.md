# k6 REST API test suite (Windows, Linux and Mac)

## Introduction
This suit is used to test the REST API services using K6.

## Prerequisites:
- Install K6 on the system used for testing

## Running tests

### Windows:
- Open command prompt and run > runtests dev (for development environment).
- Open command prompt and run > runtests qa (for qa environment).
- Open command prompt and run > runtests stg (for staged environment).
- Open command prompt and run > runtests prd (for production environment).

### Linux or Mac:
- Open command prompt and run > sh runtests.sh dev (for development environment).
- Open command prompt and run > sh runtests.sh qa (for qa environment).
- Open command prompt and run > sh runtests.sh stg (for staged environment).
- Open command prompt and run > sh runtests.sh prd (for production environment).

## Adding tests
- Add test files referring to the existing test scripts and deploy them in ./scripts/dev|qa|stg|prd folders based on the environments.
- Add json files referring to the existing json files and deploy them in ./scripts/dev|qa|stg|prd folders based on the environments.
- Add folder paths to files test.bat (for windows) or tests.sh (for linux)

## Please note:
- remove all the demo files once the application specific tests are added.

## Credits:
In githubworkflow folder, you can find different ways to setup the tools and infrastructure to execute the scripts

 ## References
* [k6 documentation](https://k6.io/docs/)
* [k6 GitHub](https://github.com/loadimpact/k6)
* [k6 examples](https://k6.io/docs/examples)


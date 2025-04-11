# k6 REST API Test Suite (Windows, Linux and Mac)

## Introduction
This suit is used to test the REST API services using K6.

## Prerequisites:
- Install K6 on the system used for testing.
- Install Git. 

## Installation:
- Create an empty folder.
- Open CMD/Terminal and navigate to this folder.
- Execute command "git clone https://github.com/monu301981/k6-restapi-test-suite".
- Get into this folder in CMD/terminal to execute further commands.

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

### Running individual scripts:
- Open command prompt and run > k6 run scripts/[dev|qa|stg|prd]/restapi-example.js

## Adding tests
- Add test files referring to the existing test scripts and deploy them in ./scripts/dev|qa|stg|prd folders based on the environments.
- Add json files referring to the existing json files and deploy them in ./scripts/dev|qa|stg|prd folders based on the environments.
- Add folder paths to files test.bat (for windows) or tests.sh (for linux)

## Please note:
- remove all the demo files once the application specific tests are added.

## Credits:
Quickpizza -> https://github.com/grafana/quickpizza.

 ## References
* [k6 documentation](https://k6.io/docs/)
* [k6 GitHub](https://github.com/loadimpact/k6)
* [k6 examples](https://k6.io/docs/examples)


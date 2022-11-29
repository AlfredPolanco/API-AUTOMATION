# API Automation


This project automates an API Collection from Postman using Newman

The framework contains the following 10 API calls for the website https://reqres.in/


1. List users
2. List <Resources>
3. Create user
4. Update user
4. Update user - PATCH
5. Delete user
6. Register user - SUCCESSFUL
7. Register user - UNSUCCESSFUL
8. Login - SUCCESSFUL
9. Login - UNSUCCESSFUL

# Tech Stack

* [Javascript.](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
* [Nodejs.](https://nodejs.org/en/about/)
* [Postman](https://www.postman.com/)
* [Newman](https://www.npmjs.com/package/newman)
* [Newman reporter](https://www.npmjs.com/package/newman-reporter-htmlextra)

# Before installing

* Node.js must be installed in order to run the project.
* Must run `npm install -g newman`and `npm install -g newman-reporter-htmlextra` on your machine.


# Installation

* Clone the repository from Github.
`git clone https://github.com/AlfredPolanco/API-AUTOMATION.git`

* Run the Postman collection with the following command
`npm run newman` an HTMML will be generated wit the test results

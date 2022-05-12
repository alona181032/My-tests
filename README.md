### Install
`npm install`
`npm install -g allure-commandline --save-dev`

# For using Allure reporter you need Java 8 or higher on your PC

### Run tests
all tests:

`npm test`

specific file:

`npx wdio wdio.conf.js --spec <path to file>`

for example:

`npx wdio wdio.conf.js --spec specs/1_registration.js`
`npx wdio wdio.conf.js --spec specs/2_registration_ddd.js`
`npx wdio wdio.conf.js --spec specs/3_login.js`

### Generate allure
`npm run report`

### Clean allure
`npm run clean`

### Run REPL with Chrome
`npm run repl`

### SITE
[https://anatoly-karpovich.github.io/HiqoMeetup/]

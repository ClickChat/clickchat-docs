# [![ClickChat](http://public.acactown.org/clickchat-logo-readme-files.png)](http://bootenv.com)-TODO

## Docs

- [x] `clickchat-docs` github repository
- [ ] A paragraph about **ClickChat**
- [ ] A short description about **ClickChat** Architecture
- [ ] A short description about github projects
- [ ] A short paragraph about SPA and `clickchat-webapp` project implementation
- [ ] A paragraph about Restful Services Architecture and `clickchat-api` project implementation
- [ ] How to run in the development environment
- [ ] How to deploy to production environment

### Nice2Have

- [x] Publish API documentation
- [x] Add useful README files
- [x] Add build status and coverage badges
- [x] Add Lincense to every project
- [x] Add label and milestones on github projects

## Some good practices

- [x] Track and report every task as github issue
- [x] Define and maintain consistent coding styles (editorconfig and jscs)
- [ ] Good inline code documentation (javadoc and jsdoc/ngdoc)
- [ ] 30% unit-test coverage (JUnit and Mocha)
- [x] Code Quality Tools (Jacoco and jshint)
- [x] Branch and merge strategy (github flow)
- [x] Integrate CI server build task on push and accepted pull-request
- [x] Use the best tools that opensource projects can provide
- [x] Read all sensitive information (ie: usernames and passwords) in execution time

## Front-end

- [x] `clickchat-webapp` github repository
- [x] Implement webapp as [SPA](http://en.wikipedia.org/wiki/Single-page_application)
- [x] Use [AngularJS](https://angularjs.org/)
- [x] Sing-in and Sign-up using [Google API](https://developers.google.com/api-client-library/javascript/start/start-js)
- [x] Use [Bootstrap](http://getbootstrap.com/) to responsive and mobile first approach

#### Login-Page

- [x] Sign-up flow using Google Account
- [x] Sign-in flow using Google Account

#### Chat-Page

- [x] Sorted users list
- [x] Load user info (ie: nickname and avatar) from Google Account
- [x] Show and send messages (up to 1000 characters)
- [x] Join and Exit chat room
- [x] Control user inactivity
- [x] Show user actions/events
- [x] After join chat room, load last 20 messages

### Nice2Have

- [x] Brand & concept
- [ ] Style guide
- [x] Wireframes/Mockups (Balsamiq mockups)
- [x] Use a web package manager (Bower)
- [x] Add Javascript task support (Grunt)
- [x] Use CSS preprocessor (Sass)
- [ ] Use library to intercepts HTTP requests for DEV mode (angular-mocks)
- [x] Add multilingual support
- [ ] Use cool Bootstrap theme
- [ ] Send emails triggered by user behavior (ie: After sign-up process)(customer.io)
- [x] Communication between chat user on browser and a server using WebSockets 
- [x] Add a front-end cache layer (cloudflare, cloudfront)
- [x] Static assets CDN distribution (cloudflare, cloudfront)

## Back-end

- [x] `clickchat-api` github repository
- [ ] Use [Play!](https://www.playframework.com/)
- [x] Add domain layer
- [x] Add data layer
- [x] Add service layer
- [x] REST-API

### Nice2Have

- [x] Add Loggin strategy (Logentries)
- [x] Add API documentation (Swagger)
- [x] Oauth 2 authentication (Tokens)
- [x] Add a NoSQL datasource (MongoDB)
- [ ] Use async queue messaging approach (RabbitMQ and Stomp, ZeroMQ)
- [x] Add cache layer (Redis)
- [x] Add Docker compose support

## CI/CD

- [x] Publish 1.0.0 version

### Nice2Have

- [ ] Build in one step
- [ ] Daily builds
- [x] Bug database
- [x] Docker based production deploy
- [ ] Add Staging and QA environment
- [ ] Add deploy protocol and deploy scripts
- [x] Configure CI Server (Jenkins, Travis)
- [x] Configure Coverage service (Coveralls)


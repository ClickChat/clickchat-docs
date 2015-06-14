# ClickChat - TODO

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

- [ ] Publish API documentation
- [ ] Add useful README files
- [ ] Add build status and coverage badges
- [ ] Add Lincense to every project
- [ ] Add label and milestones on github projects

## Some good practices

- [ ] Define and maintain consistent coding styles (editorconfig and jscs)
- [ ] Good inline code documentation (javadoc and jsdoc/ngdoc)
- [ ] 30% unit-test coverage (JUnit and Mocha)
- [ ] Code Quality Tools (Jacoco and jshint)
- [ ] Branch and merge strategy (github flow)
- [ ] Integrate CI server build task on push and accepted pull-request
- [ ] Use the best tools that opensource projects can provide
- [ ] Read all sensitive information (ie: usernames and passwords) in execution time

## Front-end

- [x] `clickchat-webapp` github repository
- [ ] Implement webapp as [SPA](http://en.wikipedia.org/wiki/Single-page_application)
- [ ] Use [AngularJS](https://angularjs.org/)
- [ ] Sing-in and Sign-up using [Google API](https://developers.google.com/api-client-library/javascript/start/start-js)
- [ ] Use [Bootstrap](http://getbootstrap.com/) to responsive and mobile first approach

#### Login-Page

- [ ] Sign-up flow using Google Account
- [ ] Sign-in flow using Google Account

#### Chat-Page

- [ ] Sorted users list
- [ ] Load user info (ie: nickname and avatar) from Google Account
- [ ] Show and send messages (up to 1000 characters)
- [ ] Join and Exit chat room
- [ ] Control user inactivity
- [ ] Show user actions/events

### Nice2Have

- [x] Brand & concept
- [ ] Style guide
- [ ] Wireframes/Mockups (Balsamiq mockups)
- [ ] Use a web package manager (Bower)
- [ ] Add Javascript task support (Grunt)
- [ ] Use CSS preprocessor (Sass)
- [ ] Use library to intercepts HTTP requests for DEV mode (angular-mocks)
- [ ] Add multilingual support
- [ ] Use cool Bootstrap theme
- [ ] Send emails triggered by user behavior (ie: After sign-up process)(customer.io)
- [ ] Communication between chat user on browser and a server using WebSockets 
- [ ] Add a front-end cache layer (cloudflare, cloudfront)
- [ ] Static assets CDN distribution (cloudflare, cloudfront)

## Back-end

- [x] `clickchat-api` github repository
- [ ] Use [Play!](https://www.playframework.com/)
- [ ] REST-API

### Nice2Have

- [ ] Add API documentation (Swagger)
- [ ] Oauth 2 authentication (Tokens)
- [ ] Add a NoSQL datasource (MongoDB)
- [ ] Use async queue messaging approach (RabbitMQ and Stomp, ZeroMQ)
- [ ] Add cache layer (Redis)

## CI/CD

- [ ] Publish 1.0.0 version

### Nice2Have

- [ ] Build in one step
- [ ] Daily builds
- [ ] Bug database
- [ ] Docker based production deploy
- [ ] Add Staging and QA environment
- [ ] Add deploy protocol and deploy scripts
- [ ] Configure CI Server (Jenkins, Travis)
- [ ] Configure Coverage service (Coveralls)


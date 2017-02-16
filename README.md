# QLICKER
Open Source Clicker - CISC498

[![CircleCI](https://circleci.com/gh/etenoch/qlicker/tree/master.svg?style=shield&circle-token=add100d7632954b295a5010c4d904e5b7801d8f5)](https://circleci.com/gh/etenoch/qlicker/tree/master)
[![codecov](https://codecov.io/gh/etenoch/qlicker/branch/master/graph/badge.svg?token=mtKx05fCA4)](https://codecov.io/gh/etenoch/qlicker)
[![GNU GPL v3](https://img.shields.io/badge/license-GNU%20GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

Qlicker is an application that will make it easier for professors to integrate student participation in classes. This involves a mobile-capable web application that can be used by students on their own devices as an alternative to the very common and hardware based iClicker system.

## Running Qlicker

Install meteor, install npm dependencies, then run.

```
curl https://install.meteor.com/ | sh 
npm install
meteor
```

To run tests locally
`npm run test:unit-watch` or `npm run test:app-watch`

## Development and Contributing

This application is built using the meteor web framework. Meteor is a node.js web framework that allows for tight integrator of server and client side javascript. It integrates with mongodb to provide seamless data model integration using pub-sub to automatically render changes on the client side. React was chosen over blaze and angular as the frontend user interface library. 

When developing, please adhere to meteor and react opinions as well as following the [Javascript Standard Code Style](http://standardjs.com). 

Changes will be merged into master after PR review.

## Deployment

Build and bundle using `meteor build`. Deploy node app and configure mongodb accordingly.

Application currently deployed at [qlicker.etdev.ca](http://qlicker.etdev.ca).




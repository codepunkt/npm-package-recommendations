> A list of personal npm package recommendations and alternatives

# Utility libraries
- [date-fns](https://date-fns.org/) - Date utility library
- [lodash](https://lodash.com/) - Generic utility library
- [ramda](https://ramdajs.com/) - Functional utility library
- [polished](https://polished.js.org/) - Styling utility library

# Frontend

## Data viz
- [d3](https://d3js.org/) - Data visualization library

## Animation
- [greensock](https://greensock.com/) - Site of tools for scripted, high-performance animations in all major browsers
- [anime](https://animejs.com/) - JavaScript animation engine

## Canvas
- [three.js](https://threejs.org/) - JavaScript 3D library

## React

### Boilerplates
- [create-react-app](https://facebook.github.io/create-react-app/) - Set up a react app with a single command
- [next.js](https://nextjs.org/) - Server-rendered react framework
- [gatsby](https://www.gatsbyjs.org/) - Site generator for React
- [react-static](https://github.com/nozzle/react-static) - A progressive static site generator for React
- [@rescripts/cli](https://github.com/harrysolovay/rescripts) - Allow custom build configurations for an app created with create-react-app

### Components
- [react-helmet](https://github.com/nfl/react-helmet) - Manage changes to the document head
- [downshift](https://github.com/downshift-js/downshift) - Primitive to build simple, flexible, enhanced input React components
- [nivo](https://nivo.rocks/) - Rich set of dataviz components, built on top of d3
- [react-media](https://github.com/ReactTraining/react-media) - CSS media queries for React
- [pigeon-maps](https://github.com/mariusandra/pigeon-maps) - ReactJS maps without external dependencies

### Routing
- [react-router](https://reacttraining.com/react-router/) - Most used routing library
- [navi](https://frontarm.com/navi/en/) - Routing library with focus on asynchronous routing & data fetching
- [@reach/router](https://reach.tech/router) - Routing library with focus on a11y

### CSS-in-JS
- [styled-components](https://www.styled-components.com/) - CSS-in-JS library for modular, component-based styling
- [emotion](https://emotion.sh/) - CSS-in-JS library for modular, component-based styling
- [linaria](https://github.com/callstack/linaria) - Zero runtime css in js library
- [rebass](https://rebassjs.org/) - React primitive UI components built with styled-system

### Forms
- [formik](https://jaredpalmer.com/formik/) - Most widely adopted form library
- [react-final-form](https://github.com/final-form/react-final-form) - Alternative form library
- [redux-form](https://redux-form.com/8.1.0/) - Form handling for redux

### State Management
- [redux](https://redux.js.org/) - Predictable, unidirectional data flow state management based on the flux pattern
- [mobx](https://mobx.js.org/) - Functional reactive programming state management
- [mobx-state-tree](https://github.com/mobxjs/mobx-state-tree) - Model driven state management
- [redux-observable](https://redux-observable.js.org/) - RxJS based middleware for redux

# Testing

- [jest](https://jestjs.io/) - JavaScript testing framework
- [cypress](https://www.cypress.io/) - JavaScript end to end testing framework, running in Chrome

# GraphQL

- [apollo](https://www.apollographql.com/docs) - GraphQL implementation for client & server
- [urql](https://github.com/FormidableLabs/urql) - Customizable GraphQL client for react
- [graphql-code-generator](https://graphql-code-generator.com/) - Generate code from your graphql schema

# XHR

- [axios](https://github.com/axios/axios) - Promise-based http client with a lot of options
- [cross-fetch](https://github.com/lquixada/cross-fetch) - Universal WHATWG Fetch API for Node, Browsers and React Native
- [make-fetch-happen](https://github.com/zkat/make-fetch-happen) - Nodejs fetch with additional features including HTTP Cache support, request pooling, proxies, retries etc
- [needle](https://github.com/tomas/needle) - Streamable HTTP client

# Node.js

## Misc
- [node-re2](https://github.com/uhop/node-re2) - fast, safe alternative to backtracking regular expression engines
- [dotenv](https://github.com/expressjs/morgan) - load environment variables from .env file
- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken#readme) - JSON web token implementation

## Web frameworks
- [express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework) - most used
- [hapi](https://hapijs.com/) - A rich framework for building applications and services
- [koa](https://github.com/koajs/koa) - Next generation web framework from the team behind express
- [helmet](https://helmetjs.github.io/) - Security toolbox for express web apps

## Database
- [mongoose](https://mongoosejs.com/) - Object modeling for MongoDB
- [mongoose-patch-history](https://github.com/codepunkt/mongoose-patch-history#readme) - Saves a history of JSON Patch operations for all documents belonging to a schema in an associated "patches" collection
- [sequelize](http://docs.sequelizejs.com/) - ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server
- [knex](https://knexjs.org/) - SQL query builder

## Logging
- [debug](https://github.com/visionmedia/debug) - Debugging utility modeled after Node.js core's debugging technique
- [morgan](https://github.com/expressjs/morgan) - HTTP request logger middleware
- [winston](https://github.com/winstonjs/winston) - Universal logging library, useable with multiple transports
- [pino](https://getpino.io/) - Low overhead logging with a focus on performance

# Tooling

## Commandline
- [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - Human readable terminal diffs
- [tldr](https://github.com/tldr-pages/tldr) - Simplified and community-driven man pages

## Project
> JavaScript project tooling

- [prettier](https://prettier.io/) - Code formatter
- [eslint](https://eslint.org/) - Code linter
- [husky](https://github.com/typicode/husky) - Define git hooks in package.json
- [commitlint](https://conventional-changelog.github.io/commitlint/) - Helps adhering to commit conventions by linting commit messages
- [lint-staged](https://github.com/okonet/lint-staged) - Runs linters, formatters or other commands on staged files
- [standard-version](https://github.com/conventional-changelog/standard-version) - Automatic semantic versioning and CHANGELOG generation
- [lerna](https://lernajs.io/) - A tool for managing JavaScript projects with multiple packages
- [size-limit](https://github.com/ai/size-limit) - Enables a build step that checks bundle sizes
- [plop](https://plopjs.com/) - Template-based code generator framework

## Github
> Applications that can be embedded into github workflows (automatically commenting on PRs etc)

- [bundlesize](https://github.com/siddharthkp/bundlesize) - Enables a build step that checks bundle sizes
- [dependabot](https://dependabot.com/) - Creates pull requests to keep dependencies secure and up-to-date
- [snyk](https://snyk.io/) -  Automates finding & fixing vulnerabilities in your dependencies
- [renovate](https://renovatebot.com/) - Automates dependency updates in software projects
- [greenkeeper](https://greenkeeper.io/) - Real-time monitoring and automatic updates for npm dependencies
- [codecov](https://codecov.io/) - Tools to group, merge and compare coverage reports

## Build
- [webpack](https://webpack.js.org/) - Highly configurable asset bundler
- [babel](https://babeljs.io/) - JavaScript compiler
- [rollup](https://rollupjs.org/guide/en) - Module bundler
- [sucrase](https://sucrase.io/) - Super fast babel alternative
- [swc](https://swc-project.github.io/) - Another fast babel alternative

### Webpack plugins
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - Visualizes size of webpack output files with an interactive treemap
- [nodemon-webpack-plugin](https://github.com/Izhaki/nodemon-webpack-plugin) - Uses nodemon to start and reload a server
- [webpack-license-plugin](https://github.com/codepunkt/webpack-license-plugin) - Helps you with the management of open source dependencies

### Babel plugins & presets
- [babel-preset-env](https://babeljs.io/docs/en/babel-preset-env) - Automatically target compile environments
- [babel-plugin-macros](https://www.npmjs.com/package/babel-plugin-macros) - Allows you to build compile-time libraries without having to add a babel plugin
- [babel-preset-typescript](https://babeljs.io/docs/en/babel-preset-typescript) - Preset used to compile typescript with babel

## Npm scripts
- [shx](https://github.com/shelljs/shx) - Unix-like, cross-platform commands
- [cross-env](https://github.com/kentcdodds/cross-env) - Set and use environment variables across platforms

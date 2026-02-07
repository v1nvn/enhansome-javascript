# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sorrycc/awesome-javascript/) ⭐ 34,890 | 🐛 30 | 📅 2026-01-05 with stars

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Component management](#component-management)
  * [Loaders](#loaders)
  * [Transpilers](#transpilers)
  * [Bundlers](#bundlers)
  * [Minimizers](#minimizers)
  * [Type Checkers](#type-checkers)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
  * [Templating Engines](#templating-engines)
  * [Game Engines](#game-engines)
  * [Articles/Posts](#articles-and-posts)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
    * [Spreadsheet](#spreadsheet)
  * [Editors](#editors)
  * [Documentation](#documentation)
  * Utilities
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structure](#data-structure)
    * [Date](#date)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#videoaudio)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Streaming](#streaming)
    * [Vision Detection](#vision-detection)
    * [Browser Detection](#browser-detection)
    * [Operating System](#operating-system)
    * [Benchmark](#benchmark)
    * [Machine Learning](#machine-learning)
    * [Web Worker](#web-worker)
  * UI
    * [Code Highlighting](#code-highlighting)
    * [Loading Status](#loading-status)
    * [Validation](#validation)
    * [Keyboard Wrappers](#keyboard-wrappers)
    * [Tours And Guides](#tours-and-guides)
    * [Notifications](#notifications)
    * [Sliders](#sliders)
    * [Range Sliders](#range-sliders)
    * [Form Widgets](#form-widgets)
    * [Tips](#tips)
    * [Modals and Popups](#modals-and-popups)
    * [Scroll](#scroll)
    * [Menu](#menu)
    * [Table/Grid](#tablegrid)
    * [Frameworks](#frameworks-1)
    * [Boilerplates](#boilerplates)
    * [Image](#image)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [Generators](#generators)
  * [Full Text Search](#full-text-search)
  * [SDK](#sdk)
  * [ORM](#orm)
  * [WebSockets](#websockets)
  * [Generative AI](#generative-ai)
  * [Misc](#misc)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

***

## Package Managers

*Host the JavaScript libraries and provide tools for fetching and packaging them.*

* [Bower](https://github.com/bower/bower) ⭐ 14,940 | 🐛 14 | 🌐 JavaScript | 📅 2024-10-13 - A package manager for the web.
* [component](https://github.com/componentjs/component) ⚠️ Archived - Client package management for building better web applications.
* [jspm](https://github.com/jspm/jspm-cli) ⭐ 3,848 | 🐛 69 | 🌐 TypeScript | 📅 2026-02-02 - Frictionless browser package management.
* [Duo](https://github.com/duojs/duo) ⚠️ Archived - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.
* [Ender](https://github.com/ender-js/Ender) ⚠️ Archived - The no-library library.
* [jam](https://github.com/caolan/jam) ⚠️ Archived - A package manager using a browser-focused and RequireJS compatible repository.
* [volo](https://github.com/volojs/volo) ⭐ 1,415 | 🐛 30 | 🌐 JavaScript | 📅 2022-11-25 - Create front end projects from templates, add dependencies, and automate the resulting projects.
* [spm](https://github.com/spmjs/spm) ⚠️ Archived - Brand new static package manager.
* [npm](https://www.npmjs.com/) - npm is the package manager for JavaScript.
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.
* [pnpm](https://pnpm.io/) - Fast, disk space efficient package manager.
* [bun](https://bun.sh/) - Bun is a fast JavaScript all-in-one toolkit.

## Component Management

* [Bit](https://github.com/teambit/bit) ⭐ 18,351 | 🐛 64 | 🌐 TypeScript | 📅 2026-02-07 - Create, find and reuse components (React, Angular, Node etc.) across applications.

## Loaders

*Module or loading system for JavaScript.*

* [browserify](https://github.com/substack/node-browserify) ⭐ 14,732 | 🐛 378 | 🌐 JavaScript | 📅 2024-12-21 - Browser-side require() the node.js way.
* [systemjs](https://github.com/systemjs/systemjs) ⭐ 13,098 | 🐛 77 | 🌐 JavaScript | 📅 2025-03-30 - AMD, CJS & ES6 spec-compliant module loader.
* [RequireJS](https://github.com/requirejs/requirejs) ⭐ 12,957 | 🐛 290 | 🌐 JavaScript | 📅 2025-11-30 - A file and module loader for JavaScript.
* [SeaJS](https://github.com/seajs/seajs) ⭐ 8,296 | 🐛 158 | 🌐 JavaScript | 📅 2023-07-03 - A Module Loader for the Web.
* [HeadJS](https://github.com/headjs/headjs) ⭐ 4,133 | 🐛 66 | 🌐 JavaScript | 📅 2023-04-20 - The only script in your HEAD.
* [script.js](https://github.com/ded/script.js) ⭐ 2,933 | 🐛 51 | 🌐 JavaScript | 📅 2020-04-14 - Asynchronous JavaScript loader and dependency manager.
* [lazyload](https://github.com/rgrove/lazyload/) ⚠️ Archived - Tiny, dependency-free async JavaScript and CSS loader.
* [ESL](https://github.com/ecomfe/esl) ⭐ 843 | 🐛 6 | 🌐 JavaScript | 📅 2023-03-30 - Module loader browser first, support lazy define and AMD.
* [LodJS](https://github.com/yanhaijing/lodjs) ⭐ 290 | 🐛 1 | 🌐 JavaScript | 📅 2022-11-07 - Module loader based on AMD.
* [modulejs](https://github.com/lrsjng/modulejs) ⭐ 128 | 🐛 3 | 🌐 JavaScript | 📅 2024-11-09 - Lightweight JavaScript module system.

## Transpilers

*Software that converts the modern JavaScript syntax into the older JavaScript syntax.*

* [SWC](https://swc.rs/) - Extensible Rust-based platform for compilation.

## Bundlers

* [webpack](https://github.com/webpack/webpack) ⭐ 65,947 | 🐛 204 | 🌐 JavaScript | 📅 2026-02-06 - Packs CommonJs/AMD modules for the browser.
* [Parcel](https://github.com/parcel-bundler/parcel) ⭐ 44,040 | 🐛 586 | 🌐 JavaScript | 📅 2026-02-04 - Blazing fast, zero configuration web application bundler.
* [Rollup](https://github.com/rollup/rollup) ⭐ 26,224 | 🐛 598 | 🌐 JavaScript | 📅 2026-02-06 - Next-generation ES6 module bundler.
* [Microbundle](https://github.com/developit/microbundle) ⭐ 8,152 | 🐛 99 | 🌐 JavaScript | 📅 2026-02-01 - Zero-configuration bundler for tiny modules.
* [Brunch](https://github.com/brunch/brunch) ⚠️ Archived - Fast front-end web app build tool with simple declarative config.
* [FuseBox](https://github.com/fuse-box/fuse-box) ⚠️ Archived - A bundler that does it right
* [Snowpack](https://www.snowpack.dev/) - A lightning-fast frontend build tool, designed for the modern web.
* [bundle](https://bundle.js.org) - A quick online npm package size checker.
* [Vite](https://vite.dev/) - Next Generation Frontend Tooling.

# Minimizers

* [Uglify](https://github.com/mishoo/UglifyJS) ⭐ 13,396 | 🐛 44 | 🌐 JavaScript | 📅 2024-11-22 - parser / mangler / compressor / beautifier toolkit
* [Terser](https://github.com/terser/terser) ⭐ 9,230 | 🐛 328 | 🌐 JavaScript | 📅 2026-02-02 - parser, mangler and compressor toolkit for ES6+

## Type Checkers

* [Zod](https://github.com/colinhacks/zod) ⭐ 41,748 | 🐛 246 | 🌐 TypeScript | 📅 2026-02-04 - TypeScript-first schema validation with built-in static type inference.
* [Yup](https://github.com/jquense/yup) ⭐ 23,687 | 🐛 239 | 🌐 TypeScript | 📅 2026-02-07 - JavaScript schema builder and validator.
* [TypL](https://github.com/getify/TypL) ⭐ 384 | 🐛 23 | 🌐 JavaScript | 📅 2021-11-11 - the JavaScript Type Linter with a bias on type inference.
* [Hindley Milner Definitions](https://github.com/xodio/hm-def) ⭐ 203 | 🐛 13 | 🌐 JavaScript | 📅 2022-12-03 - runtime type checking for JavaScript functions using Haskell-alike Hindley Milner type signatures.
* [TypeScript](https://www.typescriptlang.org/) - A typed superset of JavaScript that compiles to plain JavaScript.
* [Flow.js](https://flow.org/) - A static type checker for JavaScript from Facebook.
* [Hegel](https://hegel.js.org/) -  A static type checker for JavaScript with a bias on type inference an strong type system.

## Testing Frameworks

### Frameworks

* [jest](https://github.com/facebook/jest) ⭐ 45,280 | 🐛 237 | 🌐 TypeScript | 📅 2026-02-05 - Painless JavaScript Unit Testing.
* [mocha](https://github.com/mochajs/mocha) ⭐ 22,875 | 🐛 224 | 🌐 JavaScript | 📅 2026-02-06 - Simple, flexible, fun JavaScript test framework for node.js & the browser.
* [ava](https://github.com/avajs/ava) ⭐ 20,855 | 🐛 62 | 🌐 JavaScript | 📅 2025-11-05 - 🚀 Futuristic JavaScript test runner
* [jasmine](https://github.com/jasmine/jasmine) ⭐ 15,846 | 🐛 15 | 🌐 JavaScript | 📅 2026-01-19 - DOM-less simple JavaScript testing framework.
* [TestCafe](https://github.com/DevExpress/testcafe) ⭐ 9,902 | 🐛 19 | 🌐 JavaScript | 📅 2026-01-21 - Automated browser testing for the modern web development stack.
* [Protractor](https://github.com/angular/protractor) ⚠️ Archived - Protractor is an end-to-end test framework for AngularJS applications.
* [tape](https://github.com/substack/tape) ⭐ 5,803 | 🐛 41 | 🌐 JavaScript | 📅 2025-03-07 - Tap-producing test harness for node and browsers.
* [qunit](https://github.com/jquery/qunit) ⭐ 4,027 | 🐛 51 | 🌐 JavaScript | 📅 2026-02-05 - An easy-to-use JavaScript Unit Testing framework.
* [DalekJS](https://github.com/dalekjs/dalek) ⭐ 693 | 🐛 89 | 🌐 JavaScript | 📅 2020-04-03 - Automated cross browser functional testing with JavaScript
* [prova](https://github.com/azer/prova) ⭐ 329 | 🐛 27 | 🌐 JavaScript | 📅 2017-07-29 - Node & Browser test runner based on Tape and Browserify
* [Cypress](https://www.cypress.io/) - Complete end-to-end testing framework for anything that runs in a browser and beyond.
* [WebdriverI/O](https://webdriver.io/) - Next-gen browser and mobile automation test framework for Node.js
* [Suites](https://suites.dev) - A unit-testing framework for backends working with inversion of control and dependency injection

### Assertion

* [react testing library](https://github.com/kentcdodds/react-testing-library) ⭐ 19,529 | 🐛 74 | 🌐 JavaScript | 📅 2026-01-19 - Simple and complete React DOM testing utilities that encourage good testing practices.
* [Supertest](https://github.com/visionmedia/supertest) ⭐ 14,300 | 🐛 178 | 🌐 JavaScript | 📅 2026-01-21 - A popular HTTP assertion library for testing REST APIs, often used with other testing frameworks like Mocha or Jest
* [Sinon.JS](https://github.com/sinonjs/sinon) ⭐ 9,764 | 🐛 52 | 🌐 JavaScript | 📅 2025-12-19 - Test spies, stubs, and mocks for JavaScript.
* [chai](https://github.com/chaijs/chai) ⭐ 8,267 | 🐛 91 | 🌐 JavaScript | 📅 2026-02-07 - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [proxyquire](https://github.com/thlorenz/proxyquire) ⭐ 2,746 | 🐛 12 | 🌐 JavaScript | 📅 2025-08-13 - Stub nodejs's require.
* [expect.js](https://github.com/Automattic/expect.js) ⭐ 2,098 | 🐛 89 | 🌐 JavaScript | 📅 2023-01-14 - Minimalistic BDD-style assertions for Node.JS and the browser.
* [Pocket Mocker](https://github.com/tianchangNorth/pocket-mocker) ⭐ 543 | 🐛 8 | 🌐 TypeScript | 📅 2026-01-16 - In-browser visual network mocking tool, supports fetch/XHR interception.
* [Enzyme](https://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.

### Coverage

* [istanbul](https://github.com/gotwarlost/istanbul) ⚠️ Archived - Yet another JS code coverage tool.
* [blanket](https://github.com/alex-seville/blanket) ⭐ 1,396 | 🐛 154 | 🌐 JavaScript | 📅 2022-12-06 - A simple code coverage library for JavaScript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover](https://github.com/tntim96/JSCover) ⭐ 402 | 🐛 5 | 🌐 Java | 📅 2026-02-01 - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner

* [puppeteer](https://github.com/GoogleChrome/puppeteer) ⭐ 93,510 | 🐛 283 | 🌐 TypeScript | 📅 2026-02-06 - Headless Chrome Node.js API by official Google Chrome team.
* [Playwright](https://github.com/microsoft/playwright) ⭐ 82,260 | 🐛 595 | 🌐 TypeScript | 📅 2026-02-07 - Node.js library to automate Chromium, Firefox and WebKit with a single API.
* [phantomjs](https://github.com/ariya/phantomjs) ⚠️ Archived - Scriptable Headless WebKit.
* [karma](https://github.com/karma-runner/karma) ⭐ 11,972 | 🐛 389 | 🌐 JavaScript | 📅 2026-01-21 - Spectacular Test Runner for JavaScript.
* [nightwatch](https://github.com/nightwatchjs/nightwatch) ⭐ 11,949 | 🐛 338 | 🌐 JavaScript | 📅 2026-01-21 - UI automated testing framework based on node.js and selenium webdriver.
* [webdriverio](https://github.com/webdriverio/webdriverio) ⭐ 9,718 | 🐛 268 | 🌐 TypeScript | 📅 2026-02-06 - Next-gen WebDriver test automation framework for Node.js.
* [casperjs](https://github.com/casperjs/casperjs) ⚠️ Archived - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie](https://github.com/assaf/zombie) ⚠️ Archived - Insanely fast, full-stack, headless browser testing using node.js.
* [intern](https://github.com/theintern/intern) ⭐ 4,351 | 🐛 140 | 🌐 TypeScript | 📅 2023-03-14 - A next-generation code testing stack for JavaScript.
* [taiko](https://github.com/getgauge/taiko) ⭐ 3,661 | 🐛 62 | 🌐 JavaScript | 📅 2026-01-28 - A Node.js library with a simple API to automate Chromium based browsers.
* [slimerjs](https://github.com/laurentj/slimerjs) ⭐ 2,995 | 🐛 164 | 🌐 JavaScript | 📅 2023-03-09 - A PhantomJS-like tool running Gecko.
* [totoro](https://github.com/totorojs/totoro) ⭐ 564 | 🐛 4 | 🌐 JavaScript | 📅 2022-02-12 - A simple and stable cross-browser testing tool.

## QA Tools

* [prettier](https://github.com/prettier/prettier) ⭐ 51,522 | 🐛 1,424 | 🌐 JavaScript | 📅 2026-02-06 - Prettier is an opinionated code formatter.
* [husky](https://github.com/typicode/husky) ⭐ 34,732 | 🐛 102 | 🌐 JavaScript | 📅 2026-02-05 - Prevents bad git commit, git push and more.
* [JavaScript Standard Style](https://github.com/feross/standard) ⭐ 29,434 | 🐛 128 | 🌐 JavaScript | 📅 2025-07-11 - Opinionated, no-configuration style guide, style checker, and formatter
* [ESLint](https://github.com/eslint/eslint) ⭐ 26,864 | 🐛 89 | 🌐 JavaScript | 📅 2026-02-07 - A fully pluggable tool for identifying and reporting on patterns in JavaScript.
* [JSHint](https://github.com/jshint/jshint/) ⭐ 9,067 | 🐛 461 | 🌐 JavaScript | 📅 2025-02-13 - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [JS-Beautifier](https://github.com/beautify-web/js-beautify) ⭐ 8,935 | 🐛 432 | 🌐 JavaScript | 📅 2026-01-27 - Npm cli and library to format JS code.
* [jscs](https://github.com/jscs-dev/node-jscs) ⚠️ Archived - JavaScript Code Style checker.
* [JSLint](https://github.com/douglascrockford/JSLint) ⭐ 3,657 | 🐛 5 | 🌐 JavaScript | 📅 2026-01-01 - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language.
* [jsinspect](https://github.com/danielstjules/jsinspect) ⭐ 3,585 | 🐛 25 | 🌐 JavaScript | 📅 2024-03-20 - Detect copy-pasted and structurally similar code.
* [jsfmt](https://github.com/rdio/jsfmt) ⭐ 1,685 | 🐛 35 | 🌐 JavaScript | 📅 2020-04-04 - For formatting, searching, and rewriting JavaScript.
* [buddy.js](https://github.com/danielstjules/buddy.js) ⭐ 889 | 🐛 4 | 🌐 JavaScript | 📅 2019-11-16 - Magic number detection for JavaScript.
* [Pre-evaluate code at buildtime](https://github.com/kentcdodds/preval.macro) ⭐ 127 | 🐛 2 | 🌐 JavaScript | 📅 2021-01-25 - Pre-evaluate your front end javascript code at build-time

## MVC Frameworks and Libraries

* [vue](https://github.com/vuejs/vue) ⭐ 209,902 | 🐛 622 | 🌐 TypeScript | 📅 2024-10-10 - Intuitive, fast & composable MVVM for building interactive interfaces.
* [react-native](https://github.com/facebook/react-native) ⭐ 125,310 | 🐛 1,176 | 🌐 C++ | 📅 2026-02-06 - A framework for building native apps with React.
* [angular](https://github.com/angular/angular) ⭐ 99,812 | 🐛 1,136 | 🌐 TypeScript | 📅 2026-02-06 - Angular is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.
* [svelte](https://github.com/sveltejs/svelte) ⭐ 85,704 | 🐛 968 | 🌐 JavaScript | 📅 2026-02-06 - Svelte is a new way to build web applications. It's a compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.
* [angular.js](https://github.com/angular/angular.js) ⚠️ Archived - HTML enhanced for web apps. (deprecated)
* [meteor](https://github.com/meteor/meteor) ⭐ 44,773 | 🐛 326 | 🌐 JavaScript | 📅 2026-02-06 - An ultra-simple, database-everywhere, data-on-the-wire, pure-javascript web framework.
* [preact](https://github.com/developit/preact) ⭐ 38,365 | 🐛 154 | 🌐 JavaScript | 📅 2026-02-05 - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.
* [Alpine.js](https://github.com/alpinejs/alpine) ⭐ 31,122 | 🐛 44 | 🌐 HTML | 📅 2026-02-04 - offers you the reactive and declarative nature of big frameworks like Vue or React at a much lower cost.
* [backbone](https://github.com/jashkenas/backbone) ⭐ 28,117 | 🐛 62 | 🌐 JavaScript | 📅 2025-04-01 - Give your JS App some Backbone with Models, Views, Collections, and Events.
* [GrapesJS](https://github.com/artf/grapesjs) ⭐ 25,478 | 🐛 52 | 🌐 TypeScript | 📅 2026-02-07 - Free and Open source Web Builder Framework. Next generation tool for building templates without coding.
* [nativescript](https://github.com/NativeScript/NativeScript) ⭐ 25,432 | 🐛 951 | 🌐 TypeScript | 📅 2026-02-03 - Build truly native cross-platform iOS and Android apps with JavaScript.
* [ember.js](https://github.com/emberjs/ember.js) ⭐ 22,580 | 🐛 425 | 🌐 TypeScript | 📅 2026-02-06 - A JavaScript framework for creating ambitious web applications.
* [hyperapp](https://github.com/hyperapp/hyperapp) ⭐ 19,218 | 🐛 14 | 🌐 JavaScript | 📅 2025-03-20 - 1kb JavaScript library for building frontend applications.
* [Adonis](https://github.com/adonisjs/core) ⭐ 18,637 | 🐛 3 | 🌐 TypeScript | 📅 2026-02-06 - The Node.js Framework highly focused on developer ergonomics, stability and confidence.
* [Million](https://github.com/aidenybai/million) ⭐ 17,507 | 🐛 125 | 🌐 TypeScript | 📅 2025-12-11 - <1kb compiler-focused virtual DOM. It's fast!
* [inferno](https://github.com/infernojs/inferno) ⭐ 16,412 | 🐛 39 | 🌐 JavaScript | 📅 2026-01-30 - 🔥 An extremely fast, React-like JavaScript library for building modern user interfaces.
* [feathers](https://github.com/feathersjs/feathers) ⭐ 15,248 | 🐛 145 | 🌐 TypeScript | 📅 2026-02-03 - A minimalist real-time JavaScript framework for tomorrow's apps.
* [riot](https://github.com/riot/riot) ⭐ 14,908 | 🐛 4 | 🌐 JavaScript | 📅 2025-11-21 - React-like library, but with very small size.
* [mithril.js](https://github.com/lhorie/mithril.js) ⭐ 14,670 | 🐛 27 | 🌐 JavaScript | 📅 2026-02-03 - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).
* [Blockly](https://github.com/google/blockly) ⭐ 13,303 | 🐛 396 | 🌐 TypeScript | 📅 2026-02-06 - A library that adds a visual code editor to web and mobile apps by Google.
* [Rete.js](https://github.com/retejs/rete) ⭐ 11,844 | 🐛 6 | 🌐 TypeScript | 📅 2025-11-21 - A modular framework for visual programming allows to create node based editor in browser.
* [knockout](https://github.com/knockout/knockout) ⭐ 10,545 | 🐛 375 | 🌐 JavaScript | 📅 2024-06-27 - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* [litegraph.js](https://github.com/jagenjo/litegraph.js) ⭐ 7,858 | 🐛 150 | 🌐 JavaScript | 📅 2024-08-01 - A graph node engine and editor similar to PD or UDK Blueprints, comes with its own editor in HTML5 Canvas2D.
* [marionette](https://github.com/marionettejs/backbone.marionette) ⭐ 7,046 | 🐛 36 | 🌐 JavaScript | 📅 2026-02-05 - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* [Drawflow](https://github.com/jerosoler/Drawflow) ⭐ 5,954 | 🐛 272 | 🌐 JavaScript | 📅 2024-10-19 - This allow you to create data flows easily and quickly.
* [ractive](https://github.com/ractivejs/ractive) ⭐ 5,929 | 🐛 68 | 🌐 JavaScript | 📅 2024-05-22 - Next-generation DOM manipulation.
* [derby](https://github.com/derbyjs/derby) ⭐ 4,717 | 🐛 23 | 🌐 TypeScript | 📅 2024-10-24 - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
  * [derby-awesome](https://github.com/russll/awesome-derby) ⭐ 13 | 🐛 0 | 📅 2014-08-26 - A collection of awesome derby components
* [spine](https://github.com/spine/spine) ⭐ 3,678 | 🐛 36 | 🌐 JavaScript | 📅 2020-04-04 - Lightweight MVC library for building JavaScript applications.
* [rivets](https://github.com/mikeric/rivets) ⭐ 3,229 | 🐛 142 | 🌐 JavaScript | 📅 2020-04-06 - Lightweight and powerful data binding + templating solution.
* [Remult](https://github.com/remult/remult) ⭐ 3,199 | 🐛 90 | 🌐 TypeScript | 📅 2026-02-03 - A CRUD framework for full-stack TypeScript.
* [way.js](https://github.com/gwendall/way.js) ⭐ 2,871 | 🐛 52 | 🌐 JavaScript | 📅 2024-06-27 - Simple, lightweight, persistent two-way databinding.
* [chaplin](https://github.com/chaplinjs/chaplin) ⚠️ Archived - An architecture for JavaScript applications using the Backbone.js library.
* [jsblocks](https://github.com/astoilkov/jsblocks) ⭐ 2,758 | 🐛 14 | 🌐 JavaScript | 📅 2025-01-13 - jsblocks is better MV-ish framework.
* [canjs](https://github.com/canjs/canjs) ⭐ 1,913 | 🐛 312 | 🌐 JavaScript | 📅 2023-08-03 - Can do JS, better, faster, easier.
* [ripple](https://github.com/ripplejs/ripple) ⭐ 1,342 | 🐛 12 | 🌐 JavaScript | 📅 2014-07-30 - A tiny foundation for building reactive views.
* [thorax](https://github.com/walmartlabs/thorax) ⚠️ Archived - Strengthening your Backbone.
* [Lucia](https://github.com/aidenybai/lucia) ⚠️ Archived - 3kb library for tiny web apps.
* [espresso.js](https://github.com/techlayer/espresso.js) ⭐ 531 | 🐛 0 | 🌐 JavaScript | 📅 2021-11-23 - A minimal JavaScript library for crafting user interfaces.
* [atvjs](https://github.com/emadalam/atvjs) ⭐ 310 | 🐛 22 | 🌐 JavaScript | 📅 2023-03-08 - Blazing fast Apple TV application development using pure JavaScript.
* [Keo](https://github.com/Wildhoney/Keo) ⭐ 227 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-24 - Functional stateless React components with Shadow DOM support.
* [Whatsup](https://github.com/whatsup/whatsup) ⭐ 152 | 🐛 0 | 🌐 TypeScript | 📅 2024-03-31 - A frontend framework for chillout-mode development 🥤. JSX components on generators, fast mobx-like state management and exclusive cssx style system.
* [aurelia](http://aurelia.io) - A JavaScript client framework for mobile, desktop and web.
* [react](https://reactjs.org/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [FoalTS](https://foalts.org) - Elegant and all-inclusive Node.JS framework for building web applications (TypeScript).

## Node-Powered CMS Frameworks

* [Strapi](https://github.com/strapi/strapi) ⭐ 71,230 | 🐛 760 | 🌐 TypeScript | 📅 2026-02-07 - Open source Node.js Headless CMS to easily build customisable APIs.
* [Ghost](https://github.com/tryghost/Ghost) ⭐ 51,764 | 🐛 361 | 🌐 JavaScript | 📅 2026-02-07 - simple, powerful publishing platform.
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) ⭐ 12,435 | 🐛 94 | 🌐 JavaScript | 📅 2025-08-21 - reactive CMS, real-time architecture and design.
* [KeystoneJS](https://github.com/keystonejs/keystone) ⭐ 9,839 | 🐛 138 | 🌐 TypeScript | 📅 2026-02-04 - powerful CMS and web app framework.
* [Apostrophe](https://github.com/punkave/apostrophe) ⭐ 4,522 | 🐛 131 | 🌐 JavaScript | 📅 2026-02-06 - CMS with content editing and essential services.
* [PencilBlue](https://github.com/pencilblue/pencilblue/) ⭐ 1,569 | 🐛 62 | 🌐 JavaScript | 📅 2021-12-09 - CMS and blogging platform.
* [Factor](https://github.com/fiction-com/factor) ⭐ 1,459 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-16 - The Javascript CMS
* [Cody](https://github.com/jcoppieters/cody) ⭐ 683 | 🐛 8 | 🌐 JavaScript | 📅 2025-08-06 - CMS with WSYWYG editor.
* [We.js](https://github.com/wejs/we/) ⭐ 212 | 🐛 27 | 🌐 JavaScript | 📅 2022-12-30 - framework for real time apps, sites or blogs.
* [Nodizecms](https://github.com/nodize/nodizecms) ⚠️ Archived - CMS for CoffeeScript lovers.
* [Hatch.js](https://github.com/inventures/hatchjs) ⭐ 72 | 🐛 14 | 🌐 JavaScript | 📅 2020-04-07 - CMS platform with social features.
* [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2020-04-07 - fast and minimalist CMS based on Node.js.

## Templating Engines

*Templating engines allow you to perform string interpolation.*

* [Pug](https://github.com/pugjs/pug) ⭐ 21,850 | 🐛 329 | 🌐 JavaScript | 📅 2024-07-10 - Robust, elegant, feature rich template engine for nodejs. (formerly known as Jade)
* [handlebars.js](https://github.com/handlebars-lang/handlebars.js) ⭐ 18,587 | 🐛 117 | 🌐 JavaScript | 📅 2025-08-19 - An extension to the Mustache templating language.
* [mustache.js](https://github.com/janl/mustache.js) ⭐ 16,719 | 🐛 115 | 🌐 JavaScript | 📅 2024-06-14 - Minimal templating with {{mustaches}} in JavaScript.
* [marko](https://github.com/marko-js/marko) ⭐ 14,311 | 🐛 16 | 🌐 JavaScript | 📅 2026-02-06 - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output.
* [EJS](https://github.com/mde/ejs) ⭐ 8,084 | 🐛 25 | 🌐 JavaScript | 📅 2026-01-22 - Effective JavaScript templating.
* [hogan.js](https://github.com/twitter/hogan.js) ⭐ 5,135 | 🐛 37 | 🌐 JavaScript | 📅 2023-04-10 - A compiler for the Mustache templating language.
* [doT](https://github.com/olado/doT) ⭐ 5,058 | 🐛 31 | 🌐 JavaScript | 📅 2023-11-02 - The fastest + concise JavaScript template engine for nodejs and browsers.
* [swig](https://github.com/paularmstrong/swig) ⚠️ Archived - (Archived) A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.
* [dustjs](https://github.com/linkedin/dustjs/) ⭐ 2,913 | 🐛 82 | 🌐 JavaScript | 📅 2023-10-24 - Asynchronous templates for the browser and node.js.
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) ⚠️ Archived - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies.
* [eco](https://github.com/sstephenson/eco/) ⚠️ Archived - Embedded CoffeeScript templates.
* [t.js](https://github.com/jasonmoo/t.js) ⭐ 832 | 🐛 13 | 🌐 HTML | 📅 2023-10-18 - A tiny JavaScript templating framework in \~400 bytes gzipped.
* [xtemplate](https://github.com/xtemplate/xtemplate) ⭐ 563 | 🐛 11 | 🌐 JavaScript | 📅 2023-01-16 - eXtensible Template Engine lib for node and the browser
* [nunjucks](https://mozilla.github.io/nunjucks/) - A rich and powerful templating language for JavaScript from Mozilla.
* [hmpl](https://hmpl-lang.dev) - Server-oriented customizable templating for JavaScript.

## Game Engines

* [A-Frame](https://aframe.io) - Make WebVR.
* [Cocos](https://www.cocos.com) - Open Source Cross-Platform Game Development Framework.
* [Impact](https://impactjs.com) - Impact - HTML5 Canvas & JavaScript Game Engine.
* [GDevelop](https://gdevelop.io) - Free and Easy Game-Making App.
* [Kaboom.js](https://kaboomjs.com) - A game programming library that helps you make games fast and fun.
* [Matter.js](https://brm.io/matter-js) - A 2D rigid body JavaScript physics engine.
* [melonJS](https://melonjs.org) - Open source HTML5 game engine that empowers developers and designers to focus on content.
* [Phaser](https://phaser.io) - Phaser - A fast, fun and free open source HTML5 game framework.
* [PixiJS](https://pixijs.com) - The HTML5 Creation Engine.
* [PlayCanvas](https://playcanvas.com) - PlayCanvas WebGL Game Engine.

## Articles and Posts

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-voc%C3%AA-deveria-conhecer-b70e94d1d706) - Article about concepts of JavaScript Functional.
* [Multi-threading using web-workers](https://www.loginradius.com/blog/async/adding-multi-threading-to-javascript-using-web-workers/) - Web Workers: Adding Multi-threading to JavaScript
* [this keyword in JavaScript](https://www.loginradius.com/blog/async/breaking-down-this-keyword-in-javascript/) - Breaking down the 'this' keyword in JavaScript

## Data Visualization

*Data visualization tools for the web.*

* [d3](https://github.com/d3/d3) ⭐ 112,268 | 🐛 27 | 🌐 Shell | 📅 2025-12-02 - A JavaScript visualization library for HTML and SVG.
* [three.js](https://github.com/mrdoob/three.js) ⭐ 110,759 | 🐛 607 | 🌐 JavaScript | 📅 2026-02-06 - JavaScript 3D library.
* [Chart.js](https://github.com/chartjs/Chart.js) ⭐ 67,110 | 🐛 524 | 🌐 JavaScript | 📅 2025-12-08 - Simple HTML5 Charts using the \<canvas> tag.
* [echarts](https://github.com/apache/echarts) ⭐ 65,651 | 🐛 1,811 | 🌐 TypeScript | 📅 2026-02-05 - Enterprise Charts.
* [fabric.js](https://github.com/kangax/fabric.js) ⭐ 30,909 | 🐛 466 | 🌐 TypeScript | 📅 2026-02-05 - JavaScript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* [recharts](https://github.com/recharts/recharts) ⭐ 26,610 | 🐛 444 | 🌐 TypeScript | 📅 2026-02-07 - Redefined chart library built with React and D3.
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) ⭐ 25,064 | 🐛 33 | 🌐 TypeScript | 📅 2026-02-07 - A framework for building 3D games with HTML 5 and WebGL.
* [Frappe Charts](https://github.com/frappe/charts) ⭐ 15,090 | 🐛 143 | 🌐 JavaScript | 📅 2025-07-02 - GitHub-inspired simple and modern SVG charts for the web with zero dependencies.
* [paper.js](https://github.com/paperjs/paper.js) ⭐ 14,964 | 🐛 431 | 🌐 JavaScript | 📅 2024-07-23 - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* [G2](https://github.com/antvis/G2) ⭐ 12,516 | 🐛 181 | 🌐 TypeScript | 📅 2026-02-07 - A highly interactive data-driven visualization grammar for statistical charts.
* [G6](https://github.com/antvis/g6) ⭐ 11,954 | 🐛 328 | 🌐 TypeScript | 📅 2026-01-08 - A graph visualization engine.
* [sigma.js](https://github.com/jacomyal/sigma.js) ⭐ 11,883 | 🐛 34 | 🌐 TypeScript | 📅 2025-12-23 - A JavaScript library dedicated to graph drawing.
* [svg.js](https://github.com/wout/svg.js) ⭐ 11,746 | 🐛 15 | 🌐 JavaScript | 📅 2025-09-15 - A lightweight library for manipulating and animating SVG.
* [raphael](https://github.com/DmitryBaranovskiy/raphael) ⭐ 11,297 | 🐛 348 | 🌐 JavaScript | 📅 2024-01-12 - JavaScript Vector Library.
* [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) ⭐ 10,838 | 🐛 26 | 🌐 JavaScript | 📅 2026-01-21 - A fully featured graph theory library.
* [trianglify](https://github.com/qrohlf/trianglify) ⭐ 10,102 | 🐛 12 | 🌐 JavaScript | 📅 2025-05-12 - Low poly style background generator with d3.js.
* [c3](https://github.com/c3js/c3) ⭐ 9,364 | 🐛 779 | 🌐 JavaScript | 📅 2026-01-21 - D3-based reusable chart library.
* [two.js](https://github.com/jonobr1/two.js) ⭐ 8,602 | 🐛 48 | 🌐 JavaScript | 📅 2026-02-04 - A renderer agnostic two-dimensional drawing api for the web.
* [dc.js](https://github.com/dc-js/dc.js) ⭐ 7,452 | 🐛 413 | 🌐 JavaScript | 📅 2024-07-31 - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [metrics-graphics](https://github.com/mozilla/metrics-graphics) ⭐ 7,430 | 🐛 131 | 🌐 TypeScript | 📅 2022-05-31 - A library optimized for concise, principled data graphics and layouts.
* [nvd3](https://github.com/novus/nvd3) ⭐ 7,245 | 🐛 565 | 🌐 JavaScript | 📅 2023-09-15 - Build re-usable charts and chart components for d3.js.
* [mxGraph](https://github.com/jgraph/mxgraph) ⚠️ Archived - Diagramming library that enables interactive graph and charting applications to be quickly created that run natively in any major browser that is supported by its vendor.
* [morris.js](https://github.com/morrisjs/morris.js) ⭐ 6,890 | 🐛 326 | 🌐 CoffeeScript | 📅 2021-10-07 - Pretty time-series line graphs.
* [rickshaw](https://github.com/shutterstock/rickshaw) ⭐ 6,523 | 🐛 203 | 🌐 JavaScript | 📅 2025-01-17 - JavaScript toolkit for creating interactive real-time graphs.
* [heatmap.js](https://github.com/pa7/heatmap.js) ⭐ 6,368 | 🐛 165 | 🌐 JavaScript | 📅 2023-10-31 - JavaScript Library for HTML5 canvas based heatmaps.
* [flot](https://github.com/flot/flot) ⭐ 5,927 | 🐛 631 | 🌐 JavaScript | 📅 2023-11-08 - Attractive JavaScript charts for jQuery.
* [Frappe Gantt](https://github.com/frappe/gantt) ⭐ 5,833 | 🐛 73 | 🌐 JavaScript | 📅 2025-10-31 - A simple, interactive, modern gantt chart library for the web.
* [jointjs](https://github.com/clientIO/joint) ⭐ 5,192 | 🐛 39 | 🌐 JavaScript | 📅 2026-02-04 - Diagramming library to create static diagrams or fully interactive diagramming tools.
* [epoch](https://github.com/epochjs/epoch) ⭐ 4,956 | 🐛 69 | 🌐 HTML | 📅 2019-02-14 - A general purpose real-time charting library.
* [cubism](https://github.com/square/cubism) ⭐ 4,938 | 🐛 42 | 🌐 JavaScript | 📅 2025-04-01 - A D3 plugin for visualizing time series.
* [Infographic](https://github.com/antvis/Infographic) ⭐ 4,246 | 🐛 9 | 🌐 TypeScript | 📅 2026-02-06 - A next-generation declarative infographic visualization engine.
* [peity](https://github.com/benpickles/peity) ⭐ 4,233 | 🐛 23 | 🌐 HTML | 📅 2024-04-11 - Progressive <svg> bar, line and pie charts.
* [d3-cloud](https://github.com/jasondavies/d3-cloud) ⭐ 3,928 | 🐛 38 | 🌐 JavaScript | 📅 2025-12-02 - Create word clouds in JavaScript.
* [arbor](https://github.com/samizdatco/arbor) ⭐ 2,666 | 🐛 56 | 🌐 JavaScript | 📅 2020-04-10 - A graph visualization library using web workers and jQuery.
* [G2Plot](https://github.com/antvis/G2Plot) ⭐ 2,638 | 🐛 458 | 🌐 TypeScript | 📅 2025-09-19 - An interactive and responsive charting library. Based on the grammar of graphics.
* [vizzu](https://github.com/vizzuhq/vizzu-lib) ⭐ 1,996 | 🐛 3 | 🌐 JavaScript | 📅 2025-09-26 - Library for animated data visualizations and data stories.
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) ⭐ 1,560 | 🐛 24 | 🌐 JavaScript | 📅 2020-04-10 - Dynamic HTML5 visualization.
* [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) ⭐ 1,511 | 🐛 156 | 🌐 JavaScript | 📅 2016-01-20 - Charts for Raphaël.
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) ⭐ 1,241 | 🐛 143 | 🌐 JavaScript | 📅 2020-04-10 - A plugin for the jQuery JavaScript library to generate small sparkline charts directly in the browser.
* [GraphicsJS](https://github.com/AnyChart/GraphicsJS) ⭐ 996 | 🐛 8 | 🌐 JavaScript | 📅 2024-09-10 - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.
* [d4](https://github.com/heavysixer/d4) ⭐ 432 | 🐛 18 | 🌐 JavaScript | 📅 2020-04-11 - A friendly reusable charts DSL for D3.
* [chartist-js](https://github.com/gionkunz/chartist-js) ⭐ 97 | 🐛 10 | 🌐 JavaScript | 📅 2024-05-06 - Simple responsive charts.
* [vega](https://github.com/trifacta/vega) ⭐ 30 | 🐛 0 | 📅 2015-11-12 - A visualization grammar.
* [visjs](https://github.com/visjs) - Multiple Libraries for dynamic, browser-based data visualization.
* [dimple.js](http://dimplejs.org) - Easy charts for business analytics powered by d3.
* [cola.js](https://ialab.it.monash.edu/webcola/) - library for arranging your HTML5 documents and diagrams using constraint-based optimization techniques

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](https://www.anychart.com/), [plotly](https://plotly.com/), and [lightning chart](https://www.arction.com/lightningchart-js/).

## Timeline

* [timesheet.js](https://github.com/sbstjn/timesheet.js) ⭐ 6,985 | 🐛 23 | 🌐 JavaScript | 📅 2018-05-24 - JavaScript library for simple HTML5 & CSS3 time sheets.
* [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) ⭐ 3,158 | 🐛 233 | 🌐 JavaScript | 📅 2025-12-01 - A Storytelling Timeline built in JavaScript.

## Spreadsheet

* [HANDSONTABLE](https://github.com/handsontable/handsontable) ⭐ 21,772 | 🐛 403 | 🌐 JavaScript | 📅 2026-02-06 - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers
* [Luckysheet](https://github.com/mengshukeji/Luckysheet) ⚠️ Archived - Luckysheet is an online spreadsheet like excel that is powerful, simple to configure, and completely open source.
* [Jspreadsheet CE](https://github.com/jspreadsheet/ce) ⭐ 7,120 | 🐛 142 | 🌐 JavaScript | 📅 2026-01-13 - Jspreadsheet is a lightweight vanilla javascript plugin to create amazing web-based interactive tables and spreadsheets compatible with other spreadsheet software.
* [RevoGrid](https://github.com/revolist/revogrid) ⭐ 3,255 | 🐛 63 | 🌐 TypeScript | 📅 2026-01-01 - RevoGrid is a fast, responsive excel like data grid library for modern web applications.
* [Frappe Datatable](https://github.com/frappe/datatable) ⭐ 1,278 | 🐛 63 | 🌐 JavaScript | 📅 2026-01-19 - Frappe DataTable is a simple, modern and interactive datatable library for displaying tabular data.

## Editors

* [quill](https://github.com/quilljs/quill) ⭐ 46,818 | 🐛 625 | 🌐 TypeScript | 📅 2025-07-25 - A cross browser rich text editor with an API.
* [CodeMirror](https://github.com/codemirror/CodeMirror) ⭐ 27,230 | 🐛 437 | 🌐 JavaScript | 📅 2026-02-05 - In-browser code editor.
* [ace](https://github.com/ajaxorg/ace) ⭐ 27,130 | 🐛 135 | 🌐 JavaScript | 📅 2026-02-05 - Ace (Ajax.org Cloud9 Editor).
* [Draft.js](https://github.com/facebook/draft-js) ⚠️ Archived - A React framework for building text editors.
* [trix](https://github.com/basecamp/trix) ⭐ 19,902 | 🐛 173 | 🌐 JavaScript | 📅 2026-01-09 - A rich text editor for everyday writing. By Basecamp.
* [medium-editor](https://github.com/yabwe/medium-editor) ⭐ 16,118 | 🐛 360 | 🌐 JavaScript | 📅 2024-10-24 - Medium.com WYSIWYG editor clone.
* [TinyMCE](https://github.com/tinymce/tinymce) ⭐ 16,093 | 🐛 431 | 🌐 TypeScript | 📅 2026-02-07 - The JavaScript Rich Text editor.
* [jsoneditor](https://github.com/josdejong/jsoneditor) ⭐ 12,183 | 🐛 228 | 🌐 JavaScript | 📅 2026-02-05 - A web-based tool to view, edit and format JSON.
* [Summernote](https://github.com/summernote/summernote) ⭐ 11,808 | 🐛 98 | 🌐 JavaScript | 📅 2026-01-21 - Super simple WYSIWYG editor.
* [wysihtml5](https://github.com/xing/wysihtml5) ⚠️ Archived - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles.
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) ⚠️ Archived - Tiny bootstrap-compatible WYSIWYG rich text editor.
* [Squire](https://github.com/neilj/Squire) ⭐ 4,892 | 🐛 54 | 🌐 TypeScript | 📅 2026-01-12 - HTML5 rich text editor.
* [pen](https://github.com/sofish/pen) ⭐ 4,813 | 🐛 65 | 🌐 JavaScript | 📅 2018-09-23 - enjoy live editing (+markdown).
* [vim.js](https://github.com/coolwanglu/vim.js) ⚠️ Archived - JavaScript port of Vim with a persistent `~/.vimrc`.
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) ⭐ 4,228 | 🐛 88 | 🌐 JavaScript | 📅 2020-04-13 - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* [Trumbowyg](https://github.com/Alex-D/Trumbowyg) ⭐ 4,144 | 🐛 112 | 🌐 JavaScript | 📅 2025-03-02 - A lightweight and amazing WYSIWYG JavaScript editor.
* [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) ⭐ 4,124 | 🐛 191 | 🌐 JavaScript | 📅 2020-04-14 - Simple, beautiful wysiwyg editor
* [editor](https://github.com/lepture/editor) ⭐ 2,798 | 🐛 54 | 🌐 JavaScript | 📅 2017-10-09 - A markdown editor. still on development.
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) ⭐ 1,684 | 🐛 57 | 🌐 JavaScript | 📅 2020-04-13 - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium.
* [popline](https://github.com/kenshin54/popline) ⭐ 1,056 | 🐛 13 | 🌐 JavaScript | 📅 2025-08-12 - Popline is an HTML5 Rich-Text-Editor Toolbar.
* [raptor-editor](https://github.com/PANmedia/raptor-editor) ⭐ 532 | 🐛 50 | 🌐 PHP | 📅 2020-04-15 - Raptor, an HTML5 WYSIWYG content editor!
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) ⭐ 523 | 🐛 7 | 🌐 JavaScript | 📅 2025-02-05 - The best web text editor for everyone.
* [Everright-formEditor](https://github.com/Liberty-liu/Everright-formEditor) ⭐ 510 | 🐛 8 | 🌐 JavaScript | 📅 2024-04-22 - A visual drag-and-drop low-code form editor
* [esprima](https://github.com/ariya/esprima) ⭐ 413 | 🐛 0 | 🌐 TypeScript | 📅 2021-06-14 - ECMAScript parsing infrastructure for multipurpose analysis.

## Documentation

* [ESDoc](https://github.com/esdoc/esdoc) ⭐ 2,736 | 🐛 166 | 🌐 JavaScript | 📅 2024-08-14 is a good documentation generator for JavaScript.
* [codecrumbs](https://github.com/Bogdan-Lyashenko/codecrumbs) ⭐ 2,719 | 🐛 30 | 🌐 JavaScript | 📅 2021-09-11 is a visual tool for learning and documenting a codebase by putting breadcrumbs in source code.
* [dox](https://github.com/tj/dox) ⭐ 2,156 | 🐛 19 | 🌐 JavaScript | 📅 2022-09-07 is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags.
* [jsduck](https://github.com/senchalabs/jsduck) ⭐ 1,497 | 🐛 86 | 🌐 Ruby | 📅 2020-04-16 - API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too.
* [Ronn](https://github.com/rtomayko/ronn) ⭐ 1,402 | 🐛 48 | 🌐 Ruby | 📅 2022-01-29 builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web.
* [Beautiful docs](https://github.com/beautiful-docs/beautiful-docs) ⚠️ Archived is a documentation viewer based on markdown files.
* [jsdox](https://github.com/sutoiku/jsdox) ⭐ 210 | 🐛 32 | 🌐 JavaScript | 📅 2023-04-18 is a JSDoc3 to Markdown documentation generator.
* [DevDocs](https://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [docco](http://ashkenas.com/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* [YUIDoc](http://yui.github.io/yuidoc/) is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.

## Files

*Libraries for working with files.*

* [PDF.js](https://github.com/mozilla/pdf.js) ⭐ 52,795 | 🐛 482 | 🌐 JavaScript | 📅 2026-02-06 - PDF Reader in JavaScript.
* [jsPDF](https://github.com/MrRio/jsPDF) ⭐ 31,099 | 🐛 112 | 🌐 JavaScript | 📅 2026-02-05 - JavaScript PDF generation.
* [Papa Parse](https://github.com/mholt/PapaParse) ⭐ 13,368 | 🐛 212 | 🌐 JavaScript | 📅 2025-08-20 - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* [diff2html](https://github.com/rtfpessoa/diff2html) ⭐ 3,310 | 🐛 21 | 🌐 TypeScript | 📅 2026-01-31 - Git diff output parser and pretty HTML generator.
* [jBinary](https://github.com/jDataView/jBinary) ⭐ 552 | 🐛 27 | 🌐 JavaScript | 📅 2022-12-08 - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.

## Functional Programming

*Functional programming libraries to extend JavaScript’s capabilities.*

* [lodash](https://github.com/lodash/lodash) ⭐ 61,605 | 🐛 107 | 🌐 JavaScript | 📅 2026-02-06 - A utility library delivering consistency, customization, performance, & extras.
* [underscore](https://github.com/jashkenas/underscore) ⭐ 27,381 | 🐛 52 | 🌐 JavaScript | 📅 2026-01-28 - JavaScript's utility \_ belt.
* [ramda](https://github.com/ramda/ramda) ⭐ 24,104 | 🐛 147 | 🌐 JavaScript | 📅 2026-01-22 - A practical functional library for JavaScript programmers.
* [lazy.js](https://github.com/dtao/lazy.js) ⭐ 5,991 | 🐛 59 | 🌐 JavaScript | 📅 2020-07-15 - Like Underscore, but lazier.
* [Sugar](https://github.com/andrewplummer/Sugar) ⭐ 4,521 | 🐛 94 | 🌐 JavaScript | 📅 2024-06-13 - A JavaScript library for working with native objects.
* [rambda](https://github.com/selfrefactor/rambda) ⭐ 1,755 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-06 - Faster and smaller alternative to *Ramda*.
* [mout](https://github.com/mout/mout) ⭐ 1,287 | 🐛 21 | 🌐 JavaScript | 📅 2023-10-24 - Modular JavaScript Utilities.
* [fxts](https://github.com/marpple/FxTS) ⭐ 1,148 | 🐛 9 | 🌐 TypeScript | 📅 2026-02-01 - Lazy evaluation and concurrency.
* [wild-wild-path](https://github.com/ehmicky/wild-wild-path) ⭐ 730 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-28 - Object property paths with wildcards and regexps.
* [sweet-monads](https://github.com/JSMonk/sweet-monads) ⭐ 355 | 🐛 13 | 🌐 TypeScript | 📅 2024-11-18 - A utility library containing popular monads and lazy iterators.
* [preludejs](https://github.com/alanrsoares/prelude-js) ⭐ 100 | 🐛 4 | 🌐 JavaScript | 📅 2023-08-03 - Hardcore Functional Programming for JavaScript.

## Reactive Programming

*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJS](https://github.com/ReactiveX/rxjs) ⭐ 31,631 | 🐛 293 | 🌐 TypeScript | 📅 2025-02-23 - A reactive programming library for JavaScript.
* [MobX](https://github.com/mobxjs/mobx) ⭐ 28,173 | 🐛 83 | 🌐 TypeScript | 📅 2026-01-04 - TFRP library for simple, scalable state management.
* [Bacon](https://github.com/baconjs/bacon.js) ⭐ 6,462 | 🐛 86 | 🌐 TypeScript | 📅 2025-04-18 - FRP (functional reactive programming) library for JavaScript.
* [Most.js](https://github.com/cujojs/most) ⭐ 3,496 | 🐛 50 | 🌐 JavaScript | 📅 2022-12-06 - high performance FRP library.
* [concent](https://github.com/concentjs/concent) ⭐ 1,393 | 🐛 11 | 🌐 TypeScript | 📅 2026-01-22 - Definitely the ❤️ simplest but ⚡️ strongest state management for react, it is predictable、progressive and efficient.
* [stunk](https://github.com/I-am-abdulazeez/stunk) ⭐ 163 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-24 A framework-agnostic state management library that keeps your app’s state clean and simple. It uses a fine-grained state model, breaking state into independent, manageable chunks.
* [Kefir](https://github.com/pozadi/kefir) ⭐ 8 | 🐛 0 | 🌐 HTML | 📅 2023-09-09 - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption.
* [Highland](https://caolan.github.io/highland/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.

## Data Structure

*Data structure libraries to build a more sophisticated application.*

* [immutable-js](https://github.com/facebook/immutable-js) ⭐ 33,098 | 🐛 121 | 🌐 TypeScript | 📅 2026-01-28 - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector.
* [mori](https://github.com/swannodette/mori) ⭐ 3,375 | 🐛 63 | 🌐 Clojure | 📅 2020-04-19 - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [buckets](https://github.com/mauriciosantos/Buckets-JS) ⭐ 1,256 | 🐛 8 | 🌐 JavaScript | 📅 2020-12-21 - A complete, fully tested and documented data structure library written in JavaScript.
* [ngraph.graph](https://github.com/anvaka/ngraph.graph) ⭐ 570 | 🐛 9 | 🌐 JavaScript | 📅 2026-01-02 - Graph data structure in javascript.
* [hashmap](https://github.com/flesler/hashmap) ⭐ 383 | 🐛 4 | 🌐 JavaScript | 📅 2021-02-20 - Simple hashmap implementation that supports any kind of keys.
* [js-sdsl](https://github.com/zly201/js-sdsl) ⚠️ Archived - Refer to the javascript standard data structure library implemented by c++ stl, which supports c++ bidirectional iterator mode.

## Date

*Date Libraries.*

* [dayjs](https://github.com/iamkun/dayjs) ⭐ 48,539 | 🐛 1,188 | 🌐 JavaScript | 📅 2026-01-12 - Day.js 2KB immutable date library alternative to Moment.js with the same modern API.
* [moment](https://github.com/moment/moment) ⭐ 48,075 | 🐛 290 | 🌐 JavaScript | 📅 2024-08-14 - Parse, validate, manipulate, and display dates in JavaScript.
* [date-fns](https://github.com/date-fns/date-fns) ⭐ 36,448 | 🐛 906 | 🌐 TypeScript | 📅 2025-09-08 - Modern JavaScript date utility library.
* [luxon](https://github.com/moment/luxon) ⭐ 16,350 | 🐛 192 | 🌐 JavaScript | 📅 2026-02-04 - Luxon is a library for working with dates and times in JavaScript.
* [ms.js](https://github.com/rauchg/ms.js) ⭐ 5,502 | 🐛 23 | 🌐 TypeScript | 📅 2026-01-16 - Tiny millisecond conversion utility.
* [timeago.js](https://github.com/hustcc/timeago.js) ⭐ 5,388 | 🐛 50 | 🌐 TypeScript | 📅 2024-07-24 - Simple library (less then 2kb) used to format date with `*** time ago` statement.
* [moment-timezone](https://github.com/moment/moment-timezone) ⭐ 3,883 | 🐛 73 | 🌐 JavaScript | 📅 2026-01-21 - Timezone support for moment.js.
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) ⭐ 3,809 | 🐛 44 | 🌐 JavaScript | 📅 2025-05-10 - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* [tempo](https://github.com/formkit/tempo) ⭐ 2,578 | 🐛 16 | 🌐 TypeScript | 📅 2025-12-22 - Parsing, formatting, and timezones — Tempo is a small tree-shakable library for native Date objects.
* [fecha](https://github.com/taylorhakes/fecha) ⭐ 2,077 | 🐛 8 | 🌐 JavaScript | 📅 2023-01-05 - Lightweight date formatting and parsing (\~2KB). Meant to replace parsing and formatting functionality of moment.js.
* [date](https://github.com/MatthewMueller/date) ⭐ 1,482 | 🐛 51 | 🌐 JavaScript | 📅 2022-09-15 - Date() for humans.
* [timezone-js](https://github.com/mde/timezone-js) ⚠️ Archived - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data.
* [countdown.js](https://github.com/gumroad/countdown.js) ⭐ 422 | 🐛 4 | 🌐 JavaScript | 📅 2013-09-21 - Super simple countdowns.
* [map-countdown](https://github.com/dawidjaniga/map-countdown) ⭐ 5 | 🐛 11 | 🌐 JavaScript | 📅 2025-10-24 - A browser countdown built on top of the Google Maps.

## String

*String Libraries.*

* [query-string](https://github.com/sindresorhus/query-string) ⭐ 6,907 | 🐛 2 | 🌐 JavaScript | 📅 2025-09-19 - Parse and stringify URL query strings.
* [URI.js](https://github.com/medialize/URI.js/) ⭐ 6,247 | 🐛 104 | 🌐 JavaScript | 📅 2023-08-27 - JavaScript URL mutation library.
* [he](https://github.com/mathiasbynens/he) ⭐ 3,673 | 🐛 23 | 🌐 JavaScript | 📅 2021-12-29 - A robust HTML entity encoder/decoder written in JavaScript.
* [voca](https://github.com/panzerdp/voca) ⭐ 3,609 | 🐛 15 | 🌐 JavaScript | 📅 2023-08-01 - The ultimate JavaScript string library
* [underscore.string](https://github.com/epeli/underscore.string) ⚠️ Archived - String manipulation extensions for Underscore.js JavaScript library.
* [sprintf.js](https://github.com/alexei/sprintf.js) ⭐ 2,137 | 🐛 67 | 🌐 JavaScript | 📅 2024-04-05 - A sprintf implementation.
* [string.js](https://github.com/jprichardson/string.js) ⭐ 1,805 | 🐛 74 | 🌐 JavaScript | 📅 2021-06-04 - Extra JavaScript string methods.
* [multiline](https://github.com/sindresorhus/multiline) ⚠️ Archived - Multiline strings in JavaScript.
* [url-pattern](https://github.com/snd/url-pattern) ⭐ 590 | 🐛 13 | 🌐 CoffeeScript | 📅 2020-08-06 - Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings.
* [jsurl](https://github.com/Mikhus/domurl) ⭐ 576 | 🐛 9 | 🌐 JavaScript | 📅 2020-11-05 - Lightweight URL manipulation with JavaScript.
* [url-state-machine](https://github.com/anonrig/url-js) ⭐ 165 | 🐛 2 | 🌐 JavaScript | 📅 2023-10-07 - Super fast spec-compliant URL parser state machine for Node.js.
* [plexis](https://github.com/plexis-js/plexis) ⭐ 146 | 🐛 11 | 🌐 JavaScript | 📅 2023-10-19 - Lo-fi, powerful, community-driven string manipulation library.
* [selecting](https://github.com/EvandroLG/selecting) ⭐ 96 | 🐛 4 | 🌐 JavaScript | 📅 2015-10-22 - A library that allows you to access the text selected by the user.

## Number

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) ⭐ 9,730 | 🐛 348 | 🌐 JavaScript | 📅 2024-04-24 - A JavaScript library for formatting and manipulating numbers.
* [odometer](https://github.com/HubSpot/odometer) ⚠️ Archived - Smoothly transitions numbers with ease.
* [chance.js](https://github.com/chancejs/chancejs) ⭐ 6,560 | 🐛 177 | 🌐 JavaScript | 📅 2025-05-18 - Random generator helper in JavaScript. Can generate numbers, strings etc.
* [Fraction.js](https://github.com/infusion/Fraction.js) ⭐ 681 | 🐛 2 | 🌐 JavaScript | 📅 2025-09-26 - A rational number library for JavaScript.
* [Complex.js](https://github.com/infusion/Complex.js) ⭐ 251 | 🐛 6 | 🌐 JavaScript | 📅 2025-11-14 - A complex number library for JavaScript.
* [Quaternion.js](https://github.com/infusion/Quaternion.js) ⭐ 191 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-17 - A quaternion library for JavaScript
* [Polynomial.js](https://github.com/infusion/Polynomial.js) ⭐ 133 | 🐛 3 | 🌐 JavaScript | 📅 2025-09-12 - A polynomials library for JavaScript.
* [accounting.js](https://github.com/josscrowcroft/accounting.js) ⭐ 35 | 🐛 1 | 🌐 CSS | 📅 2016-10-18 - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* [money.js](https://github.com/josscrowcroft/money.js) ⭐ 13 | 🐛 0 | 🌐 CSS | 📅 2014-07-15 - A tiny (1kb) JavaScript currency conversion library, for web & nodeJS.

## Storage

* [localForage](https://github.com/mozilla/localForage) ⭐ 25,751 | 🐛 249 | 🌐 JavaScript | 📅 2024-07-30 - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* [js-cookie](https://github.com/js-cookie/js-cookie) ⭐ 22,839 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-06 - A simple, lightweight JavaScript API for handling browser cookies.
* [pouchdb](https://github.com/pouchdb/pouchdb) ⭐ 17,540 | 🐛 160 | 🌐 JavaScript | 📅 2026-01-23 - Javascript db inspired by Apache CouchDB to run well within the browser.
* [Dexie.js](https://github.com/dexie/Dexie.js) ⭐ 14,036 | 🐛 592 | 🌐 TypeScript | 📅 2026-01-30 - Dexie.js is a wrapper library for indexedDB.
* [store.js](https://github.com/marcuswestin/store.js) ⭐ 14,013 | 🐛 99 | 🌐 JavaScript | 📅 2024-01-16 - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood.
* [NeDB](https://github.com/louischatriot/nedb) ⭐ 13,567 | 🐛 209 | 🌐 JavaScript | 📅 2025-05-15 - Embedded Persistent database for Browsers, nw\.js, electron.
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) ⚠️ Archived - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* [Hoodie](https://github.com/hoodiehq/hoodie) ⭐ 4,535 | 🐛 89 | 🌐 JavaScript | 📅 2024-07-27 - Offline First backend to work in browser without internet connectivity.
* [basket.js](https://github.com/addyosmani/basket.js) ⭐ 3,358 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-02 - A script and resource loader for caching & loading scripts with localStorage.
* [cross-storage](https://github.com/zendesk/cross-storage) ⭐ 2,223 | 🐛 14 | 🌐 JavaScript | 📅 2025-12-10 - Cross domain local storage, with permissions.
* [lawnchair.js](https://github.com/brianleroux/lawnchair/) ⭐ 2,126 | 🐛 86 | 🌐 JavaScript | 📅 2020-05-17 - Simple client-side JSON storage.
* [basil.js](https://github.com/Wisembly/basil.js) ⭐ 1,975 | 🐛 23 | 🌐 JavaScript | 📅 2022-12-07 - The missing JavaScript smart persistent layer.
* [Cookies](https://github.com/ScottHamper/Cookies) ⭐ 1,769 | 🐛 13 | 🌐 JavaScript | 📅 2020-05-16 - JavaScript Client-Side Cookie Manipulation Library.
* [jStorage](https://github.com/andris9/jStorage) ⭐ 1,529 | 🐛 23 | 🌐 JavaScript | 📅 2020-05-16 - jStorage is a simple key/value database to store data on browser side.
* [DB.js](https://github.com/aaronpowell/db.js/) ⭐ 824 | 🐛 25 | 🌐 JavaScript | 📅 2017-04-12 - Promise based IndexDB Wrapper library.
* [PostgreSQL Browser](https://github.com/datawan-labs/pg) ⭐ 633 | 🐛 4 | 🌐 TypeScript | 📅 2024-12-02 - Browser PostgreSQL Playground, no server, just client and pglite (postgresql wasm)
* [awesome-web-storage](https://github.com/softvar/awesome-web-storage) ⭐ 447 | 🐛 4 | 📅 2024-04-26 - Everything you need to know about client-side storage.
* [proxy-web-storage](https://github.com/KID-joker/proxy-web-storage) ⭐ 384 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-05 - Keep the type of storage value unchanged and change array and object directly. Supports listening to the changes and setting expires.
* [datavore](https://github.com/StanfordHCI/datavore) ⭐ 251 | 🐛 4 | 🌐 JavaScript | 📅 2021-10-30 - A small, fast, in-browser database engine written in JavaScript.
* [crumbsjs](https://github.com/nirtz89/crumbsjs) ⭐ 233 | 🐛 11 | 🌐 JavaScript | 📅 2024-09-26 - A lightweight vanilla ES6 cookies and local storage JavaScript library.
* [sql.js](https://github.com/kripken/sql.js) ⭐ 133 | 🐛 0 | 📅 2020-03-10 - SQLite compiled to JavaScript through Emscripten.
* [bag.js](https://github.com/nodeca/bag.js) ⭐ 89 | 🐛 3 | 🌐 JavaScript | 📅 2021-07-27 - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support.
* [Lovefield](https://google.github.io/lovefield) - Lovefield is a relational database for web apps, By Google.

## Color

* [chroma.js](https://github.com/gka/chroma.js) ⭐ 10,535 | 🐛 63 | 🌐 JavaScript | 📅 2026-02-02 - JavaScript library for all kinds of color manipulations.
* [colors](https://github.com/mrmrs/colors) ⭐ 9,376 | 🐛 16 | 🌐 CSS | 📅 2023-07-20 - Smarter defaults for colors on the web.
* [randomColor](https://github.com/davidmerfield/randomColor) ⭐ 6,128 | 🐛 15 | 🌐 JavaScript | 📅 2025-12-03 - A color generator for JavaScript.
* [TinyColor](https://github.com/bgrins/TinyColor) ⭐ 5,225 | 🐛 102 | 🌐 JavaScript | 📅 2024-06-26 - Fast, small color manipulation and conversion for JavaScript.
* [color](https://github.com/Qix-/color) ⭐ 4,924 | 🐛 19 | 🌐 JavaScript | 📅 2025-11-14 - JavaScript color conversion and manipulation library.
* [Vibrant.js](https://github.com/jariz/vibrant.js/) ⚠️ Archived - Extract prominent colors from an image.
* [PleaseJS](https://github.com/Fooidge/PleaseJS) ⭐ 2,275 | 🐛 20 | 🌐 JavaScript | 📅 2018-08-31 - JavaScript Library for creating random pleasing colors and color schemes.

## I18n And L10n

*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next](https://github.com/i18next/i18next) ⭐ 8,462 | 🐛 11 | 🌐 JavaScript | 📅 2026-02-05 - internationalisation (i18n) with JavaScript the easy way.
* [polyglot](https://github.com/airbnb/polyglot.js) ⭐ 3,729 | 🐛 16 | 🌐 JavaScript | 📅 2025-11-06 - tiny i18n helper library.
* [ttag](https://github.com/ttag-org/ttag) ⭐ 353 | 🐛 44 | 🌐 TypeScript | 📅 2025-07-01 - Modern javascript i18n localization library based on ES6 tagged templates and the good old GNU gettext.
* [attranslate](https://github.com/fkirc/attranslate) ⭐ 350 | 🐛 8 | 🌐 TypeScript | 📅 2025-09-16 - A JavaScript-tool for synchronizing translation-files, including JSON/YAML/XML and other formats.
* [babelfish](https://github.com/nodeca/babelfish/) ⭐ 263 | 🐛 1 | 🌐 JavaScript | 📅 2023-06-19 - i18n with human friendly API and built in plurals support.

## Control Flow

* [async](https://github.com/caolan/async) ⭐ 28,210 | 🐛 24 | 🌐 JavaScript | 📅 2026-02-01 - Async utilities for node and the browser.
* [Bluebird](https://github.com/petkaantonov/bluebird/) ⭐ 20,805 | 🐛 127 | 🌐 JavaScript | 📅 2024-11-07 - fully featured promise library with focus on innovative features and performance.
* [q](https://github.com/kriskowal/q) ⚠️ Archived - A tool for making and composing asynchronous promises in JavaScript.
* [when](https://github.com/cujojs/when) ⭐ 3,433 | 🐛 67 | 🌐 JavaScript | 📅 2022-04-10 - A solid, fast Promises/A+ and when() implementation, plus other async goodies.
* [step](https://github.com/creationix/step/) ⭐ 2,200 | 🐛 21 | 🌐 JavaScript | 📅 2017-08-08 - An async control-flow library that makes stepping through logic easy.
* [contra](https://github.com/bevacqua/contra/) ⭐ 780 | 🐛 1 | 🌐 JavaScript | 📅 2024-03-16 - Asynchronous flow control with a functional taste to it.
* [sporadic](https://github.com/marcoonroad/sporadic) ⭐ 18 | 🐛 21 | 🌐 JavaScript | 📅 2024-08-02 - Composable concurrency abstractions (such as streams, coroutines and Go-like channels) on top of promises, for Node and browser engines.
* [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) ⭐ 13 | 🐛 2 | 🌐 JavaScript | 📅 2020-06-12 - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers).

## Routing

* [page.js](https://github.com/visionmedia/page.js) ⭐ 7,698 | 🐛 128 | 🌐 JavaScript | 📅 2023-06-27 - Micro client-side router inspired by the Express router (\~1200 bytes).
* [director](https://github.com/flatiron/director) ⭐ 5,585 | 🐛 124 | 🌐 JavaScript | 📅 2020-12-26 - A tiny and isomorphic URL router for JavaScript.
* [crossroads](https://github.com/millermedeiros/crossroads.js) ⭐ 1,439 | 🐛 64 | 🌐 JavaScript | 📅 2023-09-13 - JavaScript Routes.
* [pathjs](https://github.com/mtrpcic/pathjs) ⭐ 1,094 | 🐛 60 | 🌐 JavaScript | 📅 2017-02-26 - Simple, lightweight routing for web browsers.
* [navaid](https://github.com/lukeed/navaid) ⭐ 802 | 🐛 7 | 🌐 JavaScript | 📅 2024-01-20 - A navigation aid (aka, router) for the browser in 850 bytes\~!
* [davis.js](https://github.com/olivernn/davis.js) ⭐ 528 | 🐛 41 | 🌐 JavaScript | 📅 2020-08-31 - RESTful degradable JavaScript routing using pushState.

## Security

* [DOMPurify](https://github.com/cure53/DOMPurify) ⭐ 16,589 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-07 - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* [js-xss](https://github.com/leizongmin/js-xss) ⭐ 5,306 | 🐛 70 | 🌐 HTML | 📅 2026-01-14 - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
* [sanitize-html](https://github.com/apostrophecms/sanitize-html) ⭐ 4,132 | 🐛 20 | 🌐 JavaScript | 📅 2025-05-14 - sanitize-html provides a simple HTML sanitizer with a clear API.
* [xss-filters](https://github.com/yahoo/xss-filters) ⚠️ Archived - Secure XSS Filters by Yahoo.
* [pompelmi](https://github.com/pompelmi/pompelmi) ⭐ 464 | 🐛 17 | 🌐 TypeScript | 📅 2026-02-05 - Fast file-upload malware scanning for Node.js.

## Log

* [log](https://github.com/adamschwartz/log) ⭐ 3,018 | 🐛 9 | 🌐 HTML | 📅 2023-04-08 - Console.log with style.
* [loglevel](https://github.com/pimterry/loglevel) ⭐ 2,741 | 🐛 19 | 🌐 JavaScript | 📅 2025-03-20 - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
* [console.log-wrapper](https://github.com/patik/console.log-wrapper) ⭐ 407 | 🐛 0 | 🌐 JavaScript | 📅 2022-05-08 - Log to the console in any browser with clarity.
* [Conzole](https://github.com/Oaxoa/Conzole) ⭐ 214 | 🐛 4 | 🌐 JavaScript | 📅 2016-06-01 - A debug panel built in JavaScript that wraps JavaScript native console object methods and functionality in a panel displayed inside the page.
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends.
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.
* [LogTape](https://logtape.org/) - Simple logging library with zero dependencies for Deno, Node.js, Bun, browsers, and edge functions.

## RegExp

* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](https://regexr.com/) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.
* [Regulex](https://jex.im/regulex/) - JavaScript Regular Expression Parser & Visualizer.
* [Regex-Vis](https://regex-vis.com/) - Regex visualizer & editor.

## Voice Command

* [annyang](https://github.com/TalAter/annyang) ⭐ 6,671 | 🐛 53 | 🌐 JavaScript | 📅 2024-08-07 - A JavaScript library for adding voice commands to your site, using speech recognition.
* [voix.js](https://github.com/pazguille/voix) ⭐ 584 | 🐛 5 | 🌐 JavaScript | 📅 2020-09-02 - A JavaScript library to add voice commands to your sites, apps or games.

## API

* [axios](https://github.com/axios/axios) ⭐ 108,569 | 🐛 313 | 🌐 JavaScript | 📅 2026-02-06 - Promise based HTTP client for the browser and node.js.
* [React Query](https://github.com/tannerlinsley/react-query) ⭐ 48,425 | 🐛 151 | 🌐 TypeScript | 📅 2026-02-02 - Hooks for fetching, caching and updating asynchronous data in React.
* [SWR](https://github.com/vercel/swr) ⭐ 32,297 | 🐛 181 | 🌐 TypeScript | 📅 2026-02-04 - React Hooks library for remote data fetching.
* [wretch](https://github.com/elbywan/wretch) ⭐ 5,147 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-04 - A tiny wrapper built around fetch with an intuitive syntax.
* [SWRV](https://github.com/Kong/swrv) ⭐ 2,267 | 🐛 45 | 🌐 TypeScript | 📅 2026-02-06 - Stale-while-revalidate data fetching for Vue.
* [bottleneck](https://github.com/SGrondin/bottleneck) ⭐ 1,970 | 🐛 89 | 🌐 JavaScript | 📅 2024-01-23 - A powerful rate limiter that makes throttling easy.
* [Optic](https://github.com/opticdev/optic) ⚠️ Archived - Optic automatically documents and tests your APIs.
* [Vue Query](https://github.com/DamianOsipiuk/vue-query) ⭐ 1,117 | 🐛 4 | 🌐 TypeScript | 📅 2023-06-27 - Hooks for fetching, caching and updating asynchronous data in Vue.
* [jquery.rest](https://github.com/jpillora/jquery.rest) ⭐ 614 | 🐛 20 | 🌐 CoffeeScript | 📅 2020-09-02 - A jQuery plugin for easy consumption of RESTful APIs.
* [amygdala](https://github.com/lincolnloop/amygdala) ⚠️ Archived - RESTful HTTP client for JavaScript powered web applications.
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) ⭐ 232 | 🐛 21 | 🌐 JavaScript | 📅 2017-12-07 - JavaScript OAuth 1.0a signature generator for node and the browser.
* [FarFetch](https://github.com/WebsiteBeaver/far-fetch) ⭐ 58 | 🐛 2 | 🌐 JavaScript | 📅 2025-10-07 - Modern Fetch API wrapper for simplicity, with concise file uploading.
* [Rails Ranger](https://github.com/victor-am/rails-ranger) ⭐ 33 | 🐛 3 | 🌐 JavaScript | 📅 2021-08-09 - An opinionated REST client for Ruby on Rails APIs.

## Streaming

* [Tailor](https://github.com/zalando/tailor) ⚠️ Archived - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe.

## Vision Detection

* [tracking.js](https://github.com/eduardolundgren/tracking.js) ⭐ 9,488 | 🐛 226 | 🌐 JavaScript | 📅 2023-06-03 - A modern approach for Computer Vision on the web.
* [ocrad.js](https://github.com/antimatter15/ocrad.js) ⭐ 3,516 | 🐛 27 | 🌐 JavaScript | 📅 2020-09-02 - OCR in JavaScript via Emscripten.

## Machine Learning

* [ConvNetJS](https://github.com/karpathy/convnetjs) ⭐ 11,136 | 🐛 75 | 🌐 JavaScript | 📅 2023-01-07 - Deep Learning in JavaScript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [Brain.js](https://github.com/harthur/brain) ⚠️ Archived - Neural networks in JavaScript.
* [Synaptic.js](https://github.com/cazala/synaptic) ⭐ 6,921 | 🐛 161 | 🌐 JavaScript | 📅 2020-09-03 - Architecture-free neural network library for node.js and the browser.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) ⭐ 2,954 | 🐛 60 | 🌐 Python | 📅 2024-08-03 - A CLI tool to transpile trained classic ML models into a native JavaScript code with zero dependencies.
* [Mind.js](https://github.com/stevenmiller888/mind) ⭐ 1,510 | 🐛 8 | 🌐 JavaScript | 📅 2022-03-16 - A flexible neural network library.
* [JS-PyTorch](https://github.com/eduardoleao052/js-pytorch) ⭐ 1,222 | 🐛 8 | 🌐 JavaScript | 📅 2024-11-15 - GPU accelerated PyTorch in JavaScript.
* [DN2A](https://github.com/dn2a/dn2a-javascript) ⭐ 465 | 🐛 6 | 🌐 TypeScript | 📅 2023-10-07 - Digital Neural Networks Architecture.
* [Synapses](https://github.com/mrdimosthenis/Synapses) ⭐ 73 | 🐛 0 | 📅 2021-09-23 - Lightweight cross-platform Neural Network library.
* [TensorFlow.js](https://www.tensorflow.org/js/) - A JavaScript library for training and deploying ML models in the browser and on Node.js.
* [ml5.js](https://ml5js.org) - Friendly Machine Learning for the Web.

## Browser Detection

* [bowser](https://github.com/ded/bowser) ⭐ 5,712 | 🐛 92 | 🌐 JavaScript | 📅 2026-02-06 - a browser detector.

## Operating System

* [os.js](https://github.com/os-js/OS.js) ⭐ 7,038 | 🐛 20 | 🌐 JavaScript | 📅 2022-12-12 - An open-source web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more.

## Benchmark

* [benchmark.js](https://github.com/bestiejs/benchmark.js) ⚠️ Archived - A benchmarking library. As used on jsPerf.com.
* [bencher](https://github.com/bencherdev/bencher) ⭐ 794 | 🐛 152 | 🌐 MDX | 📅 2026-02-06 - A suite of continuous benchmarking tools designed to catch performance regressions in CI.
* [matcha](https://github.com/logicalparadox/matcha) ⭐ 563 | 🐛 17 | 🌐 JavaScript | 📅 2020-09-04 - A caffeine driven, simplistic approach to benchmarking.

## Web Worker

* [partytown](https://github.com/BuilderIO/partytown) ⭐ 13,633 | 🐛 78 | 🌐 TypeScript | 📅 2025-09-09 - Relocate resource intensive third-party scripts off of the main thread and into a web worker.
* [comlink](https://github.com/GoogleChromeLabs/comlink) ⭐ 12,559 | 🐛 117 | 🌐 TypeScript | 📅 2025-09-30 - Comlink is a tiny library (1.1kB), that removes the mental barrier of thinking about postMessage and hides the fact that you are working with workers.
* [greenlet](https://github.com/developit/greenlet) ⭐ 4,706 | 🐛 15 | 🌐 JavaScript | 📅 2021-03-01 - Move an async function into its own thread.
* [workerize](https://github.com/developit/workerize) ⭐ 4,387 | 🐛 18 | 🌐 JavaScript | 📅 2021-03-04 - Moves a module into a Web Worker, automatically reflecting exported functions as asynchronous proxies.
* [threads.js](https://github.com/andywer/threads.js) ⭐ 3,523 | 🐛 125 | 🌐 TypeScript | 📅 2024-06-19 - Offload CPU-intensive tasks to worker threads in node.js, web browsers and electron using one uniform API.
* [worker-dom](https://github.com/ampproject/worker-dom) ⭐ 3,253 | 🐛 95 | 🌐 TypeScript | 📅 2026-02-06 - An in-progress implementation of the DOM API intended to run within a Web Worker.
* [workerpool](https://github.com/josdejong/workerpool) ⭐ 2,283 | 🐛 34 | 🌐 JavaScript | 📅 2026-02-07 - Offload tasks to a pool of workers on node.js and in the browser.
* [workly](https://github.com/pshihn/workly) ⭐ 1,881 | 🐛 8 | 🌐 JavaScript | 📅 2022-07-20 - A really simple way to move a function or class to a web worker.
* [stockroom](https://github.com/developit/stockroom) ⭐ 1,753 | 🐛 10 | 🌐 JavaScript | 📅 2019-08-06 - Offload your store management to a worker easily.
* [clooney](https://github.com/GoogleChromeLabs/clooney) ⭐ 1,422 | 🐛 37 | 🌐 JavaScript | 📅 2025-12-31 - Clooney is an actor library for the web. Use workers without thinking about workers.

## Code highlighting

* [Highlight.js](https://github.com/isagalaev/highlight.js) ⭐ 24,822 | 🐛 196 | 🌐 JavaScript | 📅 2025-10-27 - JavaScript syntax highlighter.
* [PrismJS](https://github.com/PrismJS/prism) ⭐ 12,919 | 🐛 472 | 🌐 JavaScript | 📅 2026-01-21 - Lightweight, robust, elegant syntax highlighting.
* [shiki](https://github.com/shikijs/shiki) ⭐ 12,878 | 🐛 86 | 🌐 TypeScript | 📅 2026-02-06 - Code highlighter powered by VS Code TextMate grammars. Accurate, themeable, works in Node or browser, great for JS and TS.

## Loading Status

*Libraries for indicate load status.*

* [SpinKit](https://github.com/tobiasahlin/SpinKit) ⭐ 19,386 | 🐛 11 | 🌐 CSS | 📅 2020-08-01 - A collection of loading indicators animated with CSS.
* [pace](https://github.com/HubSpot/pace) ⭐ 15,656 | 🐛 276 | 🌐 CSS | 📅 2024-02-26 - Automatically add a progress bar to your site.
* [Spin.js](https://github.com/fgnass/spin.js) ⭐ 9,295 | 🐛 15 | 🌐 CSS | 📅 2024-07-19 - A spinning activity indicator.
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) ⭐ 7,877 | 🐛 69 | 🌐 JavaScript | 📅 2024-11-02 - Beautiful and responsive progress bars with animated SVG paths.
* [Ladda](https://github.com/hakimel/Ladda) ⭐ 7,808 | 🐛 9 | 🌐 JavaScript | 📅 2021-12-02 - Buttons with built-in loading indicators.
* [css-loaders](https://github.com/lukehaas/css-loaders) ⭐ 7,065 | 🐛 21 | 🌐 CSS | 📅 2025-02-21 - A collection of loading spinners animated with CSS
* [nanobar](https://github.com/jacoborus/nanobar) ⭐ 2,826 | 🐛 14 | 🌐 JavaScript | 📅 2020-03-01 - Very lightweight progress bars. No jQuery.
* [progress.js](https://github.com/usablica/progress.js) ⭐ 2,356 | 🐛 11 | 🌐 JavaScript | 📅 2015-08-31 - Create and manage progress bar for every objects on the page.
* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) ⭐ 1,542 | 🐛 8 | 🌐 JavaScript | 📅 2021-05-15 - Create Google Material Design progress linear bars.
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) ⭐ 645 | 🐛 0 | 🌐 CSS | 📅 2014-04-23 - Modern ways of revealing new content using SVG animations.
* [topbar](https://github.com/buunguyen/topbar) ⭐ 471 | 🐛 5 | 🌐 CSS | 📅 2025-08-04 - Tiny & beautiful site-wide progress indicator.
* [NProgress](https://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.

## Validation

* [validator.js](https://github.com/chriso/validator.js) ⭐ 23,748 | 🐛 369 | 🌐 JavaScript | 📅 2026-02-06 - String validation and sanitization.
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) ⭐ 10,347 | 🐛 42 | 🌐 JavaScript | 📅 2026-01-22 - jQuery Validation Plugin.
* [is.js](https://github.com/arasatasaygin/is.js) ⭐ 9,103 | 🐛 48 | 🌐 JavaScript | 📅 2022-01-11 - Check types, regexps, presence, time and more.
* [Parsley.js](https://github.com/guillaumepotier/Parsley.js) ⭐ 9,005 | 🐛 72 | 🌐 JavaScript | 📅 2023-04-14 - Validate your forms, frontend, without writing a single line of JavaScript.
* [vest](https://github.com/ealush/vest) ⭐ 2,631 | 🐛 30 | 🌐 TypeScript | 📅 2026-02-07 - 🦺 Declarative form validation framework inspired by unit testing.
* [validate.js](https://github.com/rickharrison/validate.js) ⭐ 2,558 | 🐛 32 | 🌐 JavaScript | 📅 2020-03-02 - Lightweight JavaScript form validation library inspired by CodeIgniter.
* [Funval](https://github.com/neuledge/funval) ⭐ 360 | 🐛 7 | 🌐 TypeScript | 📅 2026-01-29 - Data validation using functions interfaces (support TypeScript).
* [validatr](https://github.com/jaymorrow/validatr/) ⭐ 277 | 🐛 18 | 🌐 JavaScript | 📅 2020-09-05 - Cross Browser HTML5 Form Validation.
* [FieldVal](https://github.com/FieldVal/fieldval-js) ⭐ 135 | 🐛 3 | 🌐 JavaScript | 📅 2020-09-06 - multipurpose validation library. Supports both sync and async validation.
* [FormValidation](https://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.

## Keyboard Wrappers

* [mousetrap](https://github.com/ccampbell/mousetrap) ⭐ 11,800 | 🐛 237 | 🌐 JavaScript | 📅 2023-03-15 - Simple library for handling keyboard shortcuts in JavaScript.
* [keymaster](https://github.com/madrobby/keymaster) ⭐ 6,522 | 🐛 82 | 🌐 JavaScript | 📅 2024-07-29 - A simple micro-library for defining and dispatching keyboard shortcuts.
* [Keypress](https://github.com/dmauro/Keypress) ⭐ 3,162 | 🐛 35 | 🌐 CoffeeScript | 📅 2020-09-06 - A keyboard input capturing utility in which any key can be a modifier key.
* [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) ⭐ 2,555 | 🐛 2 | 🌐 JavaScript | 📅 2021-10-22 - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) ⭐ 2,112 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-19 - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [jwerty](https://github.com/keithamus/jwerty) ⚠️ Archived - Awesome handling of keyboard events.

## Tours And Guides

* [driver.js](https://github.com/kamranahmedse/driver.js) ⭐ 25,322 | 🐛 112 | 🌐 TypeScript | 📅 2025-11-18 - Powerful yet light-weight, vanilla JavaScript engine to drive the user's focus across the page
* [intro.js](https://github.com/usablica/intro.js) ⭐ 23,893 | 🐛 71 | 🌐 TypeScript | 📅 2026-01-04 - A better way for new feature introduction and step-by-step users guide for your website and project.
* [shepherd](https://github.com/HubSpot/shepherd) ⭐ 13,641 | 🐛 50 | 🌐 JavaScript | 📅 2026-02-06 - Guide your users through a tour of your app.
* [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) ⭐ 4,427 | 🐛 194 | 🌐 CoffeeScript | 📅 2023-10-09 - Quick and easy product tours with Twitter Bootstrap Popovers.
* [hopscotch](https://github.com/linkedin/hopscotch) ⚠️ Archived - A framework to make it easy for developers to add product tours to their pages.
* [joyride](https://github.com/zurb/joyride) ⭐ 1,419 | 🐛 128 | 🌐 JavaScript | 📅 2020-09-08 - jQuery feature tour plugin.
* [tourist](https://github.com/easelinc/tourist) ⚠️ Archived - Simple, flexible tours for your app.
* [focusable](https://github.com/zzarcon/focusable) ⭐ 1,064 | 🐛 6 | 🌐 JavaScript | 📅 2016-03-03 - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page.

## Notifications

* [notifire](https://github.com/notifirehq/notifire) ⭐ 38,519 | 🐛 151 | 🌐 TypeScript | 📅 2026-02-06 - Open-source notification infrastructure for products.
* [toastr](https://github.com/CodeSeven/toastr) ⭐ 12,122 | 🐛 156 | 🌐 JavaScript | 📅 2023-02-27 - Simple JavaScript toast notifications.
* [noty](https://github.com/needim/noty) ⭐ 6,649 | 🐛 51 | 🌐 JavaScript | 📅 2024-04-04 - jQuery notification plugin.
* [notie](https://github.com/jaredreich/notie) ⭐ 6,290 | 🐛 20 | 🌐 JavaScript | 📅 2023-05-04 - Simple notifications and inputs with no dependencies.
* [messenger](https://github.com/HubSpot/messenger) ⭐ 4,011 | 🐛 53 | 🌐 JavaScript | 📅 2020-09-07 - Growl-style alerts and messages for your app.
* [pnotify](https://github.com/sciactive/pnotify) ⭐ 3,642 | 🐛 49 | 🌐 HTML | 📅 2022-11-20 - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* [iziToast](https://github.com/dolce/iziToast) ⭐ 2,676 | 🐛 52 | 🌐 JavaScript | 📅 2024-08-07 - Elegant, responsive, flexible and lightweight notification plugin with no dependencies.
* [toastify-js](https://github.com/apvarun/toastify-js) ⭐ 2,498 | 🐛 50 | 🌐 JavaScript | 📅 2024-08-19 - Pure JavaScript library for better notification messages.
* [humane-js](https://github.com/wavded/humane-js) ⭐ 2,162 | 🐛 12 | 🌐 CSS | 📅 2025-11-14 - A simple, modern, browser notification system.
* [smoke.js](https://github.com/hxgf/smoke.js) ⭐ 925 | 🐛 21 | 🌐 JavaScript | 📅 2020-04-22 - Framework-agnostic styled alert system for JavaScript.

## Sliders

* [reveal.js](https://github.com/hakimel/reveal.js) ⭐ 70,526 | 🐛 883 | 🌐 JavaScript | 📅 2026-02-02 - A framework for easily creating beautiful presentations using HTML.
* [Swiper](https://github.com/nolimits4web/Swiper) ⭐ 41,779 | 🐛 252 | 🌐 JavaScript | 📅 2026-01-28 - Mobile touch slider and framework with hardware accelerated transitions.
* [impress.js](https://github.com/impress/impress.js) ⭐ 38,588 | 🐛 59 | 🌐 JavaScript | 📅 2026-01-24 - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* [slick](https://github.com/kenwheeler/slick) ⭐ 28,616 | 🐛 1,350 | 🌐 JavaScript | 📅 2026-01-28 - The last carousel you'll ever need.
* [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) ⭐ 25,065 | 🐛 162 | 🌐 JavaScript | 📅 2025-12-04 - JavaScript image gallery for mobile and desktop, modular, framework independent.
* [Embla Carousel](https://github.com/davidcetinkaya/embla-carousel) ⭐ 8,011 | 🐛 15 | 🌐 TypeScript | 📅 2026-02-07 - An extensible low level carousel for the web, written in TypeScript.
* [Glide.js](https://github.com/jedrzejchalubek/glidejs) ⭐ 7,677 | 🐛 246 | 🌐 JavaScript | 📅 2024-11-22 - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast.
* [Flickity](https://github.com/metafizzy/flickity) ⭐ 7,591 | 🐛 123 | 🌐 JavaScript | 📅 2024-05-29 - Touch, responsive, flickable galleries.
* [FlexSlider](https://github.com/woothemes/FlexSlider) ⚠️ Archived - An awesome, fully responsive jQuery slider plugin.
* [bespoke.js](https://github.com/bespokejs/bespoke) ⭐ 4,808 | 🐛 5 | 🌐 JavaScript | 📅 2020-09-08 - DIY Presentation Micro-Framework
* [Sequence](https://github.com/IanLunn/Sequence) ⭐ 3,335 | 🐛 38 | 🌐 JavaScript | 📅 2020-09-10 - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* [sly](https://github.com/darsain/sly) ⭐ 2,853 | 🐛 81 | 🌐 JavaScript | 📅 2020-09-07 - JavaScript library for one-directional scrolling with item based navigation support.
* [Strut](https://github.com/tantaman/Strut) ⭐ 1,886 | 🐛 16 | 🌐 TypeScript | 📅 2023-12-16 - Strut - An Impress.js and Bespoke.js Presentation Editor
* [vegas](https://github.com/jaysalvat/vegas) ⭐ 1,795 | 🐛 20 | 🌐 JavaScript | 📅 2024-07-30 - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* [slidr](https://github.com/bchanx/slidr) ⭐ 1,551 | 🐛 24 | 🌐 JavaScript | 📅 2020-09-18 - add some slide effects.
* [basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) ⭐ 541 | 🐛 52 | 🌐 JavaScript | 📅 2021-10-20 - Simple to use, simple to theme, simple to customise.
* [jcSlider](https://github.com/JoanClaret/jcSlider) ⭐ 63 | 🐛 2 | 🌐 HTML | 📅 2015-12-06 - A responsive slider jQuery plugin with CSS animations.
* [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) ⭐ 55 | 🐛 0 | 🌐 JavaScript | 📅 2014-04-07 - A jQuery plugin for a slider with adaptive colored figcaption and navigation.
* [slidesJs](http://www.slidesjs.com) - Is a responsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions

## Range Sliders

* [noUiSlider](https://github.com/leongersen/noUiSlider) ⭐ 5,799 | 🐛 49 | 🌐 TypeScript | 📅 2024-11-26 - A lightweight, highly customizable range slider without bloat.
* [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) ⭐ 2,556 | 🐛 139 | 🌐 JavaScript | 📅 2023-03-24 - Powerful and easily customizable range slider with many options and skin support.
* [rangeslider.js](https://github.com/andreruffert/rangeslider.js) ⚠️ Archived - HTML5 input range slider element polyfill.
* [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) ⭐ 669 | 🐛 80 | 🌐 JavaScript | 📅 2024-04-28 - A JavaScript slider selector that supports dates.

## Form Widgets

### Input

* [typeahead.js](https://github.com/twitter/typeahead.js) ⭐ 16,495 | 🐛 507 | 🌐 JavaScript | 📅 2023-04-14 - A fast and fully-featured autocomplete library.
* [awesomplete](https://github.com/LeaVerou/awesomplete) ⭐ 6,986 | 🐛 186 | 🌐 JavaScript | 📅 2024-07-25 - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - <https://projects.verou.me/awesomplete/>
* [At.js](https://github.com/ichord/At.js) ⭐ 5,265 | 🐛 158 | 🌐 CoffeeScript | 📅 2021-11-18 - Add GitHub like mentions autocomplete to your application.
* [tag-it](https://github.com/aehlke/tag-it) ⭐ 2,465 | 🐛 249 | 🌐 JavaScript | 📅 2023-08-28 - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) ⚠️ Archived - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* [fancyInput](https://github.com/yairEO/fancyInput) ⚠️ Archived - Makes typing in input fields fun with CSS3 effects.
* [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) ⭐ 946 | 🐛 37 | 🌐 JavaScript | 📅 2023-01-14 - A JavaScript polyfill for the HTML5 placeholder attribute.
* [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) ⚠️ Archived - jQuery plugin for styling checkboxes and radio-buttons. With skin support.
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-10 - A pure JavaScript mask input.

### Calendar

* [fullcalendar](https://github.com/fullcalendar/fullcalendar) ⭐ 20,324 | 🐛 1,084 | 🌐 TypeScript | 📅 2025-12-23 - Full-sized drag & drop event calendar (jQuery plugin).
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) ⭐ 12,669 | 🐛 882 | 🌐 JavaScript | 📅 2025-09-15 - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* [tui.calendar](https://github.com/nhn/tui.calendar) ⭐ 12,633 | 🐛 208 | 🌐 TypeScript | 📅 2024-06-24 - A JavaScript schedule calendar that is full featured. Now your service just got the customizable calendar.
* [Date Range Picker](https://github.com/dangrossman/daterangepicker) ⭐ 11,006 | 🐛 122 | 🌐 JavaScript | 📅 2024-08-09 - creates a dropdown menu from which a user can select a range of dates.
* [Pikaday](https://github.com/dbushell/Pikaday) ⚠️ Archived - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* [pickadate.js](https://github.com/amsul/pickadate.js) ⭐ 7,685 | 🐛 313 | 🌐 JavaScript | 📅 2023-07-14 - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [rome](https://github.com/bevacqua/rome) ⭐ 2,909 | 🐛 86 | 🌐 JavaScript | 📅 2024-03-16 - A customizable date (and time) picker. Dependency free, opt-in UI.
* [Schedule-X](https://github.com/schedule-x/schedule-x) ⭐ 2,163 | 🐛 53 | 🌐 TypeScript | 📅 2026-02-05 - Material design event calendar. Features drag & drop, dark mode, multiple views and more.
* [Duet Date Picker](https://github.com/duetds/date-picker) ⚠️ Archived - open source version of Duet Design System’s accessible date picker, WCAG 2.1 accessibility complaint

### Select

* [select2](https://github.com/select2/select2) ⭐ 25,978 | 🐛 169 | 🌐 JavaScript | 📅 2024-09-11 - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* [chosen](https://github.com/harvesthq/chosen) ⭐ 22,342 | 🐛 311 | 🌐 HTML | 📅 2024-12-02 - A library for making long, unwieldy select boxes more friendly.
* [selectize.js](https://github.com/selectize/selectize.js) ⭐ 13,059 | 🐛 49 | 🌐 SCSS | 📅 2026-02-06 - Selectize is the hybrid of a textbox and `<select>` box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc.

### File Uploader

* [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) ⚠️ Archived - File Upload widget with multiple file selection, drag\&drop support, progress bar, validation and preview images, audio and video for jQuery.
* [dropzone](https://github.com/enyo/dropzone) ⭐ 18,395 | 🐛 151 | 🌐 JavaScript | 📅 2024-07-15 - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [filepond](https://github.com/pqina/filepond) ⭐ 16,302 | 🐛 138 | 🌐 JavaScript | 📅 2026-02-03 - A JavaScript library that can upload anything you throw at it, optimizes images for faster uploads, and offers a great, accessible, silky smooth user experience.
* [fine-uploader](https://github.com/FineUploader/fine-uploader) ⚠️ Archived - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* [plupload](https://github.com/moxiecode/plupload) ⭐ 5,626 | 🐛 207 | 🌐 JavaScript | 📅 2024-07-18 - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.
* [FileAPI](https://github.com/mailru/FileAPI) ⭐ 3,562 | 🐛 50 | 🌐 JavaScript | 📅 2020-09-24 - A set of JavaScript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [flow.js](https://github.com/flowjs/flow.js) ⭐ 2,994 | 🐛 134 | 🌐 JavaScript | 📅 2025-01-09 - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.

### Other

* [card](https://github.com/jessepollak/card) ⭐ 11,724 | 🐛 66 | 🌐 SCSS | 📅 2023-06-12 - Make your credit card form better in one line of code.
* [dat.GUI](https://github.com/dataarts/dat.gui) ⭐ 7,723 | 🐛 121 | 🌐 JavaScript | 📅 2026-01-24 - A lightweight gui controller for changing variables in JavaScript.
* [form](https://github.com/jquery-form/form) ⭐ 5,175 | 🐛 35 | 🌐 JavaScript | 📅 2024-01-10 - jQuery Form Plugin.
* [analytics](https://github.com/davidwells/analytics) ⭐ 2,635 | 🐛 113 | 🌐 JavaScript | 📅 2025-09-03 - A lightweight, extendable analytics library designed to work with any third-party analytics provider to track page views, custom events, & identify users.
* [Garlic.js](https://github.com/guillaumepotier/Garlic.js) ⭐ 2,351 | 🐛 64 | 🌐 CSS | 📅 2021-11-03 - Automatically persist your forms' text and select field values locally, until the form is submitted.
* [Countable](https://github.com/RadLikeWhoa/Countable) ⭐ 1,645 | 🐛 10 | 🌐 JavaScript | 📅 2022-02-11 - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* [stretchy](https://github.com/LeaVerou/stretchy) ⭐ 1,274 | 🐛 18 | 🌐 JavaScript | 📅 2023-12-15 - Form element autosizing, the way it should be.

## Tips

* [hint.css](https://github.com/chinchang/hint.css) ⭐ 8,461 | 🐛 54 | 🌐 CSS | 📅 2024-10-17 - A tooltip library in CSS for your lovely websites.
* [tooltipster](https://github.com/iamceege/tooltipster) ⭐ 2,745 | 🐛 33 | 🌐 JavaScript | 📅 2020-09-18 - A jQuery tooltip plugin.
* [toolbar](https://github.com/paulkinzett/toolbar) ⭐ 2,280 | 🐛 28 | 🌐 JavaScript | 📅 2017-01-20 - A tooltip style toolbar jQuery plugin
* [tipsy](https://github.com/jaz303/tipsy) ⭐ 2,001 | 🐛 120 | 🌐 JavaScript | 📅 2022-05-23 - Facebook-style tooltips plugin for jQuery.
* [qTip2](https://github.com/qTip2/qTip2) ⚠️ Archived - Pretty powerful tooltips.
* [opentip](https://github.com/enyo/opentip) ⭐ 1,246 | 🐛 72 | 🌐 JavaScript | 📅 2020-09-18 - An open source JavaScript tooltip based on the prototype framework.
* [simptip](https://github.com/arashmanteghi/simptip) ⭐ 643 | 🐛 3 | 🌐 CSS | 📅 2018-03-06 - A simple CSS tooltip made with Sass.

## Modals and Popups

* [SweetAlert](https://github.com/t4t5/sweetalert) ⭐ 22,356 | 🐛 197 | 🌐 TypeScript | 📅 2023-04-15 - An awesome replacement for JavaScript's alert.
* [SweetAlert2](https://github.com/sweetalert2/sweetalert2) ⭐ 18,028 | 🐛 8 | 🌐 JavaScript | 📅 2026-02-02 - An awesome replacement for JavaScript's alert.
* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) ⭐ 11,367 | 🐛 678 | 🌐 JavaScript | 📅 2024-06-08 - Light and responsive lightbox script with focus on performance.
* [fancyBox](https://github.com/fancyapps/fancyBox) ⚠️ Archived - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* [screenfull.js](https://github.com/sindresorhus/screenfull.js) ⭐ 7,153 | 🐛 14 | 🌐 HTML | 📅 2022-07-08 - the JavaScript Fullscreen API, which lets you bring the page or any element into fullscreen. Smoothens out the browser implementation differences, so you don't have to.
* [lightGallery](https://github.com/sachinchoolur/lightGallery) ⭐ 6,970 | 🐛 60 | 🌐 TypeScript | 📅 2026-01-06 - A customizable, modular, responsive, lightbox gallery plugin for jQuery.
* [vex](https://github.com/HubSpot/vex) ⭐ 6,911 | 🐛 55 | 🌐 CSS | 📅 2023-02-26 - A modern dialog library which is highly configurable and easy to style.
* [bootstrap-modal](https://github.com/jschr/bootstrap-modal) ⭐ 4,973 | 🐛 110 | 🌐 JavaScript | 📅 2019-04-07 - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* [colorbox](https://github.com/jackmoore/colorbox) ⚠️ Archived - A light-weight, customizable lightbox plugin for jQuery.
* [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) ⭐ 2,498 | 🐛 54 | 🌐 JavaScript | 📅 2025-11-09 - Simple and easy to use lightbox script written in pure JavaScript.
* [swipebox](https://github.com/brutaldesign/swipebox) ⭐ 1,949 | 🐛 187 | 🌐 JavaScript | 📅 2024-01-21 - A touchable jQuery lightbox
* [css-modal](https://github.com/drublic/css-modal) ⭐ 1,816 | 🐛 29 | 🌐 JavaScript | 📅 2022-12-03 - A modal built out of pure CSS.
* [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) ⭐ 1,747 | 🐛 18 | 🌐 JavaScript | 📅 2020-09-18 - A jQuery plugin with new modal concept for popups.
* [jBox](https://github.com/StephanWagner/jBox) ⚠️ Archived - jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more.
* [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) ⭐ 504 | 🐛 41 | 🌐 HTML | 📅 2022-12-08 - jQuery plugin for responsive and accessible modal windows and tooltips.
* [jquery-popbox](https://github.com/gristmill/jquery-popbox) ⭐ 418 | 🐛 15 | 🌐 JavaScript | 📅 2018-10-01 - jQuery PopBox UI Element.
* [keukenhof](https://github.com/Alexandrshy/keukenhof) ⭐ 19 | 🐛 26 | 🌐 TypeScript | 📅 2023-08-21 - Lightweight, no dependencies, accessibility enabled TypeScript library for creating modal windows.

## Scroll

* [fullPage](https://github.com/alvarotrigo/fullPage.js) ⭐ 35,494 | 🐛 127 | 🌐 JavaScript | 📅 2026-01-22 - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites).
* [skrollr](https://github.com/Prinzhorn/skrollr) ⚠️ Archived - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* [parallax](https://github.com/wagerfield/parallax) ⭐ 16,603 | 🐛 11 | 🌐 JavaScript | 📅 2024-04-06 - Parallax Engine that reacts to the orientation of a smart device.
* [iscroll](https://github.com/cubiq/iscroll) ⚠️ Archived - iScroll is a high performance, small footprint, dependency free, multi-platform JavaScript scroller.
* [headroom](https://github.com/WickyNilliams/headroom.js) ⭐ 10,851 | 🐛 20 | 🌐 JavaScript | 📅 2023-10-25 - Give your pages some headroom. Hide your header until you need it.
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) ⭐ 9,491 | 🐛 266 | 🌐 JavaScript | 📅 2021-01-08 - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* [locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) ⭐ 8,679 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-02 - Detects the elements in viewport and smooth scrolling with parallax.
* [Clusterize.js](https://github.com/NeXTs/Clusterize.js) ⭐ 7,294 | 🐛 56 | 🌐 JavaScript | 📅 2025-05-04 - Tiny vanilla JS plugin to display large data sets easily.
* [rellax](https://github.com/dixonandmoe/rellax) ⭐ 7,164 | 🐛 75 | 🌐 HTML | 📅 2024-08-24 - Buttery smooth, super lightweight, vanilla javascript parallax library.
* [elevator.js](https://github.com/tholman/elevator.js) ⭐ 6,635 | 🐛 19 | 🌐 JavaScript | 📅 2020-06-26 - Finally, a "back to top" button that behaves like a real elevator.
* [stellar.js](https://github.com/markdalgleish/stellar.js) ⭐ 4,612 | 🐛 91 | 🌐 JavaScript | 📅 2022-05-13 - Parallax scrolling made easy.
* [stroll](https://github.com/hakimel/stroll.js) ⭐ 4,346 | 🐛 14 | 🌐 HTML | 📅 2020-07-24 - A collection of CSS List scroll effects bind to dom through javascript.
* [scrollMonitor](https://github.com/stutrek/scrollMonitor) ⭐ 3,290 | 🐛 21 | 🌐 TypeScript | 📅 2023-07-17 - A simple and fast API to monitor elements as you scroll.
* [plax](https://github.com/cameronmcefee/plax) ⭐ 2,264 | 🐛 18 | 🌐 JavaScript | 📅 2017-09-15 - jQuery powered parallaxing.
* [simpleParallax](https://github.com/geosigno/simpleParallax) ⭐ 2,113 | 🐛 18 | 🌐 TypeScript | 📅 2025-09-21 - Simple and tiny JavaScript library to add parallax animations on any images
* [jparallax](https://github.com/stephband/jparallax) ⭐ 1,141 | 🐛 53 | 🌐 HTML | 📅 2023-12-20 - jQuery plugin for creating interactive parallax effect.
* [asscroll](https://github.com/ashthornton/asscroll) ⚠️ Archived - A hybrid smooth scroll setup that combines the performance gains of virtual scroll with the reliability of native scroll.
* [ScrollMenu](https://github.com/s-yadav/ScrollMenu) ⭐ 203 | 🐛 2 | 🌐 JavaScript | 📅 2021-09-23 - A new interface to replace old boring scrollbar.

## Menu

* [Slideout](https://github.com/mango/slideout) ⭐ 7,903 | 🐛 72 | 🌐 JavaScript | 📅 2020-09-20 - A responsive touch slideout navigation menu for mobile web apps.
* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) ⭐ 7,653 | 🐛 66 | 🌐 JavaScript | 📅 2018-11-01 - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* [mmenu](https://github.com/FrDH/jQuery.mmenu) ⭐ 2,582 | 🐛 30 | 🌐 TypeScript | 📅 2023-03-15 - The best jQuery plugin for app look-alike on- and off-canvas menus with sliding submenus for your website and webapp.
* [jQuery contextMenu](https://github.com/swisnl/jQuery-contextMenu) ⭐ 2,249 | 🐛 136 | 🌐 HTML | 📅 2025-11-04 - contextMenu manager.
* [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) ⭐ 138 | 🐛 6 | 🌐 JavaScript | 📅 2018-02-22 - A sliding swipe menu that works with touchSwipe library.

## Table/Grid

* [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) ⭐ 9,360 | 🐛 62 | 🌐 HTML | 📅 2020-10-01 - Grid based on CSS3 flexbox.
* [floatThead](https://github.com/mkoryak/floatThead) ⭐ 1,212 | 🐛 3 | 🌐 JavaScript | 📅 2023-03-10 - (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css.
* [jTable](https://github.com/hikalkan/jtable) ⭐ 1,091 | 🐛 1,505 | 🌐 JavaScript | 📅 2021-11-19 - A jQuery plugin to create AJAX based CRUD tables.
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [Tabulator](http://olifolkerd.github.io/tabulator/) - (jQuery plug-in) An extremely flexible library that create tables with a range of interactive features from any JSON data source or existing HTML table.
* [Bootstrap Table](https://bootstrap-table.com/) - An Extension to the popular Bootstrap framework for creating tables that fit the style of your site with no need for additional markup.
* [Masonry](https://masonry.desandro.com/) - A cascading grid layout library.
* [Packery](https://packery.metafizzy.co/) - A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts.
* [Isotope](https://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.

## Frameworks

* [fluidity](https://github.com/mrmrs/fluidity) ⭐ 1,099 | 🐛 10 | 🌐 JavaScript | 📅 2018-12-27 - The worlds smallest fully-responsive css framework.
* [EHTML](https://github.com/Guseyn/EHTML) ⭐ 290 | 🐛 6 | 🌐 JavaScript | 📅 2026-01-05 - HTML Framework that allows you not to write JavaScript code.
* [DataFormsJS](https://github.com/dataformsjs/dataformsjs) ⭐ 197 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-31 - A minimal JavaScript Framework and standalone components for rapid development of sites and SPA's.
* [Semantic UI](https://semantic-ui.com/) - UI Kit with lots of themes and elements.
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* [Ink](https://github.com/sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping.

## Boilerplates

* [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) ⭐ 57,388 | 🐛 19 | 🌐 JavaScript | 📅 2026-02-06 - A professional front-end template for building fast, robust, and adaptable web apps or sites.
* [Wasp](https://github.com/wasp-lang/wasp) ⭐ 18,122 | 🐛 807 | 🌐 TypeScript | 📅 2026-02-06 Wasp is a declarative domain-specific language for developing, building, and deploying modern Javascript full-stack web apps with less code.
* [Cerberus](https://github.com/TedGoas/Cerberus) ⭐ 5,114 | 🐛 13 | 🌐 HTML | 📅 2024-07-16 - A few simple, but solid patterns for responsive HTML emails. Even in Outlook.
* [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) ⚠️ Archived - A front-end template that helps you build fast, modern mobile web apps.
* [this-is-responsive](https://github.com/bradfrost/this-is-responsive) ⭐ 1,576 | 🐛 13 | 🌐 HTML | 📅 2023-04-16 - This Is Responsive.
* [webplate](https://github.com/chrishumboldt/webplate) ⚠️ Archived - An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use.
* [Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) ⭐ 70 | 🐛 0 | 🌐 JavaScript | 📅 2019-10-26 - An example of a mobile-first responsive web design.
* [full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) ⭐ 47 | 🐛 1 | 🌐 JavaScript | 📅 2020-09-20 - An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation.
* [Fluid-Squares](https://github.com/crozynski/Fluid-Squares) ⭐ 32 | 🐛 1 | 🌐 HTML | 📅 2015-06-08 - A fluid grid of square units.
* [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) Task automation with NPM run-scripts.

## Images

* [Panolens.js](https://github.com/pchen66/panolens.js) ⚠️ Archived - Panolens.js is an event-driven and WebGL based panorama viewer. Lightweight and flexible
* [Drift](https://github.com/imgix/drift) ⭐ 1,570 | 🐛 16 | 🌐 JavaScript | 📅 2024-06-28 - Easily add "zoom on hover" functionality to your site's images. Lightweight, no-dependency JavaScript.
* [Magnificent.js](https://github.com/AndersDJohnson/magnificent.js) ⭐ 168 | 🐛 27 | 🌐 JavaScript | 📅 2023-01-12 - Zoom responsively, images & more, w/ jQuery.

## Gesture

* [hammer.js](https://github.com/hammerjs/hammer.js) ⭐ 24,388 | 🐛 318 | 🌐 JavaScript | 📅 2026-01-04 - A JavaScript library for multi-touch gestures.
* [Dragula](https://github.com/bevacqua/dragula/) ⭐ 22,202 | 🐛 160 | 🌐 JavaScript | 📅 2024-06-07 - Drag and drop so simple it hurts.
* [touchemulator](https://github.com/hammerjs/touchemulator) ⭐ 404 | 🐛 17 | 🌐 JavaScript | 📅 2022-11-17 - Emulate touch input on your desktop.

## Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) ⭐ 44,467 | 🐛 539 | 🌐 JavaScript | 📅 2026-02-02 - JavaScript library for mobile-friendly interactive maps.
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) ⭐ 14,807 | 🐛 1,562 | 🌐 JavaScript | 📅 2026-02-06 - Open Source WebGL virtual globe and map engine.
* [gmaps](https://github.com/HPNeo/gmaps) ⚠️ Archived - The easiest way to use Google Maps.
* [H3js](https://github.com/uber/h3) ⭐ 5,970 | 🐛 147 | 🌐 C | 📅 2026-02-07 - Hexagonal hierarchical geospatial indexing system ported to javascript by Uber for geospatial visualization.
* [mapbox.js](https://github.com/mapbox/mapbox.js) ⚠️ Archived - Mapbox JavaScript API, a Leaflet Plugin.
* [jqvmap](https://github.com/manifestinteractive/jqvmap) ⭐ 1,820 | 🐛 104 | 🌐 JavaScript | 📅 2021-03-28 - jQuery Vector Map Library.
* [polymaps](https://github.com/simplegeo/polymaps) ⭐ 1,605 | 🐛 69 | 🌐 JavaScript | 📅 2023-07-26 - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* [kartograph.js](https://github.com/kartograph/kartograph.js) ⭐ 1,504 | 🐛 35 | 🌐 CoffeeScript | 📅 2018-05-12 - Open source JavaScript renderer for Kartograph SVG maps.
* [OpenLayers3](https://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.

## Video/Audio

* [video.js](https://github.com/videojs/video.js) ⭐ 39,480 | 🐛 632 | 🌐 JavaScript | 📅 2026-02-05 - Video.js - open source HTML5 & Flash video player.
* [flv.js](https://github.com/bilibili/flv.js) ⭐ 23,258 | 🐛 449 | 🌐 JavaScript | 📅 2024-07-07 - An HTML5 Flash Video (FLV) Player written in pure JavaScript without Flash.
* [hls.js](https://github.com/video-dev/hls.js) ⭐ 16,466 | 🐛 166 | 🌐 TypeScript | 📅 2026-02-07 -  A JavaScript library that implements an HTTP Live Streaming client. It relies on HTML5 video and MediaSource Extensions for playback.
* [mediaelement](https://github.com/johndyer/mediaelement) ⭐ 8,303 | 🐛 224 | 🌐 JavaScript | 📅 2025-11-12 - HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://www.mediaelementjs.com/>
* [clappr](https://github.com/clappr/clappr) ⭐ 7,409 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-05 - An extensible media player for the web <http://clappr.io>
* [FitVids.js](https://github.com/davatron5000/FitVids.js) ⭐ 4,740 | 🐛 37 | 🌐 HTML | 📅 2022-05-06 - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
* [SoundJS](https://github.com/CreateJS/SoundJS) ⭐ 4,554 | 🐛 95 | 🌐 JavaScript | 📅 2021-03-27 - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers.
* [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) ⭐ 3,451 | 🐛 82 | 🌐 JavaScript | 📅 2023-11-04 - FFmpeg optimized for in-browser use: minimal size for faster loading, asm.js, performance tunings, etc.
* [flowplayer](https://github.com/flowplayer/flowplayer) ⚠️ Archived - The HTML5 video player for the web
  <https://flowplayer.com/>
* [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) ⭐ 1,059 | 🐛 12 | 🌐 JavaScript | 📅 2016-08-29 - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.
* [ractive-player](https://github.com/ysulyma/ractive-player) ⭐ 808 | 🐛 17 | 🌐 TypeScript | 📅 2025-12-18 - A library for making interactive videos in React.js.
* [Ion.Sound](https://github.com/IonDen/ion.sound) ⭐ 712 | 🐛 43 | 🌐 JavaScript | 📅 2020-03-06 - Simple sounds on any web page.
* [photobooth-js](https://github.com/WolframHempel/photobooth-js) ⭐ 577 | 🐛 23 | 🌐 JavaScript | 📅 2020-09-22 - A widget that allows users to take their avatar pictures on your site.
* [ts-audio](https://github.com/EvandroLG/ts-audio) ⭐ 341 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-18 - an agnostic and easy-to-use library to work with the `AudioContext` API.
* [Play-em JS](https://github.com/adrienjoly/playemjs) ⭐ 101 | 🐛 19 | 🌐 JavaScript | 📅 2024-12-07 - Play'em is a JavaScript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo.
* [polyplayer](https://github.com/Acconut/polyplayer) ⭐ 41 | 🐛 1 | 🌐 JavaScript | 📅 2020-09-22 - Rule YouTube, Soundcloud and Vimeo player with one API.
* [AmplitudeJS](https://521dimensions.com/open-source/amplitudejs) - Open Source HTML5 Web Audio Library. Design your web audio player, the way you want. No dependencies required.

## Typography

* [FitText.js](https://github.com/davatron5000/FitText.js) ⭐ 6,734 | 🐛 27 | 🌐 HTML | 📅 2020-12-02 - A jQuery plugin for inflating web type.
* [Lettering.js](https://github.com/davatron5000/Lettering.js) ⭐ 5,360 | 🐛 16 | 🌐 JavaScript | 📅 2020-07-27 - A lightweight, easy to use JavaScript `<span>` injector for radical Web Typography.
* [FlowType.JS](https://github.com/simplefocus/FlowType.JS) ⭐ 4,585 | 🐛 37 | 🌐 JavaScript | 📅 2021-07-28 - Web typography at its finest: font-size and line-height based on element width.
* [slabText](https://github.com/freqDec/slabText/) ⭐ 1,333 | 🐛 6 | 🌐 HTML | 📅 2018-10-19 - A jQuery plugin for producing big, bold & responsive headlines.
* [BigText](https://github.com/zachleat/BigText) ⭐ 888 | 🐛 35 | 🌐 JavaScript | 📅 2025-06-06 - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width.
* [simple-text-rotator](https://github.com/peachananr/simple-text-rotator) ⭐ 747 | 🐛 29 | 🌐 HTML | 📅 2020-10-02 - Add a super simple rotating text to your website with little to no markup.
* [circletype](https://github.com/peterhry/circletype) ⭐ 702 | 🐛 14 | 🌐 JavaScript | 📅 2026-01-20 - A jQuery plugin that lets you curve type on the web.
* [novacancy.js](https://github.com/chuckyglitch/novacancy.js) ⭐ 189 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-11 - Text Neon Golden effect jQuery plug-in.
* [jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) ⚠️ Archived - Make your text sizing responsive!

## Animations

* [animate.css](https://github.com/daneden/animate.css) ⭐ 82,637 | 🐛 73 | 🌐 CSS | 📅 2024-07-29 - A cross-browser library of CSS animations. As easy to use as an easy thing.
* [particles.js](https://github.com/VincentGarreau/particles.js) ⭐ 30,371 | 🐛 366 | 🌐 JavaScript | 📅 2024-03-28 - A lightweight JavaScript library for creating particles.
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) ⭐ 23,766 | 🐛 9 | 🌐 JavaScript | 📅 2025-12-12 - High-performance HTML5 animations that work in all major browsers.
* [velocity](https://github.com/julianshapiro/velocity) ⭐ 17,252 | 🐛 41 | 🌐 JavaScript | 📅 2020-10-24 - Accelerated JavaScript animation.
* [barbajs](https://github.com/barbajs/barba) ⭐ 12,869 | 🐛 13 | 🌐 TypeScript | 📅 2024-12-02 - It helps you create fluid and smooth transitions between your website's pages.
* [Effeckt.css](https://github.com/h5bp/Effeckt.css) ⚠️ Archived - A Performant Transitions and Animations Library.
* [tsParticles](https://github.com/matteobruni/tsparticles) ⭐ 8,682 | 🐛 17 | 🌐 TypeScript | 📅 2026-02-07 - A new and improved version of particles.js with bug fixes and many new features.
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) ⭐ 7,571 | 🐛 9 | 🌐 CoffeeScript | 📅 2019-02-26 - JavaScript library to create physics-based CSS animations.
* [jquery.transit](https://github.com/rstacruz/jquery.transit) ⭐ 7,258 | 🐛 136 | 🌐 JavaScript | 📅 2022-01-18 - Super-smooth CSS3 transformations and transitions for jQuery.
* [bounce.js](https://github.com/tictail/bounce.js) ⭐ 6,183 | 🐛 12 | 🌐 CSS | 📅 2020-09-03 - Create tasty CSS3 powered animations in no time.
* [move.js](https://github.com/visionmedia/move.js) ⭐ 4,709 | 🐛 36 | 🌐 JavaScript | 📅 2022-03-11 - CSS3 backed JavaScript animation framework.
* [smoothState.js](https://github.com/miguel-perez/smoothState.js) ⭐ 4,397 | 🐛 127 | 🌐 CSS | 📅 2021-11-23 - Unobtrusive page transitions with jQuery.
* [textillate](https://github.com/jschr/textillate) ⭐ 3,675 | 🐛 69 | 🌐 JavaScript | 📅 2021-08-04 - A simple plugin for CSS3 text animations.
* [animatable](https://github.com/LeaVerou/animatable) ⭐ 2,584 | 🐛 4 | 🌐 HTML | 📅 2024-08-20 - One property, two values, endless possibilities.
* [typicaljs](https://github.com/camwiegert/typical) ⭐ 1,585 | 🐛 4 | 🌐 JavaScript | 📅 2023-09-09 - Animated typing in \~400 bytes 🐡 of JavaScript
* [particles-bg](https://github.com/lindelof/particles-bg) ⭐ 669 | 🐛 6 | 🌐 JavaScript | 📅 2021-04-02 - A lightweight React particles animation background component.
* [shuffle-images](https://github.com/peachananr/shuffle-images) ⭐ 214 | 🐛 4 | 🌐 JavaScript | 📅 2020-05-08 - The Simplest Way to shuffle through images in a Creative Way.
* [TransitionEnd](https://github.com/EvandroLG/transitionEnd) ⭐ 96 | 🐛 2 | 🌐 HTML | 📅 2026-01-21 - TransitionEnd is an agnostic and cross-browser library to work with transitioned event.
* [the-cube](https://github.com/pstadler/the-cube) ⭐ 12 | 🐛 0 | 🌐 HTML | 📅 2022-11-22 - The Cube is an experiment with CSS3 transitions.
* [Anime.js](https://animejs.com/) - A JavaScript animation engine.
* [Mo.js](https://mojs.github.io/) - Motion graphics toolbelt for the web.
* [AutoAnimate](https://auto-animate.formkit.com) - Add motion to your apps with a single line of code.

## Image Processing

* [cropper](https://github.com/fengyuanchen/cropper) ⚠️ Archived - A simple jQuery image cropping plugin.
* [pica](https://github.com/nodeca/pica) ⭐ 4,027 | 🐛 18 | 🌐 JavaScript | 📅 2023-06-28 - High quality image resize (with fast Lanczos filter, implemented in pure JS).
* [lena.js](https://github.com/davidsonfellipe/lena.js) ⭐ 680 | 🐛 10 | 🌐 JavaScript | 📅 2023-06-25 - A Library for image processing with filters and util functions.

## ES6

* [Babel (Formerly 6to5)](https://github.com/babel/babel) ⭐ 43,877 | 🐛 754 | 🌐 TypeScript | 📅 2026-02-06 - Turn ES6+ code into vanilla ES5 with no runtime.
* [es6features](https://github.com/lukehoban/es6features) ⭐ 29,155 | 🐛 38 | 📅 2023-01-27 - Overview of ECMAScript 6 features.
* [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) ⭐ 13,353 | 🐛 7 | 🌐 JavaScript | 📅 2022-10-08 - ES2015 \[ES6] cheatsheet containing tips, tricks, best practices and code snippets.
* [Traceur compiler](https://github.com/google/traceur-compiler) ⭐ 8,161 | 🐛 292 | 🌐 JavaScript | 📅 2024-12-10 - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.
* [es6-features](https://github.com/rse/es6-features) ⭐ 6,180 | 🐛 34 | 🌐 HTML | 📅 2024-06-20 - ECMAScript 6: Feature Overview & Comparison.
* [ECMAScript 6 compatibility table](https://compat-table.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.

## Generators

* [Next.js](https://github.com/vercel/next.js) ⭐ 137,553 | 🐛 3,281 | 🌐 JavaScript | 📅 2026-02-07 - React powered static site generator, and they say "All the tools you need to make the Web. Faster.".
* [Docusaurus](https://github.com/facebook/docusaurus) ⭐ 63,695 | 🐛 356 | 🌐 TypeScript | 📅 2026-02-06 - React-based static site generator by Facebook, ideal for content-centric websites.
* [Astro](https://github.com/withastro/astro) ⭐ 56,594 | 🐛 226 | 🌐 TypeScript | 📅 2026-02-07 - The web framework for content-driven websites.
* [Gatsby.js](https://github.com/gatsbyjs/gatsby) ⭐ 55,973 | 🐛 360 | 🌐 JavaScript | 📅 2026-02-04 - React-based static site generator.
* [Gridsome](https://github.com/gridsome/gridsome) ⭐ 8,513 | 🐛 581 | 🌐 JavaScript | 📅 2024-04-10 - Vue-powered static site generator.
* [Lume](https://github.com/lumeland/lume) ⭐ 2,202 | 🐛 36 | 🌐 TypeScript | 📅 2026-02-06 - Static site generator for Deno.

## SDK

* [OpenAI SDK](https://github.com/openai/openai-node) ⭐ 10,607 | 🐛 142 | 🌐 TypeScript | 📅 2026-02-06 - Official JavaScript / TypeScript library for the OpenAI API.
* [Stripe Node.js SDK](https://github.com/stripe/stripe-node) ⭐ 4,339 | 🐛 44 | 🌐 TypeScript | 📅 2026-02-05 - Stripe Node.js SDK lets you integrate payments, subscriptions, and billing into your JavaScript/TypeScript apps.
* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) ⭐ 1,437 | 🐛 2 | 🌐 JavaScript | 📅 2025-10-15 - JavaScript SDK design guide extracted from work and personal experience.
* [Spotify SDK](https://github.com/loverajoel/spotify-sdk) ⭐ 228 | 🐛 13 | 🌐 JavaScript | 📅 2021-08-22 - Entity oriented SDK to work with the Spotify Web API.
* [Square Node.js SDK](https://github.com/square/connect-nodejs-sdk/) ⚠️ Archived - JavaScript client library for payments and other Square APIs.

## Full Text Search

* [flexsearch](https://github.com/nextapps-de/flexsearch) ⭐ 13,577 | 🐛 27 | 🌐 JavaScript | 📅 2025-09-26 - It is a Next-Generation full text search library for Browser and Node.js.
* [lunr](https://github.com/olivernn/lunr.js) ⭐ 9,202 | 🐛 130 | 🌐 JavaScript | 📅 2024-07-31 - Library for use in the browser and It indexes JSON documents and provides a simple search interface for retrieving documents that best match text queries.
* [Elasticlunr](https://github.com/weixsong/elasticlunr.js) ⭐ 2,078 | 🐛 77 | 🌐 JavaScript | 📅 2022-12-10 - This library is based on lunr.js, but more flexible and customized.

## ORM

* [Prisma](https://github.com/prisma/prisma) ⭐ 45,234 | 🐛 2,474 | 🌐 TypeScript | 📅 2026-02-06 Next-generation ORM for Node.js & TypeScript | PostgreSQL, MySQL, MariaDB, SQL Server, SQLite, MongoDB and CockroachDB.
* [TypeORM](https://github.com/typeorm/typeorm) ⭐ 36,297 | 🐛 479 | 🌐 TypeScript | 📅 2026-02-03 ORM for TypeScript and JavaScript, Works in NodeJS, Browser, Ionic, Cordova and Electron platforms.
* [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) ⭐ 32,686 | 🐛 1,537 | 🌐 TypeScript | 📅 2026-02-06 Headless TypeScript ORM with a head. Runs on Node, Bun and Deno.
* [Sequelize](https://github.com/sequelize/sequelize) ⭐ 30,336 | 🐛 1,004 | 🌐 TypeScript | 📅 2026-02-05 Feature-rich ORM for modern Node.js and TypeScript | PostgreSQL, MySQL, MariaDB, SQLite, MS SQL Server, Snowflake, Oracle DB...
* [Mongoose](https://github.com/Automattic/mongoose) ⭐ 27,449 | 🐛 201 | 🌐 JavaScript | 📅 2026-02-07 MongoDB object modeling designed to work in an asynchronous environment.
* [Knex](https://github.com/knex/knex) ⭐ 20,206 | 🐛 702 | 🌐 JavaScript | 📅 2026-02-03 A query builder for PostgreSQL, MySQL, CockroachDB, SQL Server, SQLite3 and Oracle, designed to be flexible, portable, and fun to use.
* [Kysely](https://github.com/kysely-org/kysely) ⭐ 13,423 | 🐛 156 | 🌐 TypeScript | 📅 2026-02-03 A type-safe typescript SQL query builder.
* [MikroORM](https://github.com/mikro-orm/mikro-orm) ⭐ 8,817 | 🐛 40 | 🌐 TypeScript | 📅 2026-02-06 TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns.
* [Objection.js](https://github.com/Vincit/objection.js) ⭐ 7,354 | 🐛 127 | 🌐 JavaScript | 📅 2025-10-02 A SQL-friendly ORM for Node.js built on top of Knex.js, with powerful relational support.

## WebSockets

* [Socket.io](https://github.com/socketio/socket.io) ⭐ 62,859 | 🐛 203 | 🌐 TypeScript | 📅 2026-01-23 The most widely used WebSocket library for real-time applications. Supports auto-reconnection, rooms, and fallbacks (e.g., polling).
* [ws](https://github.com/websockets/ws) ⭐ 22,652 | 🐛 5 | 🌐 JavaScript | 📅 2026-01-09 Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js.

## Generative AI

* [KaibanJS](https://github.com/kaiban-ai/KaibanJS) ⭐ 1,335 | 🐛 64 | 🌐 TypeScript | 📅 2025-12-12 - KaibanJS is an open-source framework browser-compatibility of orchestration of multi-agent ai systems using a Kanban-inspired architecture.

## Misc

* [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) ⭐ 195,529 | 🐛 388 | 🌐 JavaScript | 📅 2026-01-02 - Algorithms and data structures implemented in JavaScript with explanations and links to further readings.
* [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) ⭐ 26,442 | 🐛 19 | 🌐 TypeScript | 📅 2026-02-07 - Makes a visitor identifier from a browser fingerprint that stays the same in incognito mode and when browser data is purged.
* [ky](https://github.com/sindresorhus/ky) ⭐ 16,317 | 🐛 31 | 🌐 TypeScript | 📅 2026-01-25 - Tiny and elegant HTTP client based on the browser Fetch API.
* [list.js](https://github.com/javve/list.js) ⭐ 11,248 | 🐛 202 | 🌐 JavaScript | 📅 2025-04-27 - Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
  <https://listjs.com>
* [picturefill](https://github.com/scottjehl/picturefill) ⚠️ Archived - A responsive image polyfill for \<picture>, srcset, sizes.
* [Peg.js](https://github.com/pegjs/pegjs) ⭐ 4,918 | 🐛 117 | 🌐 JavaScript | 📅 2021-11-08 - A simple parser generator for JavaScript that produces fast parsers with excellent error reporting. Usable from your browser, from the command line, or via JavaScript API.
* [SurveyJS](https://github.com/surveyjs/survey-library) ⭐ 4,671 | 🐛 499 | 🌐 TypeScript | 📅 2026-02-06 - SurveyJS is a JavaScript Survey and Form Library. <https://surveyjs.io/>
* [mixitup](https://github.com/patrickkunka/mixitup) ⚠️ Archived - MixItUp - A Filter & Sort Plugin.
* [echo](https://github.com/toddmotto/echo) ⭐ 3,702 | 🐛 87 | 🌐 JavaScript | 📅 2026-01-02 - Lazy-loading images with data-\* attributes.
* [platform.js](https://github.com/bestiejs/platform.js) ⚠️ Archived - A platform detection library that works on nearly all JavaScript platforms.
* [jquery-match-height](https://github.com/liabru/jquery-match-height) ⭐ 3,167 | 🐛 86 | 🌐 JavaScript | 📅 2018-08-24 - a responsive equal heights plugin for jQuery.
* [Array Explorer](https://github.com/sdras/array-explorer) ⭐ 2,615 | 🐛 30 | 🌐 JavaScript | 📅 2024-06-28 and [Object Explorer](https://objectexplorer.netlify.app/) - Resources to help figure out what native JavaScript method would be best to use at any given time.
* [Idyll](https://github.com/idyll-lang/idyll) ⭐ 2,024 | 🐛 60 | 🌐 JavaScript | 📅 2023-02-04 - Create explorable explanations and interactive storytelling essays. Can be [embedded in HTML](https://github.com/idyll-lang/idyll-embed) ⭐ 13 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-07.
* [jsemu](https://github.com/fcambus/jsemu) ⭐ 1,839 | 🐛 0 | 📅 2026-01-29 - A list of emulators written in the JavaScript programming language.
* [emoji-button](https://github.com/joeattardi/emoji-button) ⚠️ Archived - Vanilla JavaScript emoji picker component.
* [json3](https://github.com/bestiejs/json3) ⚠️ Archived - A modern JSON implementation compatible with nearly all JavaScript platforms.
* [spoiler-alert](https://github.com/joshbuddy/spoiler-alert) ⭐ 474 | 🐛 11 | 🌐 JavaScript | 📅 2016-10-27 - SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site.
* [BitSet.js](https://github.com/infusion/BitSet.js) ⭐ 236 | 🐛 4 | 🌐 JavaScript | 📅 2024-10-09 - A JavaScript Bit-Vector implementation.
* [iooxa](https://github.com/iooxa/article) ⭐ 193 | 🐛 20 | 🌐 TypeScript | 📅 2025-05-14 - Components for interactive scientific writing, reactive documents and explorable explanations.
* [jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) ⭐ 144 | 🐛 4 | 🌐 HTML | 📅 2016-05-26 - Vibration API Wrappers
* [lune](https://github.com/ryanseys/lune) ⭐ 124 | 🐛 4 | 🌐 JavaScript | 📅 2023-04-14 - Library to calculate the phases of the moon accurately.
* [Fcal](https://github.com/5anthosh/fcal) ⭐ 115 | 🐛 5 | 🌐 TypeScript | 📅 2021-02-03 -  Math expression evaluator.
* [Logical Or Not](https://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* [grid](https://github.com/hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists.
* [Clipboard.js](https://clipboardjs.com/) - "Copy to clipboard" without Flash or use of Frameworks.

# Worth Reading

* [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) ⭐ 184,366 | 🐛 3 | 📅 2026-01-18 - Possibly the best book written on modern JavaScript, completely readable online for free, or can be bought to support the author.
* [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) ⭐ 94,290 | 🐛 119 | 🌐 JavaScript | 📅 2024-07-29 - Clean Code concepts adapted for JavaScript.
* [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) ⭐ 16,796 | 🐛 26 | 🌐 JavaScript | 📅 2023-12-26 - Pragmatic, balanced FP in JavaScript.
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) ⭐ 8,714 | 🐛 31 | 🌐 HTML | 📅 2024-01-25 - An easy-to-read, quick reference for JS best practices, accepted coding standards, and links around the Web.
* [JSbooks](https://github.com/revolunet/JSbooks) ⭐ 2,528 | 🐛 8 | 🌐 CSS | 📅 2020-09-25 - Directory of free JavaScript ebooks.
* [SJSJ](https://github.com/KittyGiraudel/SJSJ) ⭐ 2,264 | 🐛 19 | 🌐 HTML | 📅 2022-09-25 - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
* [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) ⭐ 185 | 🐛 0 | 📅 2020-09-28 - A comprehensive guide through a set of steps to publish a JavaScript open source library.
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* [JavaScript Tutorials](https://hackr.io/tutorials/learn-javascript) - Learn Javascript online from a diverse range of user ranked online tutorials.
* [Roadmap.sh JavaScript Roadmap](https://roadmap.sh/javascript) - Learn JavaScript from a community sourced learning roadmap.

# Other Awesome Lists

* [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ⭐ 435,645 | 🐛 67 | 📅 2026-01-28
* [MaximAbramchuck/awesome-interviews](https://github.com/MaximAbramchuck/awesome-interview-questions) ⚠️ Archived
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react) ⭐ 71,886 | 🐛 14 | 📅 2026-01-14
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,201 | 🐛 43 | 🌐 Ruby | 📅 2024-06-02
* [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch) ⭐ 13,548 | 🐛 0 | 📅 2022-01-20
* [jnv/list](https://github.com/jnv/lists) ⭐ 10,936 | 🐛 7 | 📅 2025-05-20
* [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) ⭐ 8,799 | 🐛 5 | 🌐 JavaScript | 📅 2025-07-21
* [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css) ⭐ 5,502 | 🐛 12 | 📅 2024-10-30
* [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) ⭐ 4,628 | 🐛 14 | 🌐 Shell | 📅 2026-01-06
* [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning) ⭐ 4,541 | 🐛 0 | 📅 2022-09-02
* [denolib/awesome-deno](https://github.com/denolib/awesome-deno) ⭐ 4,403 | 🐛 1 | 📅 2025-08-19
* [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) ⭐ 3,987 | 🐛 14 | 📅 2019-10-31
* [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun) ⭐ 3,448 | 🐛 52 | 📅 2025-07-20
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) ⭐ 3,090 | 🐛 16 | 📅 2024-07-31
* [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs) ⚠️ Archived
* [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery) ⭐ 977 | 🐛 0 | 📅 2026-01-01
* [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents) ⭐ 646 | 🐛 1 | 📅 2024-01-15
* [instanceofpro/awesome-backbone](https://github.com/sadcitizen/awesome-backbone) ⭐ 405 | 🐛 3 | 📅 2018-03-20
* [davidyezsetz/you-might-not-need-jquery-plugins](https://github.com/davidyezsetz/you-might-not-need-jquery-plugins) ⭐ 139 | 🐛 20 | 🌐 HTML | 📅 2017-12-12
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo) ⭐ 95 | 🐛 0 | 📅 2020-09-25

# Contributing

Contributions welcome! Read the [contribution guidelines](origin/CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.

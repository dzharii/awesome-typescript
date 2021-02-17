# Awesome TypeScript [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[TypeScript](https://www.typescriptlang.org) is an extension of JavaScript that supports type definitions.

## Contents

- [Resources](#resources)
- [Boilerplates](#boilerplates)
- [Books](#books)
- [Tools](#tools)
- [IDE](#ide)
  - [Offline](#offline)
    - [Visual Studio](#visual-studio)
    - [Other](#other)
  - [Online](#online)
    - [Playground](#playground)
    - [Chrome Extension](#chrome-extension)
- [Awesome TypeScript Videos](#awesome-TypeScript-videos)
- [Frameworks](#frameworks)
  - [React](#react)
- [Aspect Oriented Programming](#aspect-oriented-programming)
- [Build Systems](#build-systems)
- [Cloud Data Warehousing](#cloud-data-warehousing)
- [Module Bundlers](#module-bundlers)
- [CMS](#cms)
- [Tools](#tools-1)
- [Types](#types)
  - [Runtime](#runtime)
- [Validation](#validation)
- [Built with TypeScript](#built-with-TypeScript)
  - [Mobile](#mobile)
  - [Web](#web)
  - [Back-end API](#back-end-api)
  - [Standalone apps](#standalone-apps)
  - [Design patterns](#design-patterns)
  - [Libraries](#libraries)
- [Video Courses](#video-courses)
- [Free](#free)
- [Paid](#paid)

## Resources

* [Handbook](https://www.TypeScriptlang.org/docs/handbook/intro.html) - Basic guide to using TypeScript
* [TypeScript Deep Dive](https://basarat.gitbooks.io/TypeScript/) - Solving common TypeScript issues
* [TypeScript Blog](http://blogs.msdn.com/b/TypeScript/) - Annoucements and recent updates
* [DefinitelyTyped](http://definitelytyped.org/) - Community-maintained type definitions
* [Type search](https://aka.ms/typings) - Search for packages that support type definitions
* [Clean code guide](https://github.com/labs42io/clean-code-TypeScript) - How to write readable, clean TypeScript code
* [Should you learn TypeScript?](https://snipcart.com/blog/learn-TypeScript-why-use-ts)
* [Community curated resources](https://hackr.io/tutorials/learn-TypeScript)

## Boilerplates

* [TypeScript-starter](https://github.com/bitjson/TypeScript-starter) – A CLI to quickly generate and configure new libraries and Node.js projects
* [next-smrt](https://github.com/csprance/next-smrt) – A Typescript/Next.js boilerplate with Redux/Styled Components/Material UI and TypeSafe Actions
* [Next-Postgres-With-Typescript](https://github.com/brandontle/next-postgres-with-TypeScript) - Forum-like fullstack web app boilerplate with Next.js 7.0.2 + Sequelize 4/Postgres + Typescript + Redux + Passport Local Auth + Emotion
* [MicroTS](https://www.npmjs.com/package/microts) Microservice code generator with interface-first approach: from OpenAPI (Swagger) REST API specification is generated complete project with TypeScript code, input validator, UI, tests and Docker configuration.
* [pankod/next-boilerplate](https://github.com/pankod/next-boilerplate) A well-structured production ready Next.js boilerplate with Typescript, Redux, Jest, Enzyme, Express.js, Sass, Css, EnvConfig, Reverse Proxy, Bundle Analyzer and Built-in CLI
* [jsynowiec/node-TypeScript-boilerplate](https://github.com/jsynowiec/node-TypeScript-boilerplate) Up-to-date, developer ready and comprehensive, yet minimalistic template. Works out of the box for most Node.js projects. All basic tools included and configured. Targets latest Node.js LTS and TypeScript releases.
* [TypeScript-express-starter](https://github.com/ljlm0402/TypeScript-express-starter) - Quick and Easy TypeScript Express Starter.
* [The Knests Stack](https://github.com/tudorconstantin/knests/) - Full stack boilerplate (hackathon starter) with: PostgreSQL, Knex.js, NestJS, Next.js, GraphQL, React (with hooks and TypeScript), Material-UI, Docker multistage images for, Docker compose and a Gitlab CI/CD pipeline fully configured.

## Books

* [TypeScript Quickly](https://www.manning.com/books/TypeScript-quickly) Learn modern TypeScript and build your own blockchain; Supporting code samples [yfain/getts](https://github.com/yfain/getts)
* [Angular Development with Typescript, Second Edition (MEAP October 2017)](https://www.manning.com/books/angular-development-with-TypeScript-second-edition) Angular Development with Typescript, Second Edition is an intermediate-level tutorial that introduces Angular and TypeScript to developers comfortable with building web applications using other frameworks and tools. (by Yakov Fain and Anton Moiseev; Manning)
* [Angular 2 Development with TypeScript (2016)](https://www.manning.com/books/angular-2-development-with-TypeScript) by Yakov Fain and Anton Moiseev; Manning
* [Learning TypeScript 2.x 2nd Ed.](https://www.learningTypeScript.com) by Remo H. Jansen
* [Mastering TypeScript 2nd Ed.](https://www.packtpub.com/application-development/mastering-TypeScript-second-edition) by Nathan Rozentals
* [Beginning Angular 4 with TypeScript](https://www.amazon.com/Beginning-Angular-Typescript-Greg-Lim/dp/1542916674) by Greg Lim
* [Programming with Types](https://www.manning.com/books/programming-with-types) - A book on how to design safe, resilient, correct software that’s easy to maintain and understand by taking advantage of the power of type systems. (by Vlad Riscutia)

## Tools

* [ts-node](https://github.com/TypeStrong/ts-node) - run scripts or REPL

## IDE

### Offline

#### Visual Studio
* [ Visual Studio Community Edition 2015](https://www.visualstudio.com/products/visual-studio-community-vs) - free (conditionally) IDE with integrated TypeScript support
  * [VS Addon - TypescriptSyntaxPaste](https://visualstudiogallery.msdn.microsoft.com/eb0887f8-3ac1-434a-b50b-f0112f1572f7) - Allow you to copy C# source code, then paste as Typescript syntax which help you with converting DTO or interface
* [NodeJS Tools for Visual Studio](https://github.com/Microsoft/nodejstools)

#### Other

* [Visual Studio Code](https://www.visualstudio.com/en-us/products/code-vs.aspx)
* [PhpStorm](https://www.jetbrains.com/phpstorm/download/)
* [WebStorm](https://www.jetbrains.com/webstorm/download/)
* [CATS](http://jbaron.github.io/cats/) is an IDE for TypeScript and Web developers by @jbaron
* [TypeScript Sublime Plugin](https://github.com/Microsoft/TypeScript-Sublime-Plugin) by @Microsoft
* [Atom TypeScript](https://github.com/TypeStrong/atom-TypeScript) by @TypeStrong
* [TypeScript Interactive Development Environment for Emacs](https://github.com/ananthakumaran/tide) by @ananthakumaran
* [TypeScript Syntax for VIM](https://github.com/leafgarland/TypeScript-vim)
* [Typescript addin for](https://github.com/mrward/TypeScript-addin) MonoDevelop, SharpDevelop and Xamarin Studio;  a short [review article](http://lastexitcode.com/blog/2015/04/01/TypeScriptSupportInXamarinStudio/)
* [Typescript tooling for Neovim](https://github.com/mhartington/nvim-TypeScript) is a language service plugin for TypeScript for Neovim.

### Online

#### Playground
* [TypeScript playground](https://agentcooper.github.io/TypeScript-play/) by @agentcooper, supports multiple TS versions and compiler targets
* [TypeScript playground-on-ace](https://github.com/hi104/TypeScript-playground-on-ace) by @hi104 [updated to TypeScript 1.5](https://github.com/basarat/TypeScriptEditor)
* [TypeScript official Playground](http://www.TypeScriptlang.org/Playground/)
* [JS Bin](http://jsbin.com/?js) (Select TypeScript)
* [Codepen](http://codepen.io/) (Select TypeScript)
* [TypeScript Interpret - Terminal Emulator](http://niutech.github.io/TypeScript-interpret/) by @niutech
* [TypeScript Editor](http://drake7707.github.io/Typescript-Editor/) by @drake7707

#### Chrome Extension

* [OctoLinker](https://github.com/OctoLinker/browser-extension)

## Awesome TypeScript Videos

* [Evolving JavaScript with TypeScript](https://www.youtube.com/watch?v=Ut694dsIa8w) a detailed introduction to TypeScript

## Frameworks
### React

* [facebook/create-react-app](https://facebook.github.io/create-react-app/docs/adding-TypeScript) Create React apps using TypeScript with no build configuration
* [Microsoft/TypeScript-React-Starter](https://github.com/Microsoft/TypeScript-React-Starter) A starter template for TypeScript and React with a detailed README describing how to use the two together; based on `create-react-app`
* [TypeScript-cheatsheets/react-TypeScript-cheatsheet](https://github.com/TypeScript-cheatsheets/react-TypeScript-cheatsheet) Cheatsheets for experienced React developers getting started with TypeScript
* [jsxtyper](https://github.com/fuselabs/jsxtyper) Generates TypeScript interfaces from .jsx files
* [Building a simple react component with TypeScript](http://www.austentalbot.com/how-to-use-react-with-TypeScript/)
* [TodoMVC • TypeScript + React Example](https://github.com/tastejs/todomvc/tree/gh-pages/examples/TypeScript-react)
* [Working with React and TypeScript](http://blog.wolksoftware.com/working-with-react-and-TypeScript)
* [**vortigern** - A universal boilerplate for building web applications w/ TypeScript, React, Redux and more.](https://github.com/barbar/vortigern)
* [Convert React code to TypeScript automatically](https://github.com/lyft/react-javascript-to-TypeScript-transform)
* [React Server Example TSX](https://github.com/styfle/react-server-example-tsx) Boilerplate for isomorphic web app with React server-side rendering in TypeScript
* [React & Redux in TypeScript - Static Typing Guide](https://github.com/piotrwitek/react-redux-TypeScript-guide) The complete guide to static typing in "React & Redux" using TypeScript
* [Typescript Monorepo CRA Example](https://github.com/deptno/TypeScript-monorepo-cra-example) - A minimalistic CRA + TypeScript monorepo.
* [Typescript Monorepo Next Example](https://github.com/deptno/TypeScript-monorepo-next-example) - A minimalistic next.js + TypeScript monorepo.
* [React TypeScript Kickstart Guide](https://sandstorm.github.io/TypeScript-react-app-kickstart-guide/) - In-depth, incl. boilerplate, cookbook & snipptes for Redux, Sass, Storybook and unit testing.
* [Crisp React](https://github.com/winwiz1/crisp-react) Boilerplate with React client and Express backend. Offers performance and extended functionality. Helps to avoid frequent React-Express pitfalls.
* [React by Example](https://reactbyexample.github.io/) Code-oriented React tutorial for programmers

## Aspect Oriented Programming

* [Agent Framework](https://github.com/agentframework/agentframework) Create interceptor for your class and method using @decorators

## Build Systems

* [Grunt](http://gruntjs.com/) tasks:
  - [grunt-ts](https://www.npmjs.com/package/grunt-ts) - Grunt-ts is an npm package that handles TypeScript compilation work in GruntJS build scripts
* [Zwitterion](https://github.com/lastmjs/zwitterion) - Super simple development server with built-in support for TypeScript files.

## Cloud Data Warehousing

* [Crisp BigQuery](https://github.com/winwiz1/crisp-bigquery) Starter project that delivers Google BigQuery data to end user browsers with cost control. Allows to implement rich data presentation options.
* [DDB-Table](https://github.com/neuledge/ddb-table) Strongly typed querys and tables for AWS DynamoDB

## Module Bundlers

* [Webpack](http://webpack.github.io/) - supports CommonJS and AMD module bundling
  - [TypeScript and webpack](http://www.jbrantly.com/TypeScript-and-webpack/) - How to configure Webpack for TypeScript with source map support
* [Browserify](http://browserify.org/) - CommonJS module bundler. Does not support TypeScript out of the box, but can be applied with [Grunt](http://gruntjs.com/) tasks: [grunt-ts](https://www.npmjs.com/package/grunt-ts), [grunt-browserify](https://www.npmjs.com/package/grunt-browserify), [grunt-contrib-uglify](https://www.npmjs.com/package/grunt-contrib-uglify)
* [fuse-box](https://github.com/fuse-box/fuse-box) - TypeScript sample: [fuse-box-ts-react-reflux-seed](https://github.com/fuse-box/fuse-box-ts-react-reflux-seed)

## CMS

* [Factor](https://factor.dev) - The Javascript CMS (TypeScript supported natively)

## Tools

* [Deno](https://deno.land/) - A secure runtime for JavaScript and TypeScript
* [SweetIQ/schemats](https://github.com/SweetIQ/schemats) Generate TypeScript interface definitions from SQL database schema
* [TypeDoc](http://typedoc.org/) - A documentation generator for TypeScript projects
* [TsLint](https://github.com/palantir/tslint) - TypeScript linter by @palantir
* [TypeScript Standard](https://github.com/e2tox/TypeScript-standard) - Zero-configuration TypeScript 2 Standard Validation
* [typed-install](https://github.com/xavdid/typed-install) - Easily install new dependencies and their typings, no matter where they may be
* [Interactive TypeScript AST Viewer](https://ast.carlosroso.com/) - Write TypeScript snippets and explore its AST.
* [type-config](https://github.com/Saul-Mirone/type-config) - A generator for tsconfig.

## Types

* [type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability
* [utility-types](https://github.com/piotrwitek/utility-types) - Utility Types for TypeScript (provide compatibility with Flow's Utility Types)
* [elm-ts](https://github.com/gcanti/elm-ts) - Port of Elm architecture to TypeScript featuring fp-ts, io-ts, rxjs5 and React
* [ts-essentials](https://github.com/krzkaczor/ts-essentials) - All essential TypeScript types in one place
* [TypeScript-conditional-types](https://github.com/LeDDGroup/TypeScript-conditional-types) - Helpers for TypeScript generic types
* [ts-types-utils](https://github.com/LeDDGroup/ts-types-utils) - Type utilities for TypeScript
* [typesync](https://github.com/jeffijoe/typesync) - Install missing TypeScript typings for dependencies in your package.json.
* [type-fest](https://github.com/sindresorhus/type-fest) - A collection of essential TypeScript types
* [typetype](https://github.com/mistlog/typetype) - A programming language designed for TypeScript type generation
### Runtime

* [json-decoder](https://github.com/venil7/json-decoder) - Typesafe JSON decoder and runtime checker
* [TypeScript-is](https://github.com/woutervh-/TypeScript-is) - TypeScript transformer that generates run-time type-checks.
* [type-plus](https://github.com/unional/type-plus) - Additional types and type adjusted utilities

## Validation

* [io-ts](https://github.com/gcanti/io-ts) - Runtime type system for IO decoding/encoding
* [zod](https://github.com/vriad/zod) - TypeScript-first schema validation with static type inference
* [runtypes](https://github.com/pelotom/runtypes) - Runtime validation for static types
* [ow](https://github.com/sindresorhus/ow) - Function argument validation for humans
* [superstruct](https://github.com/ianstormtaylor/superstruct) - A simple and composable way to validate data
* [computed-types](https://github.com/neuledge/computed-types) - 🦩 Joi like validations for TypeScript
* [json-schema-to-ts](https://github.com/thomasaribart/json-schema-to-ts) - Dynamic type inference from JSON schemas


## Built with TypeScript

### Mobile
* [NativeScript](https://github.com/NativeScript/NativeScript) - Open Source framework for building cross-platform truly native iOS, Android and Windows mobile apps using JavaScript
* [Monaco Editor](https://microsoft.github.io/monaco-editor/index.html)

### Web
* [Angular](https://github.com/angular/angular) - Angular is a development platform for building mobile and desktop web applications
* [feednext.io](https://github.com/feednext/feednext) - An open-source social media application built with Typescript on both client-server side.
* [ionic](https://github.com/ionic-team/ionic) - An open-source mobile app development framework build in TypeScript
* [React-UWP](https://github.com/myxvisual/react-uwp) - React Components that Implement Microsoft's UWP Design & Fluent Design.
* [palantir/plottable](https://github.com/palantir/plottable) - A library of modular chart components, built on `D3` (see also: http://plottablejs.org)
* [APIs-guru/graphql-voyager](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph 🛰️
* [Rebilly/ReDoc](https://github.com/Rebilly/Redoc) - OpenAPI/Swagger-generated API Reference Documentation
* [excaliburjs/Excalibur](https://github.com/excaliburjs/Excalibur) - Free open source JavaScript game engine
* [Bobril](https://github.com/Bobris/Bobril) - Component oriented framework inspired by Mithril and ReactJs. (see also: http://bobril.com/)
* [Stencil](https://github.com/ionic-team/stencil) - a tool for building modern Web Components
* [redux-zero](https://github.com/concretesolutions/redux-zero) - A lightweight state container based on Redux
* [wretch](https://github.com/elbywan/wretch) - A tiny (< 2.2Kb g-zipped) wrapper built around fetch with an intuitive syntax.
* [Cycle.js](https://github.com/cyclejs/cyclejs) - A functional and reactive JavaScript framework for predictable code.
* [Tridactyl](https://github.com/tridactyl/tridactyl) - A Firefox browser addon that replaces browser's control mechanism with one modelled on the one true editor, Vim.
* [armour/vue-TypeScript-admin-template](https://github.com/Armour/vue-TypeScript-admin-template) - A vue-cli 3.0 & TypeScript minimal admin template + a production-ready front-end solution for admin interfaces ([demo](https://armour.github.io/vue-TypeScript-admin-template/#/dashboard))
* [n8n.io](https://github.com/n8n-io/n8n) - Open Source Workflow Automation Tool
* [Dnote](https://github.com/dnote/dnote) - A command line notebook with a multi-device sync and a web interface.

### Back-end API

* [design-first](https://adam-hanna.github.io/design-first-docs/) - A REST api templating engine for Typescript
* [Nest](https://github.com/nestjs/nest) - A progressive Node.js framework for building efficient, scalable, and enterprise-grade server-side applications on top of TypeScript 🚀 (see also: https://nestjs.com/)
* [LoopBack 4](https://github.com/strongloop/loopback-next) - A highly extensible Node.js and TypeScript framework for building APIs and microservices. :rocket: (see also: https://loopback.io/)
* [FoalTS](https://github.com/FoalTS/foal) - A simple, intuitive and complete framework for building enterprise-grade Node.JS applications :boom: :rocket: (see also: https://foalts.org)
* [Enso](http://ensojs.netlify.com) - Typescript first Node.JS framework inspired by Domain Driven Design principles with a focus on composition and Developer Experience
* [Libstack](https://libstack.io) - A collection of various modules to create Typescript server easily and ready to be deployed on Docker.
* [tinyhttp](https://github.com/talentlessguy/tinyhttp) - A modern Express-like web framework for Node.js, written in TypeScript and compiled to Native ESM.
* [ZenTS](https://github.com/sahachide/ZenTS) - A modern Node.js and TypeScript first framework for building rich web applications (see also: https://zents.dev)
* [Booster Framework](https://github.com/boostercloud/booster) - Event-driven cloud native GraphQL open-source framework, part of the Booster Cloud ecosystem. It makes use of high-level abstractions and conventions. (see also: https://booster.cloud)


### Standalone apps
* [Visual Studio Code](https://github.com/Microsoft/vscode) - Multiplatform IDE.
* [alm - A next generation IDE just for TypeScript written in TypeScript + React](https://github.com/alm-tools/alm)

### Design patterns
* [Design Patterns implementation](https://github.com/torokmark/design_patterns_in_TypeScript) - Implementation of the well-known 23 patterns of GoF

### Libraries
* [Procedurem](https://github.com/ImVexed/Procedurem) - A Small (2kb) And Performant Bi-Directional RPC Library Using WebSockets.
* [RxJS](https://github.com/ReactiveX/RxJS) - A reactive programming library for JavaScript.
* [xstream](https://github.com/staltz/xstream) - An extremely intuitive, small, and fast functional reactive stream library for JavaScript.
* [substitute.js](https://github.com/ffMathy/FluffySpoon.JavaScript.Testing) - A fluent mocking library for TypeScript ported from NSubstitute.
* [TypeMoq](https://github.com/florinn/typemoq) - A simple mocking library for TypeScript.
* [fast-check](https://github.com/dubzzz/fast-check) - Property based testing framework for TypeScript.
* [InversifyJS](https://github.com/inversify/InversifyJS/) -  powerful and lightweight inversion of control container for JavaScript & Node.js apps powered by TypeScript.
* [TypeORM](https://github.com/typeorm/typeorm) - ORM for TypeScript and JavaScript (ES7, ES6, ES5). Supports MySQL, PostgreSQL, MariaDB, SQLite, MS SQL Server, Oracle, WebSQL databases. Works in NodeJS, Browser, Ionic, Cordova and Electron platforms.
* [MikroORM](https://github.com/mikro-orm/mikro-orm) - TypeScript ORM for Node.js based on Data Mapper, Unit of Work and Identity Map patterns. Supports MongoDB, PostgreSQL, MySQL and SQLite.
* [Prisma](https://github.com/prisma/prisma) - Modern database access (ORM alternative) for Node.js & TypeScript | PostgreSQL, MySQL & SQLite
* [TypeGQL](https://github.com/prismake/typegql) - Set of tools for creating GraphQL schema directly from typed TypeScript class.
* [TSTL](https://github.com/samchon/tstl) - Implementation of C++ STL (Standard Template Library) in TypeScript. Provided modules are containers, iterators, algorithms and functors.
  * [ECol](https://github.com/samchon/ecol) - Extension of TSTL containers; collections dispatching Elements I/O events.
  * [TGrid](https://github.com/samchon/tgrid) - Grid Computing Framework, Network & Thread extension of TSTL, supporting RFC (Remote Function Call).
  * [Mutex-Server](https://github.com/samchon/mutex-server) - Critical sections controller, like mutex and semaphore, in the network level.
* [Kalimdor.js](https://github.com/JasonShin/kalimdorjs) - Machine Learning library for the Web, Node and Developers!
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts) - Functional programming: immutable persistent collections, constructs such as Option and Either, and combinators.
* [ee-ts](https://github.com/aleclarson/ee-ts) - Typed event emitters
* [io-ts](https://github.com/gcanti/io-ts) - Type validation at runtime
* [mokia](https://github.com/varHarrie/mokia) - A mock server integrated data simulation and http service.
* [sub-events](https://github.com/vitaly-t/sub-events) - Strongly-typed events.
* [ts-audio](https://github.com/EvandroLG/ts-audio) - an agnostic and easy-to-use library to work with the `AudioContext` API
* [tslog](https://github.com/fullstack-build/tslog) - A powerful logging library with native TypeScript support: beautiful interpolation, native V8 stack trace, secret masking, support for requestIds based on AsyncLocalStorage
* [tsParticles](https://github.com/matteobruni/tsparticles) - A lightweight library for easily creating particles animations for websites (Supports also ReactJS, VueJS, Angular, Svelte and others)
* [statek](https://github.com/pie6k/statek) - Reactive state management library
* [Injex](https://www.injex.dev/) - Simple, Decorated, Pluggable dependency-injection framework for TypeScript applications

# Video Courses

## Free

* [Angular Applications with TypeScript](https://mva.microsoft.com/en-US/training-courses/angular-applications-with-TypeScript-14330) (Microsoft Virtual Academy)
* [AngularJS with TypeScript made easy](https://www.youtube.com/watch?v=OZxnFB0yQHs) (SSW TV)
* [Full Stack React GraphQL TypeScript Tutorial - 14 hour course](https://www.youtube.com/watch?v=I6ypD7qv3Z8) (YouTube)

## Paid

* [TypeScript Fundamentals](https://www.pluralsight.com/courses/TypeScript) (Pluralsight)
* [Practical TypeScript Migration](https://www.pluralsight.com/courses/TypeScript-practical-migration) (Pluralsight)
* [Angular with TypeScript](http://www.pluralsight.com/courses/angular-TypeScript) (Pluralsight)
* [Using TypeScript for Large AngularJS Applications](https://www.pluralsight.com/courses/using-TypeScript-large-angularjs-apps) (Pluralsight)
* [Introduction to TypeScript](https://www.packtpub.com/application-development/introduction-TypeScript-video) (Packt)
* [Mastering TypeScript](https://www.packtpub.com/web-development/mastering-TypeScript-video) (Packt)
* [TypeScript: The Complete Developer's Guide](https://www.udemy.com/TypeScript-the-complete-developers-guide/) (Udemy)
* [Angular with TypeScript](https://www.manning.com/livevideo/angular-for-java-developers-TypeScript/) (Manning)

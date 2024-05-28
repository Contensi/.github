# Welcome to Contensi

## Projects

### Conductor Project
 - [Conductor Generator POC](https://github.com/Contensi/conductor-generator-poc)
 - [Conductor Components Examples](https://github.com/Contensi/conductor-components-example)
 - [Conductor App](https://github.com/Contensi/conductor-app)

### Perspik Project
- [Perspik API](https://github.com/Contensi/perspik-api)
- [Perspik App](https://github.com/Contensi/perspik-app)
- [Perspik Infra](https://github.com/Contensi/perspik-infra)

## Rule Book: Software Engineer Perspective

## Introduction

In this document, we list a set of rules, guidelines and specs that **must be strictly followed by any engineer at Contensi**. It is worth mentioning that while standards in Software Industry exist, yet they exist in many variations. Thus, we try to formalize the standards that we will stick to in order to achieve our goals. This document is our Code Book for software development.

## SW Engineering Department Objective

Our main objectives in our SW Engineering Department is building high quality software products and tools that enable Contensi achieving its goals. We define high quality as follows:

- Well Architected.
- Well Coded.
- Maintainable.
- Readable.
- Well Tested.
- Automated.

## Technical Skills

### Code Style

- We favor spaces over tabs unless it is part of the language syntax (ex: Golang).
- 2 spaces for HTML, CSS, JSON, Any Markup language.
- 4 spaces for the rest.
- Each file should end with an empty line. Here is why [Answer](https://stackoverflow.com/a/729795/4117381)
- We keep our code style consistent whenever we introduce a new pattern or design.
- Any line of code should not exceed 80 characters.
- We use [Trunk](https://trunk.io/products/check) to maintain our code styles. 
- For Dart, use [official guidelines](https://dart.dev/effective-dart/style).
- We recommend not committing commented code..

### Git Workflow

- We follow [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) as a branching strategy.
- We follow the following steps strictly [GitHub Flow Guidelines](https://githubflow.github.io/).
- Branches should be only merged to master via Approved Pull Requests. This means that it has to be reviewed and approved.
- Pull requests should have the followings:
  - A descriptive title
  - A description of what this PR is all about both business and technical wise.
  - Major changes and deploying instruction if any.
  - Steps to QA and run the tests.
- Branches must have a clear descriptive name prefixed by Jira task id. Sample `pers-11-create-user-endpoint`.
- We use dashes in branch naming instead of underscores.
- Each branch commit must have a clear.

### Our Engineering Practices

1. We promote Clean Architecture and Domain Driven Design in every artifacts we deliver.
   - Clean Architecture Talk: [The Principles of Clean Architecture](https://www.youtube.com/watch?v=o_TH-Y78tt4)
   - DDD: [DDD 101](https://medium.com/the-coding-matrix/ddd-101-the-5-minute-tour-7a3037cf53b8), [Bounded Context](https://github.com/ddd-crew/bounded-context-canvas)
2. Delivering Automated Tests are as important as delivering the feature itself. Delivering a feature without a sufficient organized tests is delivering an anomaly and not a delivery in any mean.
3. Before assigning a reviewer for your PR, make sure to review your code first and make sure it follows our standards.
4. We encourage pair programming practice.


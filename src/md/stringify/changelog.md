---
title: Changelog
description: Complete changelog of the Node.js csv-stringify package
keywords: ['csv', 'generate', 'changelog', 'history', 'feature', 'changes', 'version']
sort: 4
---

# Changelog

## Trunk

* travis: test agains Node.js 11
* samples: improve some scripts

## Version 4.3.1

* readme: fix links to project website

## Version 4.3.0

* package: move to csv.js.org

## Version 4.2.0

* formatter: new string formatter
* stream: be a much better transform citizen
* package: upgrade to babel 7

## Version 4.1.0

* columns: support array with column definition objects
* travis: support Node.js 10
* samples: new formatters script
* samples: update syntax
* package: improve ignore files

## Version 4.0.1

* typescript: reflect latest change in formatters

## Version 4.0.0

Backward incompatibilities:

* formatters: rename bool to boolean

New features:

* formatters: handle number

Cleanup

* src: cache call to typeof
* package: latest dependencies

## Version 3.1.1

* typescript: sync API needs to return a string

## Version 3.1.0

* typescript: add typings

## Version 3.0.0

* Switch linebreak check for rowDelimiter check

## Version 2.1.0

* package: allow empty quote value
* package: add ascii option for rowDelimiter

## Version 2.0.4

* package: move babel to dev dependencies

## Version 2.0.3

* package: es5 backward compatiblity
* package: ignore yarn lock file

## Version 2.0.2

* package: start running tests in preversion

## Version 2.0.1

* package: new release workflow
* formatters: validate returned value

## 2.0.0

This major version use CoffeeScript 2 which produces a modern JavaScript syntax
(ES6, or ES2015 and later) and break the compatibility with versions of Node.js
lower than 7.6 as well as the browsers. It is however stable in term of API.

* package: use CoffeeScript 2

## v1.1.0

* test: should require handled by mocha
* package: coffeescript 2 and use semver tilde
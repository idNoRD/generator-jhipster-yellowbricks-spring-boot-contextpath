# generator-jhipster-yellowbricks-spring-boot-contextpath

## Change target:

- File: https://github.com/jhipster/generator-jhipster/blob/main/generators/spring-boot/templates/src/main/resources/config/application.yml.ejs
- Generator: https://github.com/jhipster/generator-jhipster/tree/main/generators/spring-boot
- Purpose: Configure context-path

## For example

Assume the context-path is "/jh"
So `src/main/resources/config/application.yml` will be

```diff
server:
  servlet:
+   context-path: /jh/
    session:
      cookie:
        http-only: true
```

> JHipster blueprint, yellowbricks-spring-boot-contextpath blueprint for JHipster

[![NPM version][npm-image]][npm-url]
[![Generator][github-generator-image]][github-generator-url]
[![Samples][github-samples-image]][github-samples-url]

# Introduction

This is a [JHipster](https://www.jhipster.tech/) blueprint, that is meant to be used in a JHipster application.

# Prerequisites

As this is a [JHipster](https://www.jhipster.tech/) blueprint, we expect you have JHipster basic knowledge:

- [JHipster](https://www.jhipster.tech/)

# Installation

To install or update this blueprint:

```bash
npm install -g generator-jhipster-yellowbricks-spring-boot-contextpath
```

# Usage

To use this blueprint, run the below command

````bash
jhipster-yellowbricks-spring-boot-contextpath

You can look for updated yellowbricks-spring-boot-contextpath blueprint specific options by running

```bash
jhipster-yellowbricks-spring-boot-contextpath app --help
````

And looking for `(blueprint option: yellowbricks-spring-boot-contextpath)` like

## Pre-release

To use an unreleased version, install it using git.

```bash
npm install -g jhipster/generator-jhipster-yellowbricks-spring-boot-contextpath#main
jhipster --blueprints yellowbricks-spring-boot-contextpath --skip-jhipster-dependencies
```

[npm-image]: https://img.shields.io/npm/v/generator-jhipster-yellowbricks-spring-boot-contextpath.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-yellowbricks-spring-boot-contextpath
[github-generator-image]: https://github.com/jhipster/generator-jhipster-yellowbricks-spring-boot-contextpath/actions/workflows/generator.yml/badge.svg
[github-generator-url]: https://github.com/jhipster/generator-jhipster-yellowbricks-spring-boot-contextpath/actions/workflows/generator.yml
[github-samples-image]: https://github.com/jhipster/generator-jhipster-yellowbricks-spring-boot-contextpath/actions/workflows/samples.yml/badge.svg
[github-samples-url]: https://github.com/jhipster/generator-jhipster-yellowbricks-spring-boot-contextpath/actions/workflows/samples.yml

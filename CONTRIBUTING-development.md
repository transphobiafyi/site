# Developing transphobia.fyi

This document, in conjunction with [CONTRIBUTING.md](./CONTRIBUTING.md), describes how to set up your environment to 
contribute code to the site. These steps have only been validated in Fedora 39 - if you use a different OS
and would like to set this up, feel free to give it a try and to contribute steps of your own to help others that use
your OS.

# Tools

* Node.js
* yarn
* nvm

## Installation

### Set Up Tooling

1. Install nvm: https://github.com/nvm-sh/nvm
2. Navigate to the directory where you cloned the project
3. Run `nvm use`
4. Enable `yarn`: `corepack enable`

### Set Up The Project

```
$ yarn
```

## Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without
having to restart the server.

## Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting
service.

## CI

The site is built at the pull request level using Github actions.

## CD

Successful merges to `main` are deployed automatically to the site.

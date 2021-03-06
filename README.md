# Textpattern CMS default theme

[![Greenkeeper badge](https://badges.greenkeeper.io/textpattern/textpattern-default-theme.svg)](https://greenkeeper.io/)
[![Build Status](https://img.shields.io/travis/textpattern/textpattern-default-theme.svg)](https://travis-ci.org/textpattern/textpattern-default-theme)

[Demo](https://default-theme.textpattern.io/)

This project is the source for the default theme that ships as standard with [Textpattern CMS](https://textpattern.com/) as of v4.7.0 onwards. It is intended as a starting point for new users learning the Textpattern CMS for the first time or existing users that want to adapt their current code for modern standards, and is not intended as a finished production theme (though you could use it as such if you want to).

## Features

1. The code is commented throughout with helpful information to help you learn some of the techniques and tags available within Textpattern.
2. Current best practices gathered from all over the web - in particular the [HTML5 Boilerplate](https://html5boilerplate.com/).
3. Mobile first structure.
4. Responsive CSS layout adapts to various device screen sizes, from 320px to over 1280px.
5. Adheres to the [Schema.org microdata format](https://schema.org/).
6. Includes [Sass](http://sass-lang.com/) version of CSS for rapid development.
7. No images used at all.
8. Tested on a wide range of devices, browsers and operating systems.

## Supported web browsers

* Internet Explorer 11.
* Chrome, Edge, Firefox, Safari and Opera the last two recent stable releases.

## Requirements

Building this repository requires:

* [Node.js](https://nodejs.org/) >=4.0
* [Grunt](https://gruntjs.com/) >=1.0

## Build setup

### Installing required tools

The project uses [Grunt](https://gruntjs.com/) to run tasks and [Sass](http://sass-lang.com/) for CSS pre-processing. First make sure you have base dependencies installed: [Node.js](https://nodejs.org/) and [Grunt](https://gruntjs.com/). You can install Node using the [installer](https://nodejs.org/) and Grunt with npm:

```ShellSession
$ npm install -g grunt-cli
```

Consult the Grunt documentation for more instructions if necessary.

### Installing dependencies

After you have the base dependencies taken care of, you can install the project's dependencies. Navigate to the project's directory, and run the dependency manager:

```ShellSession
$ cd textpattern-default-theme
$ npm install
```

**npm** installs Node modules for Grunt.

## Building

This repository hosts sources and needs to be built before it can be used. After you have installed all dependencies, you will be able to run tasks using Grunt, including building:

```ShellSession
$ grunt @task@
```

Where the `@task@` is either `build` or `watch`.

* The `build` task builds the project.
* The `watch` task will launch a task that watches for file changes; the project is then automatically built if a source file is modified.

## Pre-built version

We provide a pre-built version of the theme files within the `dist` directory in case you don't want to build it yourself.

### Design patterns Textile/HTML reference page

The file `src/dev-docs/design-patterns-page.textile` is a reference you can use when authoring themes, it contains many of the HTML tags (and their equivalent [Textile](https://github.com/textile/php-textile) format where available) that should be accounted for in your designs. Paste this code directly into a Textpattern article.

## License

Licensed under the [GPLv2 license](https://github.com/textpattern/textpattern-default-theme/blob/master/LICENSE).

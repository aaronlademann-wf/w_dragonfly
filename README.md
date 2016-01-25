# Dragonfly

> __WebdriverCSS Admin Panel for Web Skin__

This repository serves as a centralized location for all __image-based regression tests__ for [Web Skin](https://github.com/Workiva/web-skin/), and [Web Skin Dart](https://github.com/Workiva/web_skin_dart/).

The application contained here helps us manage the CSS regression tests made with [WebdriverCSS](https://github.com/webdriverio/webdrivercss).
It provides an API to synchronise and configure them. This allows us to exchange the repositories amongst our UI Platform peers to be able to run regression tests decentralized.

- **NodeJS and npm**
  For installing packages.
  Download and run the [NodeJS installer](https://nodejs.org/download/).
- **Ruby, Sass, and Compass**
  Needed for Compass extension to SASS, which provides CSS niceties.
  Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
  and run `gem install compass`.

> Note: Grunt will be installed locally with npm.
  If you'd like to install Grunt globally, run `npm install -g grunt-cli`.


## Install

First download this repository and change to the project directory:

```sh
$ git clone git@github.com:webdriverio/webdrivercss-adminpanel.git
$ cd webdrivercss-adminpanel
```

Then download all client and server-side dependencies:

```sh
$ npm install
```

Last but not least, run the admin panel application on [localhost:9000](http://localhost:9000).

```sh
$ grunt serve:dist
```


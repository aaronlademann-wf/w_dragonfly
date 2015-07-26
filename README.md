# Cavendish

> __UI Platform's WebdriverCSS Adminpanel__

This repository serves as a centralized location for all __image-based regression tests__ for the [Web Skin](https://github.com/Workiva/web-skin/), [Web Skin React](https://github.com/Workiva/web-skin-react/) and [Web Skin Dart](https://github.com/Workiva/w_ui_platform/) projects.

The application contained here helps us manage the CSS regression tests made with [WebdriverCSS](https://github.com/webdriverio/webdrivercss).
It provides an API to synchronise and configure them. This allows us to exchange the repositories amongst our UI Platform peers to be able to run regression tests decentralized.


## Initial install

Download all client and server-side dependencies:

```sh
$ npm install && bower install
```


## Run the application

Runs the admin panel application on [localhost:9000](http://localhost:9000).

```sh
$ grunt serve:dist
```


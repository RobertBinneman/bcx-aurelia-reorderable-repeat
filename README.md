# bcx-aurelia-reorderable-repeat [![Build Status](https://travis-ci.org/buttonwoodcx/bcx-aurelia-reorderable-repeat.svg?branch=master)](https://travis-ci.org/buttonwoodcx/bcx-aurelia-reorderable-repeat)

An Aurelia repeater supports drag & drop reordering automatically.

## Install Package

`npm i bcx-aurelia-reorderable-repeat` or `yarn add bcx-aurelia-reorderable-repeat`

> For aurelia-cli users, please make sure to use aurelia-cli version `1.0.0-beta.1` or above.

## Usage

In your main.js file

```js
aurelia.use.plugin(PLATFORM.moduleName('bcx-aurelia-reorderable-repeat'));
```

Simply use `reorderable-repeat.for="item of items"` in your view template. That's it!

Read full documentation [here](https://buttonwoodcx.github.io/doc-bcx-aurelia-dnd/#/reorderable-repeat)

## Since v0.4.0, This plugin is bootstrapped by aurelia-cli

This repo is runable using `au run`. The dist files are not polluted by cli setup, they are generated by `au build-plugin`.

[Official Guide on how to use cli to develop plugin](https://aurelia.io/docs/plugins/write-new-plugin)

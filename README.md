Thumbprint
==========

Certificate thumbprint calculator for Node.js.

This is meant to be a transient fork of the _thumbprint_ package [until it supports Node 6](https://github.com/leandrob/thumbprint/pull/3).

## Installation

    $ npm install @auth0/thumbprint

## Usage

```javascript

var thumbprint = require('@auth0/thumbprint');

var result = thumbprint.calculate(base64Certificate);
```
# This is no official repository

**I forked this repository for publish to meteor package.**

My procedure to build this repository from typescript to available javascript as follow.

1.
Fetch the repo :

```sh
$ git clone https://github.com/n3-charts/line-chart.git
```

2.
Install the type definitions :

```sh
$ tsd reinstall -s
```

3.
Install dev dependencies :

```sh
$ npm install
```

4.
Build :

```sh
$ gulp
```

then `.tmp` folder would appear with the javascript source inside.

# n3-line-chart [![Build Status](https://travis-ci.org/n3-charts/line-chart.svg?branch=dev)](https://travis-ci.org/n3-charts/line-chart) [![Coverage Status](https://coveralls.io/repos/n3-charts/line-chart/badge.svg?branch=dev&pouet=tut)](https://coveralls.io/r/n3-charts/line-chart?branch=dev) [![Join the chat at https://gitter.im/n3-charts/line-chart](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/n3-charts/line-chart)

### Installing
```sh
$ npm install n3-charts
```

### Building
Fetch the repo :
```sh
$ git clone https://github.com/n3-charts/line-chart.git
$ git checkout dev
```

Install dev dependencies :
```sh
$ npm install
```

Install the type definitions :
```sh
$ tsd reinstall -s
```

Watch :
```sh
$ gulp watch
```

Or just build :
```sh
$ gulp
```

Run the integration tests :

```sh
$ gulp test:e2e
```

Run the demo (http://localhost:1234/test/e2e) :

```sh
$ gulp demo
```

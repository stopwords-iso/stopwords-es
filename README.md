Stopwords Spanish (ES)
=======

[![Build Status](https://travis-ci.org/stopwords-iso/stopwords-es.svg?branch=master)](https://travis-ci.org/stopwords-iso/stopwords-es)

The most comprehensive collection of stopwords for the spanish language.

A [multiple language](https://github.com/stopwords-iso/stopwords-iso) collection is also available.

### Usage

The collection comes in a
[JSON format](https://raw.githubusercontent.com/stopwords-iso/stopwords-es/master/stopwords-es.json) and a
[text format](https://raw.githubusercontent.com/stopwords-iso/stopwords-es/master/stopwords-es.txt).
You are free to use this collection any way you like.
It is only currently published on [npm](https://www.npmjs.com/stopwords-es) and [bower](https://bower.io).

```sh
$ npm install stopwords-es
```

```sh
$ bower install stopwords-es
```

```js
// Node
const stopwords = require('stopwords-es'); // array of stopwords
```

### Contributing

If you wish to remove or update some of the stopwords, please file an issue first before sending a PR on the repo of the specific language.

If you would like to add a stopword or a new set of stopwords, please add them as a new text file insie the `raw` directory then send a PR.

Please send a separate PR on the [main repo](https://github.com/stopwords-iso/stopwords-iso) to credit the source of the added stopwords.

### Credits

All stopwords sources are [listed on the main repo](https://github.com/stopwords-iso/stopwords-iso/blob/master/CREDITS.md).

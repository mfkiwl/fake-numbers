# Fake Numbers
Generate fake and valid numbers.

~~~ javascript
// Generate a fake credit card number
import fake from './src/creditCard/fake';

const creditCardNumber = fake();

// Check if a given value is a valid credit card nunber
import check from './src/creditCard/check';
check(creditCardNumber).valid;      // true
~~~

## Supported numbers

* [x] 01. BIC (Business Identifier Code)
* [x] 02. Credit card number
* [x] 03. EAN (International Article Number)
* [x] 04. IMEI (International Mobile Equipment Identity)
* [x] 05. IMO (International Maritime Organization)
* [x] 06. ISBN (International Standard Book Number)
* [x] 07. ISIN (International Securities Identification Number)
* [x] 08. ISMN (International Standard Music Number)
* [x] 09. VIN (Vehicle Identification Number): Support US only

## Command

1. Running tests

```
$ npm run test
```

## About

This project is developed by [Nguyen Huu Phuoc](https://twitter.com/nghuuphuoc).
You might be interesting in my projects:

| Product                                           | Description                                                       |
|---------------------------------------------------|-------------------------------------------------------------------|
| [Blur Page](https://blur.page)                    | A browser extension to hide sensitive information on a web page   |
| [CSS Layout](https://csslayout.io)                | A collection of popular layouts and patterns made with CSS        |
| [Fake Numbers](https://fakenumbers.io)            | Generate fake and valid numbers                                   |
| [FormValidation](https://formvalidation.io)       | The best validation library for JavaScript                        |
| [React PDF Viewer](https://react-pdf-viewer.dev)  | A React component to view a PDF document                          |

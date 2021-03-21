# Unique id generator

## DESCRIPTION

It is node package that generates a unique string of the characters as random id. It is provided set of letters and number. Set idLength parameter, determines the number of characters in the string. 
The result is printed in the console.

## PREREQUISITES

To run this package in your environment you will need Node.js and npm or yarn installed.

## INSTALATION

To install use npm 

`npm install @siem_aga/unique-id-generator`

or yarn

`yarn add @siem_aga/unique-id-generator`

## USAGE

``` js
const randomID = require('@siem_aga/unique-id-generator');

console.log(randomID(15)); // set the desired length , e.g. 15
```


# Validador de CPF
[![Build Status](https://travis-ci.org/hlays/lab-cpf-validator.svg?branch=master)](https://travis-ci.org/hlays/lab-cpf-validator)
[![Coverage Status](https://coveralls.io/repos/github/hlays/lab-cpf-validator/badge.svg?branch=master)](https://coveralls.io/github/hlays/lab-cpf-validator?branch=master)

[![link-npm](https://img.shields.io/badge/link-npm-red.svg)](https://www.npmjs.com/package/lab-cpf-validator)
![Lib version](https://img.shields.io/badge/lib-v1.0.3-blue.svg)

![JavaScript](https://img.shields.io/badge/-JavaScript-yellow.svg)
![mocha](https://img.shields.io/badge/-mocha-yellowgreen.svg)
![nyc](https://img.shields.io/badge/-nyc-brightgreen.svg)
![chai](https://img.shields.io/badge/-chai-orange.svg)

Esta biblioteca se destina a validar números de cpf.

## Como instalar:

```bash
npm i lab-cpf-validator
```

## Como utilizar:
*Formato de entrada da função: string.*

Exemplo:

```node
const cpf = require('lab-cpf-validator');

console.log(cpf('12345678909'));
// returns true
```

## Roadmap oficial do projeto

### versão 2.0.0
* entrada de dados formato string e number

### versão 1.0.0 (released)
* validação de CPF
* entrada de dados formato string

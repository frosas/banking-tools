# Banking Tools

[![Greenkeeper badge](https://badges.greenkeeper.io/frosas/banking-tools.svg)](https://greenkeeper.io/)

## Setup

```bash
$ npm i
```

## Usage

### Revolut to Buxfer

Export Revolut statement as a CSV.

```bash
$ bin/revolut-statements-to-buxfer < Revolut-XXX.csv > Revolut-XXX-fixed.csv
```

Upload to Buxfer as CSV.

## Development

```bash
$ eslint .
```
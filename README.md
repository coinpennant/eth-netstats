EOS Classic Network Stats
============
[![Build Status][travis-image]][travis-url] [![dependency status][dep-image]][dep-url]

<b>Live Version: [stats.eos-classic.io](https://stats.eos-classic.io)</b>

This is a visual interface for tracking ethereum network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface.

![Screenshot](https://raw.githubusercontent.com/eosclab/eth-netstats/master/src/images/screenshot.jpg?v=0.0.6 "Screenshot")

## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/eosclassic/eosc-netstats
cd eosc-netstats
npm install
```

## Build the resources

To build run
```bash
npm run dist
```

## Run

```bash
npm start
```

see the interface at http://localhost:3000

## Updates since original cubedro/eth-netstats base:

+ Fixed block history if chain is shorted than MAX_HISTORY

+ Fixed broken headings in Markdown files

+ Docker support added (compatible with puppeth)

+ Updated geoip-lite package to latest version (fixed location info)

+ Responsive design patch added for mobile view

+ Bug fixed with charts and formats

## To-do list

+ Update npm libraries for vulnerability patch & performance increase

+ Add average TPS calculation

+ More features with DPOS / POA!

[travis-image]: https://travis-ci.org/eosclab/eth-netstats.svg
[travis-url]: https://travis-ci.org/eosclab/eth-netstats
[dep-image]: https://david-dm.org/eosclab/eth-netstats.svg
[dep-url]: https://david-dm.org/eosclab/eth-netstats

## Credits

Originally made by [cubedro](https://github.com/cubedro/eth-netstats)

Modified by eosclassicteam for EOS Classic usage.

[travis-image]: https://travis-ci.org/eosclassic/eosc-netstats.svg
[travis-url]: https://travis-ci.org/eosclassic/eosc-netstats
[dep-image]: https://david-dm.org/eosclassic/eosc-netstats.svg
[dep-url]: https://david-dm.org/eosclassic/eosc-netstats

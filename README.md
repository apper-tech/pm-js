# Gnosis Prediction Market JS Library

[![Logo](https://raw.githubusercontent.com/gnosis/pm-js/master/assets/logo.png)](https://gnosis.pm/)

[![Build Status](https://travis-ci.org/gnosis/pm-js.svg?branch=master)](https://travis-ci.org/gnosis/pm-js)

[![Slack Status](https://slack.gnosis.pm/badge.svg)](https://slack.gnosis.pm)

## Getting Started

See the [documentation](https://gnosis-apollo.readthedocs.io/en/latest/pm-js.html).

## Really quick start

1. Get [Ganache-cli](https://github.com/trufflesuite/ganache-cli)
   ```sh
   npm install -g ganache-cli
   ```
2. Run this:
   ```sh
   ganache-cli -d -i 437894314312
   ```
3. Clone [pm-contracts](https://github.com/gnosis/pm-contracts), cd in there, and migrate the contracts onto the Ganache-cli instance with:
   ```sh
   cd path/to/pm-contracts
   npm install
   npm run migrate -- --network quickstart
   ```
4. Download [`gnosis-pm.js`](https://raw.githubusercontent.com/gnosis/pm-js/master/dist/gnosis-pm.js) and put it in an HTML file:
   ```html
   <script src="gnosis-pm.js"></script>
   ```

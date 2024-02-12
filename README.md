# TON inscription assets info

## Overview

The repository contains inscription assets on TON blockchain.

## How to add assets

Folder name:

URL-safe encode tick lowercase to Base64 format.
For example, if your tick is `NANO`:
1. To lowercase: `NANO` -> `nano`
2. URL-safe encoding: `nano` -> `bmFubw`. You can perform encoding on [base64encode](https://www.base64encode.org/)

info file fields:

- `tick`: inscription tick
- `description`: a few sentence summary of the ticker

## Disclaimer

Tonano team allows anyone to submit new assets to this repository. However, this does not mean that we are in direct partnership with all of the inscriptions.

Tonano team will reject assets that are deemed as scam or fraudulent after careful review.Tonano team reserves the right to change the terms of assets submissions at any time due to changing market conditions, risk of fraud, or any other factors we deem relevant.

## License

The documentation in this project are released under the [MIT License](LICENSE)
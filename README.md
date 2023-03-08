# Open Contracts
[![TON](https://img.shields.io/badge/based%20on-TON-blue)](https://ton.org/)
[![License](https://img.shields.io/badge/license-GPL--3.0-brightgreen)](https://opensource.org/licenses/GPL-3.0)

A collection of open source, standalone FunC contracts/snippets for the TON blockchain.

## Overview
### Installation
Use GitHub repository to install contracts:
```
$ wget https://raw.githubusercontent.com/TonoxDeFi/open-contracts/main/contracts/<lib>/<lib>.func
```
Replace `<lib>` with the name of the library you want to install.

Currently available libraries:
- [messages.func](contracts/messages/README.md)
- [math.func](contracts/math/README.md)
- [strings.func](contracts/strings/README.md)
- [tuples.func](contracts/tuples/README.md)
- [utils.func](contracts/utils/README.md)
- [crypto.func](contracts/crypto/README.md)
- [slices.func](contracts/slices/README.md)

### Usage
Import the library into your contract:
```c
#include "<lib>.func";
```
You can check the usage and examples in README.md of the library itself.

## Contribute
open-contracts exists thanks to all the people who contribute. PR are welcome!
You can also sponsor the project by donating TON or any Jetton to the following address:
```
EQDnLXD_E_U7ZZO6k57Fpyp6flVy4QetQSbUUOtFuORn1nu7
```
## License
Licensed under the [MIT License](LICENSE).
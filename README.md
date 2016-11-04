# cpp-ethereum - Ethereum C++ client (Ethereum Classic Blockchain)

[![Join the chat at https://gitter.im/ethereumproject/cpp-ethereum](https://badges.gitter.im/ethereumproject/cpp-ethereum.svg)](https://gitter.im/ethereumproject/cpp-ethereum?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Travis CI Build Status](https://travis-ci.org/ethereumproject/cpp-ethereum.svg?branch=develop)](https://travis-ci.org/ethereumproject/cpp-ethereum/branches)
[![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/vslpgeb3mwya8bh0/branch/develop?svg=true)](https://ci.appveyor.com/project/igetgames/cpp-ethereum-lrwsa/branch/develop)

This repository contains cpp-ethereum, the [Ethereum Classic](https://ethereumclassic.github.io/) C++ client. It is a fork
of [cpp-ethereum](http://cpp-ethereum.org/), the [Ethereum](http://ethereum.org) C++ client. This repository is maintained by
the Ethereum Classic development team. At some point Ethereum and Ethereum Classic may diverge into separate networks. In any
case, this version of cpp-ethereum should only be used to operate on the Ethereum Classic blockchain. 

It is the third most popular of the Ethereum clients, behind [geth](https://github.com/ethereum/go-ethereum) (the [go](https://golang.org)
client) and [Parity](https://github.com/ethcore/parity) (the [rust](https://www.rust-lang.org/) client).  The code is exceptionally
[portable](http://cpp-ethereum.org/portability.html) and has been used successfully on a very broad range
of operating systems and hardware.

The Ethereum development team is working to [re-license](https://bobsummerwill.com/2016/07/12/c-re-licensing-plan/) cpp-ethereum and
supporting libraries from the [GPLv3](https://en.wikipedia.org/wiki/GNU_General_Public_License) license to the
[Apache 2.0](https://en.wikipedia.org/wiki/Apache_License) license:
```
We are in the process of re-licensing the codebase from the copyleft
GPLv3 license to the permissive [Apache 2.0] licence, to enable Ethereum
to be used as broadly as possible.  There is a long-form article -
"Ethereum Everywhere" (https://bobsummerwill.com/2016/07/12/ethereum-everywhere/) - 
which talks about the rationale for the change and the history leading
up to this proposed change of licensing.
```

## Getting Started

The Ethereum Documentation site hosts the **[cpp-ethereum homepage](http://cpp-ethereum.org)**, which
has a Quick Start section.

Come and find us on the Ethereum Classic [Slack](http://ethereumclassic.herokuapp.com/) in the [#development](https://ethereumclassic.slack.com/messages/development/)
channel if you have any questions or suggestions.

## Contributing

The current codebase is the work of many, many hands, with nearly 100
[individual contributors](https://github.com/ethereumproject/cpp-ethereum/graphs/contributors) over the course of its development.

All contributions are welcome! If you have any questions, please just ask.

Please read [CodingStandards.txt](CodingStandards.txt) thoroughly before making alterations to the code base.
Please do *NOT* use an editor that automatically reformats whitespace away from astylerc or the formatting guidelines
as described in [CodingStandards.txt](CodingStandards.txt).

All development goes in develop branch.

## Testing

To run the tests, make sure you clone https://github.com/ethereum/tests and point the environment variable
`ETHEREUM_TEST_PATH` to that path.

## License

All contributions are made under the [GPLv3 license](http://www.gnu.org/licenses/gpl-3.0.en.html). See [LICENSE](LICENSE).

We are in the process of re-licensing to Apache 2.0.   See above for more details.

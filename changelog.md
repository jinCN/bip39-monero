# 0.3.11

* Add NIX network
* Fix coin parameters for NMC, XMY, CLAM, ONX, LKR
* Add DEXON network
* Add Nebulas network
* Add LSP network
* Fix Crown network address format
* Add Ellaism network
* Add Etheresocial network
* Add Bolivarcoin network
* Force spellcheck and autocomplete to be off

# 0.3.10

* Add Phore network
* Add Blocknode network
* Add Ravencoin network
* Add Safecoin network
* Add LitecoinZ network
* Add LKRcoin network
* Update Peercoin scripthash parameter
* Add Blockstamp network
* Remove old info regarding use of private keys

# 0.3.9

* Update BTG signing message
* Add segwit parameters for BTG
* Add segwit parameters for DigiByte
* Add Stash network (see 0.3.8s below)
* Add Salus network
* Add Cryptoescudo network
* Add ExchangeCoin network
* Add Artax network
* Add BitCloud network
* Add Megacoin network
* Add Bitcoin Green network
* Add ANON network
* Add ProjectCoin network
* Reword the 'generate' inputs and words
* Add note for running http server in python 2
* Adjust test to run reliably on slow computers

# 0.3.8s

* Add Stash network

# 0.3.8

* Add p2wpkh for litecoin
* Add more networks - TSTRAT, Hush, ETC, PIRL, CLO, MIX, MUSIC, POA, EXP
* Add coinomi/ledger client to BIP32 tab
* Fix SYSCOIN and BTX parameters
* Remove bip39-standalone.html from repository
* Remove duplicate id properties on html elements

# 0.3.7

* Update AXE network parameters
* Add new networks - Xuez, BTCP, BTCZ, ZCL, ZEN
* Add litecoin bech32 params
* Fix BIP38 for altcoins
* Fix missing span closing tag
* Add indicator to UI for when BIP84 is unavailable
* Replace hasSegwit variable with test for segwit params
* Allow xpub to be used as root key for segwit derivations
* Add visual privacy safeguard

# 0.3.6

* Add Kobocoin
* Update Vertcoin version byte and segwit support
* Add Zcash
* Korean mnemonics use ascii spaces
* Add CashAddr address format for bitcoin cash

# 0.3.5

* Fix typo
* Add Neblio network
* Update bitcoinjs-lib from 3.3.0 to 3.3.2
* Add Beetle Coin
* Add segwit for bitcoin testnet and Fujicoin
* Set coin number for Bitcoin God to 156
* Add coins supported by coinomi
* Warn when generating low entropy mnemonics
* Warn when overriding weak entropy with a strong mnemonic length

# 0.3.4

* Add BlackCoin
* Add Denarius
* Raw entropy shows groupings with space every 11 bits
* Checksum shown in entropy details
* Warn that entropy values should exclude checksum
* Add Korean language

# 0.3.3

* Add AXE network
* Ethereum private key generation bugfix
* Add BIP38 support
* Allow initial number of rows to be set by the user

# 0.3.2

* Add Onixcoin
* Add Komodo
* BIP84 tab for derivation path
* CSV tab for derived addresses

# 0.3.1

* Populate entropy field with hex value used from PRNG
* Show list of word indexes
* Fix typos
* Update jquery from 2.1.1 to 3.2.1
* Update bootstrap from 3.2.0 to 3.3.7
* Move application-specific css into own file
* QR codes with accents work correctly by replacing jquery.qrcode with kjua

# 0.3.0

* Update bitcoinjs from 3.1.1 to 3.3.0
* Litecoin defaults to ltub instead of xpub
* Segwit option removed from bip32 tab
* BIP141 tab added for full segwit compatibility

# 0.2.9

* Update links from old site to new site
* Add Monacoin
* Add Bitcoin Gold
* Port test suite to selenium
* Allow more rows to be generated starting from a custom index

# 0.2.8

* Enable segwit for Litecoin
* BitPay-style addresses for Bitcoin Cash
* Use new xpub/xprv prefixes for Segwit BIP49
* Add nubits network

# 0.2.7

* Add Fujicoin
* List alternative tools
* Remove unused translations and library

# 0.2.6

* Detect and warn when entropy is filtered / discarded
* Reword entropy text to indicate using a single source only
* Add BIP49 to More Info section
* Update compile script to work across python 2 and 3
* QR Codes use correctLevel 3 instead of 2
* Source map removed from zxcvbn
* Tidy up code with consistent use of commas and semicolons

# 0.2.5

* Rename variables for clarity between BIP49 and P2WPKH Nested In P2SH
* Fix bug for validation of root key when using non-bitcoin networks
* Add option to use P2WPKH Nested In P2SH addresses on BIP32 tab

# 0.2.4

* Show error when using xpub with hardened addresses
* Allow switching litecoin prefixes between xprv and Ltpv

# 0.2.3

* Add maza coin

# 0.2.2

* Improve showing feedback for pending calculations
* Bugfix: Clear old seed when mnemonic is changed
* Add PIVX network

# 0.2.1

* BTC is the default coin
* Add myriadcoin
* Add Bitcon Cash

# 0.2.0

* BitcoinJS library upgrded to v3.1.1
* Tab order is alphabetical
* BIP44 'purpose' and 'coin' fields are readonly
* Refactor method to clear old data from the display
* BIP49 support
* Release process is documented

# 0.1.2

* Add Crown network
* Network names are displayed with currency code

# 0.1.1

* Add DASH Testnet
* Change entropy Strength to Time To Crack

# 0.1.0 2017-06-14

* Add changelog
* Display version number in top right
* Add hex prefix to ethereum keys

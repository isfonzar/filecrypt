<p align="center"><img src="http://i.imgur.com/yIXu97n.png"></p>

<p align="center">
<a href="https://github.com/isfonzar/filecrypt"><img src="https://img.shields.io/badge/Language-Go-blue.svg" alt="Language"></a>
<a href="https://goreportcard.com/report/github.com/isfonzar/filecrypt"><img src="https://goreportcard.com/badge/github.com/isfonzar/filecrypt" alt="GoReportCard"></a>
<a href="https://github.com/isfonzar/filecrypt/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"></a>
<a href="https://github.com/isfonzar/filecrypt/releases"><img src="https://img.shields.io/badge/Status-Beta-brightgreen.svg" alt="Status"></a>
</p>

## About filecrypt

filecrypt is a Go library to easily encrypt and decrypt files using the GCM encryption.

## Installation

### Option 1: Go Get

```golang
import "github.com/isfonzar/filecrypt"
```

## Usage

```golang
// Encrypts a file
filecrypt.Encrypt(file, password)

// Decrypts a file
filecrypt.Decrypt(file, password)
```

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/isfonzar/filecrypt/issues) to report any bugs or file feature requests.

### Developing

PRs are welcome. To begin developing, do this:

```bash
$ git clone --recursive git@github.com:isfonzar/CryptoGo.git
$ cd CryptoGo/
```

## Social Coding

1. Create an issue to discuss about your idea
2. [Fork it] (https://github.com/isfonzar/filecrypt/fork)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request
7. Profit! :white_check_mark:

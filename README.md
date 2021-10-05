# SailsJs 1.4 + VueJs 3.0 Boilerplate
Boilerplate for SailsJs with VueJs to run in a single domain.

## Installation

### Prerequisites

To get started, you need Node.js. It's also recommend to have Sails.js globally installed. Finally, install the Node.js modules.

#### Get Node.js

```bash
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

#### Get Sails.js (optional)

```bash
$ sudo npm install sails -g
```

#### Install modules

```bash
$ npm install
```

## Usage

### Development

```bash
$ npm run dev
```

After that, open [localhost:1337](http://localhost:1337) in your browser.

Also you could run client & server separately in case it requires.

```bash
$ npm run server
$ npm run client
```

Open server in [localhost:1337](http://localhost:1337) and client in [localhost:8080](http://localhost:8080)

### Production

```bash
$ npm run prod
```

After that, open [localhost:1337](http://localhost:1337) in your browser.

Tuesmon events
============

[![Kaleidos Project](http://kaleidos.net/static/img/badge.png)](https://github.com/kaleidos "Kaleidos Project")
[![Managed with Tuesmon.com](https://img.shields.io/badge/managed%20with-TUESMON.io-709f14.svg)](https://manage.tuesmon.com/project/tuesmon/ "Managed with Tuesmon.com")

The Tuesmon websocket server.

Installation
------------

> *NOTE:* You should use node >= 6.0 

Install the RabbitMQ service.

```bash
  apt-get install rabbitmq-server
```

Install the javascript dependencies.

```bash
  npm install
```

Install globally the coffeescript interpreter.

```bash
  sudo npm install -g coffee-script
```

Copy and edit the config.json file.

```bash
  cp config.example.json config.json
```

Then run the tuesmon events service

```bash
  coffee index.coffee
```

You can specify you own config path

```bash
  coffee index.coffee --config /path/to/config.json
```

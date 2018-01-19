# Foxbit_Bot
Bot Automatic Trader Foxbit - Buy & Sell.

Using API  [Blinktrade](https://blinktrade.com/docs/#trade-api).

![Panel](http://image.prntscr.com/image/6c2313f622e34b52b7d309179ddeeb42.png)

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed (v8.9.3) and Npm (5.5.1) too!

```sh
$ git clone https://github.com/wendellpalazzo/Foxbit_Bot # or clone your own fork
$ cd Foxbit_Bot
$ npm install
$ NODE_ENV=production node index.js
```

Your app should now be running on [localhost:3000](http://localhost:3000/).

## Config the config.json file with the key and secret information

```
{
  "key": "YOUKEY",
  "password": "YOUPASSWORDAPI",
  "secret": "YOUKEYSECRET",
  "currency": "BRL",
  "brokerId": "4"
}
```


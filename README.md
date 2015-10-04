# Amazon Dash Rickroll
This is a node.js application to Rickroll somebody who presses your Amazon Dash button.


## Demo

See the action in 6sec on [Vine](https://vine.co/v/e2m3emJZVqB)!

![Rick button](rick-button.jpg "Dash to Rickroll")



## Running the App on your Local Machine

### Requirement

Make sure you have node.js running on your machine.

### Setup

First, install the dependency. This app uses `node-dash-button`:

```bash
$ npm install
```

Before running this app, you need to obtain your dash's MAC address. 

```bash
$ cd node_modules/node-dash-button
$ node bin/findbutton
```

See this [instruction](https://github.com/hortinstein/node-dash-button#find-a-dash) for more details.

Create a `config.js file` with your Dash's MAC address.

```javascript
module.exports = {
  dash: {
    MAC_address: '2c:f0:xx:xx:fc:xx'
  }
};
``` 

Run

```bash
$ sudo node index.js
```

---


Thank you, Alex Hortin (hortinstein) for creating [node-dash-button](https://github.com/hortinstein/node-dash-button)!


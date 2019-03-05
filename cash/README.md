# cash

> Convert the currency you want into currencies you want.

## Installation

```sh
❯ npm install
```

## Usage
```js
const command = {
	amount: parseFloat(argv[0]) || 1,
	from: argv[1] || config.get('defaultFrom', 'EUR'),
	to: (argv.length > 2) ? process.argv.slice(4) : config.get('defaultTo', DEFAULT_TO_CURRENCIES)
};
```

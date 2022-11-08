# React Currency Symbols

This package is an export of all world collection of currncy symbols, you can use this symbols on either react js or react native projects.

To get you started run:
`npm install @bilmapay/react-currency-symbols`

---

### Or for yarn lovers

`yarn add @bilmapay/react-currency-symbols`

# Documentation

There is nothing to document since the project is just an object export for example if you want to import and use a currency you can do so by import it like this:

```js
import { NAIRA_SIGN } from "@bilmapay/react-currency-symbols"

// and then use it like thise

export default function App() {
	return <span className="currency">{NAIRA_SIGN}</span>
}

// For react Native

export default function App() {
	return <Text style={styles.currency}>{NAIRA_SIGN}</Text>
}
```

# A Very Big Thanks!

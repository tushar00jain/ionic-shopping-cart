# ionic-shopping cart

A shopping cart app built with ionic alongside mean stack

```
cd server
npm install
```

```
cd src
npm install
bower install
```

```
mongostore -d test -c categories server/dump/test/categories.bson
mongostore -d test -c products server/dump/test/products.bson
node server/index.js
ionic serve --lab
```
Complete 'server/config.json'

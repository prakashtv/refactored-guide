## Prerequisites

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/en/)

## Installation

```bash
git clone https://github.com/prakashtv/shopify-products-listing-app
yarn install
```

## Configuring

If you would like to connect your store to this example, open up `src/graphql-js-client.js` and update the `url` and `Authorization` header:
```js
export default new Client(typeBundle, {
  url: 'https://your-shop-name.myshopify.com/api/graphql',
  fetcherOptions: {
    headers: {
      'X-Shopify-Storefront-Access-Token': 'your-storefront-access-token'
    }
  }
});
```

## Running

* `yarn start`
* View the example at [http://localhost:4200](http://localhost:4200).



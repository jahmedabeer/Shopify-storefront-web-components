# Shopify Storefront Web Components - Headless eCommerce

Storefront Web Components let you bring Shopify-powered commerce capabilities to any website. Display products, showcase collections, and offer a checkout, all with a few lines of embedded HTML. Storefront Web Components are a set of HTML components that handle the complexity of querying Shopify's Storefront API.

## GraphQL Connections in Web Components

To iterate through connection data, use `<shopify-list-context>` with the connection query:

```html
<!-- List all products from a connection -->
<shopify-list-context query="products" type="product" first="10">
  <template>
    <shopify-data query="product.title"></shopify-data>
  </template>
</shopify-list-context>
```

## Documentation

- [Getting Started](https://shopify.dev/docs/api/storefront-web-components/getting-started)
- [Storefront API](https://shopify.dev/docs/api/storefront)
- [Product objects](https://shopify.dev/docs/api/storefront/latest/objects/product)
- [Selling Plan](https://shopify.dev/docs/api/storefront/latest/objects/SellingPlan)
- [Headless app](https://apps.shopify.com/headless)
- [Playground](https://webcomponents.shopify.dev/playground)

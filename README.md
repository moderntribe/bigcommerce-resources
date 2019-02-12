# BigCommerce Plugin Resources

The Resources page in the plugin admin will show a collection of resources
that can be used to enhance, extend, and support the BigCommerce plugin
for specific use cases.

The page is powered by an API that returns the collection of resources
as a JSON object.

This repository maintains the data returned by said API.

```
wp bigcommerce resources build --pretty resources.csv > resources.json
```
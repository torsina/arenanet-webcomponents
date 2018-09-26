# arenanet-webcomponents

This is a repository of mithril components and CSS, to easy include and access across multiple arenanet products.

## Including

First, include the npm project

```bash
# Install
npm install https://github.com/arenanet/arenanet-webcomponents.git
# Update
npm update arenanet-webcomponents
```

To use as a dependency from your js, include like so:

```js
import exampleComponent from "arenanet-webcomponents/js/example-component.js";
import exampleCss from "arenanet-webcomponents/css/example-style.css";

// exampleComponent is accessible as usual
// exampleCss is accessible as usual
```

## Contributing

To contribute
 1. Fork this repo
 2. Add your code directly to the `/css` or `/js` directories. 
 3. To make your code available in the latest npm module, make sure to increment the `version` number in your final release.
 4. Submit PR

Just pass a UAST to the component and it will be rendered.

The original UAST must be converted to a flat structure.
The library provides a default transformer function for this purpose.

```js
const { transformer } = require('uast-viewer');

<UASTViewer uast={transformer(uast)} />
```

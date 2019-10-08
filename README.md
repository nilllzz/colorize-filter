# colorize-filter

JS Module to apply a hex color to an image through css filters

# Installation

```sh
npm install colorize-filter --save
yarn add colorize-filter
```

# Usage

### Javascript

```javascript
var colorizeFilter = require("colorize-filter");
var filter = colorizeFilter.generateFilter("dead00");
console.log(filter);
```

Output should be `invert(75%) sepia(89%) saturate(3406%) hue-rotate(13deg) brightness(101%) contrast(104%)`.

### Typescript

```typescript
import { generateFilter } from "colorize-filter";

const filter = generateFilter("dead00");
console.log(filter);
```

Output should be `invert(75%) sepia(89%) saturate(3406%) hue-rotate(13deg) brightness(101%) contrast(104%)`.
